Merge Sort Projesi

## 1[16,21,11,8,12,22] -> Merge Sort

                                                                -[16,21,11,8,12,22]
    Önce ikiye ayırıyoruz                                       -[16,21,11]     [8,12,22]
    Ayrılan iki dizeyi tekrar ikiye ayırıyoruz                  -[16] [21,11]   [8] [12,22]
    Tek eleman kalana kadar ikiye ayırıyoruz                    -[16] [21] [11]     [8] [12] [22]
                                
                                
    Küçükten büyüğe sıralayarak ikili birleştiriyoruz           -[16] [11,21]       [8,12] [22]
    Tekrar sıralayarak ikili birleştiriyoruz                    -[11,16,21]         [8,12,22]
    Son iki diziyi de sıralayarak birleştiriyoruz               -[8,11,12,16,21,22]




## 2 Big-O gösterimini yazınız.

    Hep ikiye böldüğümüz için 2^x=n --> x=logn O(n)->O(nlogn)

    -O(nlogn)