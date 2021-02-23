# Automatic Wifi Cracker
  
  Automatic Wifi Cracker ile Deauthentication saldırısı kolay ve otonom bir şekilde gerçekleştirilir. Wireless Cracker aircrack-ng ailesindeki toolların(airmon-ng, airodump-ng, aireplay-ng, aircrack-ng) otomatik bir şekilde kullanılmasını sağlamaktadır. 


## Adımları
  
  Program çalıştıktan sonra otonom bir şekilde sırayla aşağıdaki işlemler gerçekleşmektedir.
  
  * Ağ kartını belirtir ve ağ kartını monitor moda alır.
  * Monitor moda alınan ağ kartının ismini tutar.
  * Etraftaki ağları tarar.
  * Öncesinde belirlediğimiz BSSID listesindeki(input.csv) ağlardan handshake yakalar.
  * Yakalanan handshakelere, belirlediğimiz wordlistler kullanılarak brute-force saldırı gerçekleştirir.
  * Parolaları txt'ye yazdırır
  * Monitor modu durdurur.

## Nasıl Çalışır?

      git clone https://github.com/istec-iuc/Wireless_Network_Cracker.git
      cd Wireles_Network_Cracker
      sudo python3 networkCracker.py


### Geliştiricileri

**Binnaz Demirçeviren :** 
  Github: https://github.com/binnazdemirceviren
  
  Linkedin: https://www.linkedin.com/in/binnaz-demirceviren/
  

**Merve Nur Teke :** 
  Github: https://github.com/Merveeenur
  
  Linkedin: https://www.linkedin.com/in/mervenurteke/
  
  
**İsmail Can Tosun :** 
  Github: https://github.com/Cantsnn 
  
  Linkedin: https://www.linkedin.com/in/ismailcantosun/


  
  
  
