# Merge Sort Projesi

## Soru
**[16 , 21 , 11 , 8 , 12 , 22] -> Merge Sort**

**Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.**

**Big-O gösterimini yazınız.**

### cevap

* [16,21,11,8,12,22] 
[16,21,11] [8,12,22] (ikiye böldük)
[16] [21,11] [8] [12,22] (ayırdık tekrar)
[16] [21] [11] [8] [12] [22] (hepsini teker teker böldük)
[16] [11,21] [8] [12,22]  (tekrar birleştiriyoruz)
[11,16,21] [8,12,22]
[8,11,12,16,21,22] (son hali)



* Big-O gösterimi ise "O(nlogn)"dir.









