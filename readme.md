Selection Sort Projesi

Soru 1: [22,27,16,2,18,6]

a) Issertion sort türünde aşamaları:
1. Aşama: Tüm dizi taranarak en küçük sayı olan 2 bulunur ve dizinin en başındaki sayı ile yer değiştir.
[2,27,16,22,18,6] 
2. Aşama: Dizinin sonraki en küçük sayısı olan 6 bulunarak 2. sıraya geçirilir.
[2,6,16,22,18,27]
3. Aşama: Dizinin sonraki en küçük sayısı olan 16 bulunarak 3. sıraya geçirilir(3. sırada olduğundan dizide değişme olmadı.).
[2,6,16,22,18,27]
4. Aşama: Dizinin sonraki en küçük sayısı olan 18 bulunarak 4. sıraya geçirilir.
[2,6,16,18,22,27]
5. Aşama: Dizinin sonraki en küçük sayısı olan 22 bulunarak 5. sıraya geçirilir.(5. sırada olduğundan dizide değişme olmadı.).
6. Aşama: Dizinin son terimi de kontor edilerek sırama işlemi tamamlanır.

b)Big-O gösterimi: 
1. aşamada 6(n) işlem
1. aşamada 5(n-1) işlem
2. aşamada 4(n-2) işlem
3. aşamada 3(n-3) işlem
4. aşamada 2(n-4) işlem
5. aşamada 1(n-5) işlem
Toplam İşlem = n+(n-1)+(n-2)+(n-3)+(n-4)+(n-5) = n.(n-1)/2= (n^2-n)/2
Denklemde en büyük etkiye sahip terimi seçersek:
Big-O = n^2

c) Time Complexity: 18 sayısı dizinin orta kısımlarında yer aldığı için "Average Case" kapsamına girer.

Soru 2: [7,3,5,8,2,9,4,15,6] -->Selection Sort'a göre adımları:
1. Adım: [2,3,5,8,7,9,4,15,6]
2. Adım: [2,3,5,8,7,9,4,15,6]
3. Adım: [2,3,4,8,7,9,5,15,6]
4. Adım: [2,3,4,5,7,9,8,15,6]