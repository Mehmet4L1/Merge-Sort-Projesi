# Merge-Sort-Projesi
## Merge Short Projesi www.patika.dev
## [16 , 21 , 11 , 8 , 12 , 22] Dizimizin Merge Sort aşamaları ;

                             [16 , 21 , 11 , 8 , 12 , 22]            (n/2)
                             
                         |16,21,11|                |8,12,22|          (n/2)
                         
                       |16|  |21,11|             |8|  |12,22|         (n/2)
                       
                     |16|  |21|  |11|           |8|  |12|  |22|          :
                     
                       |16|  |11,21|             |8|  |12,22|            :
                       
                         |11,16,21|                 |8,12,22|            :
                         
                             [8 , 11 , 12 , 16 , 21 , 22]
                            
## Big O Notation
Merge Sort'ta n elemanlı bir dizide (n-1) sorgu yapmamız gereklidir. <br>
Time Complexity ise bu işlemi kaç defa tekrarladığımızı gösterir ; <br>
2<sup>x</sup>=n <br>
logn=x <br>
### Big O(nlogn)
