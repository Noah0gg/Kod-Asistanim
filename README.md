# Kod-Asistanim
#Proje Yazarı : Alireza Derakhshanikhozove
##Projenin Amacı : Kullanıcılara günlük işlerinde (hesaplama, selamlama vb.) yardımcı olacak bir dıjıtal asistan tasarlamak 
## Projenin Hedefleri : Bu asistanın ilerleyen zamanlara hangi özellikleri kazanacağın ( örneğin v1.0 Akıllı Menü, v2.0 Veri Saklama ) maddeler halınde yazınız.



##KRİTİK EŞİK Sözde Kod

#BAŞLA
    saat = 1
    su_seviyesi = 0

    DÖNGÜ
        su_seviyesi = Sensörden_Oku()

        EĞER su_seviyesi > 50 İSE
            Ekrana Yazdır: "KRİTİK EŞİK AŞILDI!"
            Ekrana Yazdır: "Tahliye Saati:", saat
            Ekrana Yazdır: "Kritik Su Seviyesi:", su_seviyesi
            DÖNGÜYÜ KIR (BİTİR)
        DEĞİLSE
            Kapakları Kapalı Tut
            saat = saat + 1
        SON EĞER
    SON DÖNGÜ
BİTİR
