# Proje 1
## Soru 1
**[22,27,16,2,18,6]** -> Insertion Sort

*Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.*
```
[2,27,16,22,18,6] -> adım 1  
[2,6,16,22,18,27] -> adım 2 
[2,6,16,18,22,27] -> adım 3  
```
*Big-O gösterimini yazınız.*
```
Worst case: Aradığımız sayının en sonda olması.
Bu durumda her adımda yerinde olmayan elemanların hepsini taradığımız için eleman sayısı kadar işlem yapılır.

n = eleman sayısı  
n+(n-1)+(n-2)...+1 = [n(n+1)]/2 = (n^2+n)/2
Belirleyici olan n^2 olduğu için worst case durumlarında O(n^2) zaman karmaşıklığına sahiptir.
```
*Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer?*
```
Dizi sıralandıktan sonra 18 sayısı Average case kapsamına girer.
```
## Soru 2
**[7,3,5,8,2,9,4,15,6]** *dizisinin Selection Sort'a göre ilk 4 adımını yazınız.*
```
[2,3,5,8,7,9,4,15,6] -> 1. adım
[2,3,4,8,7,9,5,15,6] -> 2. adım
[2,3,4,8,7,9,5,15,6] -> 3. adım
[2,3,4,5,7,9,8,15,6] -> 4. adım
```