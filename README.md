# MergeSortProjesi
Başlangıç seviye java ile backend web development patikası -> Veri yapıları ve algoritmalar > Merge sort projesi

# Soru: Proje 2
[16,21,11,8,12,22] -> Merge Sort

- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız.

# Cevap: Proje 2
- 1.Adım: [16,21,11]---[8,12,22]
  2.Adım: [16,21],[11]---[8,12],[22]
  3.Adım: [16],[21],[11]---[8],[12],[22]
  4.Adım: [16,21],[11]---[8,12],[22]
  5.Adım: [11,16,21]---[8,12,22]
  6.Adım: [8,11,12,16,21,22]
 
- O(N * log(N))
