#Proje 2
##[16,21,11,8,12,22] -> Merge Sort

**Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.**

dizi ikiyi ayrılır [16,21,11] ve [8,12,22]. Bunlar tekrar ikiye ayrılır ve sonra küçükten büyüğe doğru sıralanarak birleştirilir.
[16,21,11]-> [16] ve [21,11] --> 16<21, 16>11 o zaman [11,16,21]
[8,12,22]-> [8,12] ve [22] --> 8<12-> 8 en başa gelir. 12<22 -->[8,12,22]
daha sonra bu iki dizi tekrar sıralamaya  sokulur.

[11,16,21] ve [8,12,22]--> diziler soldan sağa büyüdüğü için en soldan başlayarak karşılaştırma yapılır.
 11>8-> 8 en başa yazılır.
 11<12-> 11 yazılır.
 16>12-> 12 yazılır. 
 16<22->16 yazılır.
 21<22->21 yazılır.
 En sona 22 yazılır.
 [8,11,12,16,21,22]

**Big-O gösterimini yazınız.**

O(nlogn)