# Linq-Sorgusu# 
Linq Sorguları

> OrderBy(x⇒x.Name) //ismi Alfabeye göre sırala
> 

> Where(x⇒x.yas == 20) //Yaş 20 ise
> 

> Max() //maksimum değeri alır
> 

> Min() //Minumum değeri alır
> 

> Sum() //Sayı kumesindeki elemanların toplamını bulan extension methodtur.
> 

## **First**

Collectiondaki ilk elemanı bulan extension methodtur. Eğer collectionda değer bulunmadıysa *InvalidOperationException* hatasını bize verir

## **FirstOrDefault**

Collectiondaki ilk elemanı bulur, eğer eleman yoksa Null değer vermek yerine default value’sunu döndürür.

## **Last**

Collectiondaki son elemanı bulan extension methodtur. Eğer collectionda değer bulunamadıysa *InvalidOperationException* hatasını bize verir

## **LastOrDefault**

Collectiondaki son elemanı bulur, eğer eleman yoksa Null değer vermek yerine default value’sunu döndürür.

## **Single**

Collectionda yer alan tek bir uniqe elemanı bulan extension methodtur. Eğer collectionda aranan eleman bulunamadıysa veya birden daha fazla sayıda varsa *InvalidOperationException* Hatasını verir

## **SingleOrDefault**

Collectionda yer alan tek bir uniqe elemanı bulan extension methodtur. Eğer eleman bulunamdıysa Null değer vermek yerine default value’sunu döndürür. Aranan eleman collectionda yoksa *InvalidOperationException* hatasını bize verir
