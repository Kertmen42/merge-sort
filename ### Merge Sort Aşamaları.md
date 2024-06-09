### Merge Sort Aşamaları

Verilen dizi: [16, 21, 11, 8, 12, 22]

Merge Sort adımları:

1. **Diziyi ikiye böl**:
   - [16, 21, 11, 8, 12, 22]
   - Sol yarı: [16, 21, 11]
   - Sağ yarı: [8, 12, 22]

2. **Sol yarıyı ikiye böl**:
   - [16, 21, 11]
   - Sol yarı: [16]
   - Sağ yarı: [21, 11]

3. **Sağ yarıyı ikiye böl**:
   - [21, 11]
   - Sol yarı: [21]
   - Sağ yarı: [11]

4. **Küçük dizileri birleştir (merge)**:
   - [21] ve [11] birleştirilir: [11, 21]
   - [16] ve [11, 21] birleştirilir: [11, 16, 21]

5. **Sağ yarıyı ikiye böl**:
   - [8, 12, 22]
   - Sol yarı: [8]
   - Sağ yarı: [12, 22]

6. **Sağ yarıyı ikiye böl**:
   - [12, 22]
   - Sol yarı: [12]
   - Sağ yarı: [22]

7. **Küçük dizileri birleştir (merge)**:
   - [12] ve [22] birleştirilir: [12, 22]
   - [8] ve [12, 22] birleştirilir: [8, 12, 22]

8. **Son olarak iki büyük yarıyı birleştir (merge)**:
   - [11, 16, 21] ve [8, 12, 22] birleştirilir: [8, 11, 12, 16, 21, 22]

Sonuç: [8, 11, 12, 16, 21, 22]

### Big-O Gösterimi

Worst Case: O(6 log 6)
Average Case: O(6 log 6)
Best Case: O(6 log 6)