# sayi_bulma-oyunu
python ile sayı bulma oyunu 0 ve 100 arası bir sayıyı girin...


       import random as r
       def sayıyıdeğiştir():
           global x
           x=r.randint(0,100)
       sayıyıdeğiştir()
       print("Sayı tahmin etme oyununa hoş geldiniz...")
       while True :
           y=int(input("tahmininizi girin(0 la 100 arasında olmalı):"))
           if x==y:
               print("Tebrikler bildiniz...  Yeni oyun için 'yeni',çıkmak için 'çık' yazın.")
               z="jdajld"
               z=input()
               if z== "yeni":
                   sayıyıdeğiştir()
               else:
                   break
           
               
           elif x>y:
               if x<=y+6:
                   print("çok yaklaştınız,az daha yukarı")
               else:
                   print("daha büyük bir sayı giriniz")
           elif x<y :
               if x>=y-6:
                   print("çok yaklaştınız,az daha aşağı")
               else:
                   print("daha küçük bir sayı giriniz")
           print(x)
