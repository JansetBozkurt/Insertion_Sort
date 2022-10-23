# Insertion_Sort
##### Patika.dev'in Veri Yapıları ve Algoritmalar eğitiminin ilk projesidir. 

## **[22,27,16,2,18,6] -> Insertion Sort**

**1.Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.** 

- [2,27,16,22,18,6] En küçük sayının 2 olduğunu belirleriz. 2 ve 22'nin yerini değiştiririz.
- [2,6,16,22,18,27] 2 haricinde en küçük sayı 6. 6 ve 27'nin yerini değiştiririz.
- [2,6,16,22,18,27] 16 üçüncü en küçük sayı olduğundan yerini değiştirmedik.
- [2,6,16,18,22,27] 18 ve 22'nin yeri değiştirildi.
- [2,6,16,18,22,27] Sıradaki sayı 22. Yer değiştirilme yapılmadı.
- [2,6,16,18,22,27] Sıradaki sayı 27. İstenen sıralama bulunduğundan yer değiştirilmesi yapılmadı.

**2.Big-O gösterimini yazınız.**
- Worst Case: O(n^2)
- Avarage Case: o(n^2)
- Best Case: O(n)

**3.Time Complexity:**
- Best Case: [2,6,16,18,22,27]
- Worst Case: [27,22,18,16,6,2]

**4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?**
- Dizi sıralandıktan sonra [2,6,16,18,22,27] olur. Bu durumda 18 sayısı başta ve sonda olmadığı için Avarage Case kapsamında yer alır.


## [7,3,5,8,2,9,4,15,6] dizisinin Intersion Sort'a göre ilk 4 adımını yazınız.

- [2,3,5,8,7,4,15,6] En küçük sayının 2 olduğu bulundu. 2 ve 7 yer değiştirildi. 
- [2,3,5,8,7,4,15,6] 3 olması gerektiği yerde olduğundan sabit kaldı.
- [2,3,4,8,7,5,15,6] 4 ve 5 yer değiştirildi.
- [2,3,4,5,7,8,15,6] 5 ve 8 yer değiştirildi.
