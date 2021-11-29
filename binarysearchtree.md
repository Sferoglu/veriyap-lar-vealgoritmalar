# **Binary Search Tree Projesi**
## **[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.** 

                  4
              1        7
           0    3    5    8
              2       6     9
          
### Root 4'tür
```
1- 1 eklenmek istenmiş ve 4'ten küçük olduğundan kökün soluna eklenmiştir

2- 7 eklenmek istenmiş ve 4'ten büyük olduğundan kökün sağına eklenmiştir

3- 3 sayısı eklenmek istenmiş, 4'ten küçük olduğundan soldaki subtreeye geçilmiş, oradaki değer olan 1'den ise büyük olduğundan onun sağına doğru dallanmıştır

4- 2 sayısı eklenmiş ve 4'ten küçük olduğundan soldaki subtreeye geçilmiş, oradaki değer olan 1'den ise büyük olduğundan onun sağındaki subtreeye geçilmiş. burada bulunan değer olan 3'ten ise küçük olduğundan sola doğru dallanmıştır

5- 8 sayısı eklenmek istenmiş ve 4'ten büyük olduğundan sağdaki subtreeye geçilmiş, burada bulunan değer olan 7'den daha büyük bir değer olduğundan sağa doğru dallanmıştır.

6- 9 sayısı eklenmek istenmiş ve 4'ten büyük olduğundan sağdaki subtreeye geçilmiş, burada bulunan değer olan 7'den daha büyük bir değer olduğundan sağdaki subtreeye geçilmiş, burada bulunan değer olan 8 sayısından daha büyük bir değer olduğundan sağa doğru dallanmıştır.

7- 0 sayısı eklenmek istenmiş ve 4'ten küçük olduğundan soldaki subtreeye geçilmiş, oradaki değer olan 1'den küçük olduğundan sola doğru dallanmıştır.

8- 5 sayısı eklenmek istenmiş ve 4'ten büyük olduğundan sağdaki subtreeye geçilmiş, burada bulunan değer olan 7'den daha küçük bir değer olduğundan sola doğru dallanmıştır.

9- 6 sayısı eklenmek istenmiş ve 4'ten büyük olduğundan sağdaki subtreeye geçilmiş, burada bulunan değer olan 7'den daha küçük bir değer olduğundan soldaki subtreeye geçilmiş, buradaki 5 değerinden büyük olduğundan sağa doğru dallanmıştır. 
```

