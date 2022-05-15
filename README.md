# Markov-Decision-Make-Process

Çıktı bize merkezden başlayan robotun 0.2 olasılıkla bir üst hücre, 0.3 olasılıkla bir aşağı hücre vb. olacağını söylüyor. 
Bunu 3, 10 ve 100 adım için yapalım. Sonuçlar şurada gösterilir:

n=1

![image](https://user-images.githubusercontent.com/63358327/168470201-84ffa13d-74f6-420c-b713-857a2d5c5a4e.png)



n=3 

![image](https://user-images.githubusercontent.com/63358327/168470191-1bd31f39-df05-4194-bc58-e3f97998121b.png)

n=100

![image](https://user-images.githubusercontent.com/63358327/168470122-8513cba7-b17e-43aa-a009-75901066783c.png)



10 adım ve 100 adımdan sonraki olasılık dağılımının çok benzer olduğunu fark edebilirsiniz. 
Bunun nedeni, sistemin birkaç adımdan sonra neredeyse kararlı bir duruma ulaşmasıdır. 
Yani 10, 100 veya 1.000 adımdan sonra robotu belirli bir durumda bulma şansımız hemen hemen aynıdır.

![image](https://user-images.githubusercontent.com/63358327/168472146-2624177a-415e-4e1a-a9d6-dae31637ab83.png)
