# InsertionSortProjesi
Kodluyoruz Insertion Sort Projesi
## Proje 1
**[22,27,16,2,18,6]** -> Insertion Sort
1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2.Big-O gösterimini yazınız.
3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
 **[7,3,5,8,2,9,4,15,6]** dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
 1.ADIM:[2,3,5,8,7,9,4,15,16]
 2.ADIM:[2,3,4,8,7,9,5,15,16]
 3.ADIM:[2,3,4,5,7,9,8,15,16]
 4.ADIM:[2,3,4,5,7,8,9,15,16]
 
**Big-O gösterimini yazınız.** 
-o(n²)
**3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.**

Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
**CEVAP**:Time Complexity: Average case

**Merge Sort Projesi**
***Proje 2***
 [16,21,11,8,12,22]
 Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
- [16,21,11,8,12,22] yarıya bölüyoruz.
- [16,21,11][8,12,22] ve bunlarıiki grubu sıralıyoruz.
- [11,16,21][8,12,22] sıraladık şimdi iki grubumuz da sıralı iki gruba bakarak küçükten büyüğe veya istersek  büyükten küçüğe sıralıyoruz.
- [8,11,12,16,21,22]sıraladık normalden logn kadar hızlı yaptık .
Big-O gösterimini yazınız.
- o(logn)

**Binary Search Tree Projesi**

***Proje 3 ***
[7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız.

- root 7'dir.Ve büyük küçük ilişkisi kurarak sağsol yapacağız.şimdi başalayalım.
- root 7 sıradaki sayı beş , beş yediden küçük olduğundan dolayı sol tarafa yazarız ve diğer sayıya geçeriz.
- bir diğer sayımız 1,7'den küçük sol tarafa geçer 5'ten de küçük olduğundan dolayı yine sol tarafa geçer.
- 8 , 7'den büyük sağ tarfa geçer ve diğer sayıya geçeriz.
- 3,7'den küçük sol tarafa geçer 5'ten de küçük 1'den büyük 1'in sağ tarafına geçer diğer sayımıza geçeriz.
- 6,7'den küçük sol tarafa geçer 3'ten büyük sağına geçer.
- 0, 7'den küçük sol tarafa 6'nın sol tarafına geçer .
- 9, 7'den büyüktür sol tarafa 8'den de büyük sağ tarafına geçer.
- 4,'den küçük sol tarafa geçer 0'dan büyük sağ tarafa geçer.
- 2,7'den küçük sol tarafa geçer 4'den de küçük olduğundan dolayı sol tarfa geçer ve burada işimizi tamamlarız çok kısa bir şekilde işimizi tamamlamış olduk.


