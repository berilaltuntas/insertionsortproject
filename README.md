# Data Structures Proje 1
-----

## Kodluyoruz Eğitimi Data Structures Ödevi 1


Proje 1
---
**[22,27,16,2,18,6]** -> Insertion Sort

**Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.**

**Big-O gösterimini yazınız.**

**Time Complexity:** Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

1. Average case: Aradığımız sayının ortada olması
2. Worst case: Aradığımız sayının sonda olması
3. Best case: Aradığımız sayının dizinin en başında olması.

.


**[7,3,5,8,2,9,4,15,6]** dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

---
## Yanıtlar

Dizi: **[22,27,16,2,18,6]**

1. Dizinin en küçük elemanı en başa gelir ve 22 sayısı ile yer değiştirir.
   
    **[2,27,16,22,18,6]**

2. Bir sonraki elemana geçilir, bir sonraki en küçük eleman 27 sayısı ile yer değiştirir.

    **[2,6,16,22,18,27]**

3. Sonraki en küçük eleman 16, zaten yerinde olduğu için işlem yapulmaz.

    **[2,6,16,22,18,27]**

4. Bir sonraki en küçük eleman 18, 22 sayısı ile yer değiştirir. Bu aşamadan sonra sona kalan elemanlara bakılır zaten yerleşmiş oldukları için işlem yapılmaz.

    **[2,6,16,18,22,27]**


**Big O Notation :** O(n^2)

**Time Complexity:** Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? 
---
-***Average case*** 


**[7,3,5,8,2,9,4,15,6]** dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

1. **[2,3,5,8,7,9,4,15,6]**
2. **[2,3,4,8,7,9,5,15,6]**
3. **[2,3,4,5,7,9,8,15,6]**
4. **[2,3,4,5,6,9,8,15,7]**
---