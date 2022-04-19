# Binary Search Tree
## Soru
> [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
> Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
## Cevap
```
[0, 1, 2, 3, 4, 5, 6, 7, 8, 9]

1. aşama : Root 4'tür. Root'un solunda kendinden küçük sayılar [0, 1, 2, 3],
sağında kendin büyük sayılar [5, 6, 7, 8, 9] bulunur.

2. aşama : Bütün sayılar ardışık olduğundan soldaki her sayı birbirinin soluna, sağdaki her sayı birbirinin sağına dallanır.
Solda en altta 0, sağda en altta 9 vardır. 
```
