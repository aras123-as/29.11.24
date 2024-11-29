# ÖRNEK 1


x=[78,2,35,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,23,20]

for x in x[1:20:2]:
    print(x)

print(  "BAŞKA ÖRNEK ")



# ÖRNEK 2



sayilar=[1,-2,-3,-4,-5,-6,-7,-8,0,0,0,-9,0,17,2037,479,25,84]


pozitif_toplam = 0
negatif_toplam = 0


for sayi in sayilar:
    if sayi > 0:
        pozitif_toplam += sayi
    elif sayi < 0:
        negatif_toplam += sayi


print("Pozitif sayilarin toplami:", pozitif_toplam)
print("Negatif sayilarin toplami:", negatif_toplam)




for q in sayilar: 
    if(q>0):
        print(q)




print("---------------------------------------")

for z in sayilar: 
    if(z<0):
        print(z)


eleman_sayisi=0
for eleman in sayilar:

    if(eleman==0):
        eleman_sayisi+=1
print("0 sayısı:{}".format(eleman_sayisi))




# ÖRNEK 3
metin = "Bugün sabah erken saatlerde parka gidip yürüyüş yaparak doğanın keyfini çıkaracağım ve huzur bulacağım."


sesli_harfler = "aeiouAEIOU"


sesli_sayisi = 0
sessiz_sayisi = 0
sembol_sayisi = 0


for karakter in metin:
    if karakter.isalpha():  
        if karakter in sesli_harfler:
            sesli_sayisi += 1  
        else:
            sessiz_sayisi += 1  
    else:
        sembol_sayisi += 1  


print(f"Sesli harf sayısı: {sesli_sayisi}")
print(f"Sessiz harf sayısı: {sessiz_sayisi}")
print(f"Sembol sayısı: {sembol_sayisi}")
