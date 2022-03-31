# Merge Sort Projesi 

## Merge Sort
 
 **Dizi : **[16,21,11,8,12,22]****
Bir listeyi her adımda parçaya ayırıp tek eleman kalıncaya kadar bölüyor.
			
		

                    [16, 21, 11, 8, 12, 22]
                         /            \
                  [16, 21, 11]     [8, 12, 22]
                      /   \           /   \
                [16, 21]  [11]     [8, 12]  [22]
                  /   \    |         /  \     \
               [16]  [21] [11]      [8] [12]  [22]
                   \   /    \         \   /   /
                 [16, 21]  [11]   [8, 12]  [22]
                     \       /       \      /    
                   [11, 16, 21]    [8, 12, 22]
                         \             /
                     [8, 11, 12, 16, 21, 22 ]

		
#### Big-O  notation formülümüz ise ;
		   O(nlogn)
