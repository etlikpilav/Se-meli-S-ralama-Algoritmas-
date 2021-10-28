# Se-meli-S-ralama-Algoritmas-
/*
Secmeli Sıralam bilgisaray bilimlderinde kullanılan bir sıralama algoritmasıdır.
O (N'2) olduğu icin büyük listeler üzerinde kullanıldığında verim sağlamaz ve genel olarak benzeri olan.
 eklemeli sıralamadan daha başarısızdır. Seçmeli sıralama yalın olduğu ve bazı durumlarda daha karmaşık olan.
 algoritmalardan daha iyi sonuç verdiği için tercih edilebilir.
 */ 
 
 *
YÖNTEM
Algoritma aşağıdaki gibi çalışır:
1- Listedeki en küçük değerli öğeyi bul.
2- İlk konumdaki öğeyle bulunan en küçük değerli öğenin yerini değiştir.
3- ukarıdaki adımları listenin ilk elemanından sonrası için (ikinci elemandan başlayarak) yinele.

 */
 
 *
import java.util.*; class Main{ // Driver method to test above public static void
main(String args[]) { //declare an array of integers int intArray[] =
{23,43,13,65,11,62,76,83,9,71,84,34,96,80}; //print original array
System.out.println('Original array: ' + Arrays.toString(intArray)); int n =
intArray.length; //iterate over the array comparing adjacent elements for (int i = 0; i
intArray[j+1]) { int temp = intArray[j]; intArray[j] = intArray[j+1]; intArray[j+1] =
temp; } //print the sorted array System.out.println('Sorted array: ' +
Arrays.toString(intArray)); } }
 */
