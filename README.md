# Platinum-2
An interesting task

Anggota Kelompok:
* M. Afra Dzaki       - 16418056
* Fandi Azam Wiranata - 16518131
* Daniel Riyanto      - 16518296
* Firas Zuhair Altair - 16918213

Strategi:
* Jika zoneID HQ(HeadQuarter) Lawan > zoneID HQ(HeadQuarter) Sendiri maka
  - zoneID tengah = ((IdZone HQ Lawan) + (zoneID HQ Sendiri)) / 2 
  - Pod boleh bergerak secara random tetapi 
       * tidak boleh melewati (zoneID tengah + 40)
       * sampai semua IdZone yang ada di kiri (zoneID tengah) terkuasai semua
  - Sebaliknya, tidak boleh melewati (zoneID tengah - 40) sampai semua zoneID di sebelah kanan (zoneID tengah) terkuasai semua
* Setelah zone-zone yang terkuasai itu
  - Untuk yang zoneID HQ(HeadQuarter) Lawan > zoneID HQ(HeadQuarter) Sendiri
    * Zone yang terkuasai : di sebelah kiri zoneID Tengah, Pod-Pod langsung bergerak ke arah zoneID HQ Lawan
  - Untuk yang zoneID HQ(HeadQuarter) Lawan < zoneID HQ(HeadQuarter) Sendiri
    * Zone yang terkuasai : di sebelah kanan zoneID Tengah, Pod-Pod langsung bergerak ke arah zoneID HQ Lawan
       
       
      
 
