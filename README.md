# SelectionSortProjesi

          [22,27,16,2,18,6] -> Insertion Sort

 1) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

          1. [ 22-27-16-2-18-6 ]   (n)      2 Dizinin en küçük sayısı olduğundan en başa alabilmek için 22 ile yer değiştiriyoruz.
       
          
          2. [ 2-27-16-22-18-6 ]   (n-1)    Sonraki en küçük rakamı 6 olduğundan 6 ile 27 rakamlarını yer değiştiriyoruz.
         
         
          3. [ 2-6-16-22-18-27 ]   (n-2)     Ondan sonra en küçük rakam 16 olduğunda üçüncü sıra için herhangi bir işlem yapmiyoruz.
         
          
          4. [ 2-6-16-18-22-27 ]   (1)      Daha sonra en küçük rakam olan 18 i dördüncü sıraya alabilmek için 22 ile yer değiştiriyoruz.

	           * Beşinci ve altıncı sıradaki rakamlar zaten sıralı olduğundan dizimiz sıraya alınmış oluyor.

 
  2)  Big-O gösterimi : O(n²)
 
 
  
  
  3) Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.
 
     * Average Case : Aradığımız sayının ortada olması
   
      
       [18,x,y,z,v,t]
      
      
     * Worst Case : Aradığımız sayının sonda olması
      
       
       [x,y,z,z,v,t,18]
      

     * Best Case : Aradığımız sayının dizinin en başında olması. 
      
       
       [18,x,y,z,v,t,]
      
      
     * [2,6,16,18,22,27] dizi sıralandığında 18 sayısı ortada kaldığı için Avarage Case olur.


  
  
   4)  [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
                     
          1. [2,3,5,8,7,9,4,15,6]  (Birinci) 
     
          2. [2,3,5,8,7,9,4,15,6]  (İkinci) 
     
          3. [2,3,4,8,7,9,5,15,6]  (Üçüncü) 
     
          4. [2,3,4,5,7,9,8,15,6]  (Dördüncü)



    www.patika.dev
