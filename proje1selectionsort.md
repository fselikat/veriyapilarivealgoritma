#Proje 1
##[22,27,16,2,18,6] -> Insertion Sort

**Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.**

[22,27,16,2,18,6]-> en küçük sayıyı arar sırayla bakar, 2'yi bulur ve baştaki değerle yerini değiştirir.->[2,27,16,22,18,6]
[2,27,16,22,18,6]-> 2. en küçük sayıyı arar sırayla bakar 6'yı bulur ve 2. sıradakielemanla yerlerini değiştirir -> [2,6,16,22,18,27]
[2,6,16,22,18,27]-> 3. en küçük sayıyı arar 16'yı bulur zaten 3. sırada olduğu için değiştirmez -> [2,6,16,22,18,27]
[2,6,16,22,18,27]-> 3. en küçük sayıyı arar 18'i bulur ve 4. sıradaki 22 ile yerini değiştirir-> [2,6,16,18,22,27]
[2,6,16,18,22,27]-> 4. ve 5. elemanlarını kontrol eder, elemanlar küçükten büyüğe sıralı olduğu için değişiklik yapmadan işlem biter.


**Big-O gösterimini yazınız.**

selection sort için Big-O ->O(n^2) olur.

**Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız**

*Average case: Aradığımız sayının ortada olması*
*Worst case: Aradığımız sayının sonda olması*
*Best case: Aradığımız sayının dizinin en başında olması*


Dizi sıralandıktan sonraki hali [2,6,16,18,22,27] olduğu için 18 ortada bulunacağından average case kapsamına girer.



**[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.**


[7,3,5,8,2,9,4,15,6]-> dizinin en küçük elemanını arar 2'yi bulur başlangıç(7) ile yerini değiştirir.->[2,3,5,8,7,9,4,15,6]
[2,3,5,8,7,9,4,15,6]->en küçük ikinci elemana bakar 3'ü bulur zaten 2. sırada olduğu için yerini değiştirmez.
[2,3,5,8,7,9,4,15,6]->en küçük üçüncü elemana bakar 4'ü bulur  3. sıradaki elemanla (5) yerini değiştirir.->[2,3,4,8,7,9,5,15,6]
[2,3,4,8,7,9,5,15,6]->en küçük dördüncü elemana bakar 5'i bulur, 4. sıradaki elemanla(8) yerini değiştirir->[2,3,4,5,7,9,8,15,6]