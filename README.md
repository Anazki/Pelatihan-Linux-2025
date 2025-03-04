# Pelatihan-Linux-2025
Latihan cuk
1. Membuat folder lalu membuka nya
```bash
mkdir artist_who_can_sing && cd artist_who_can_sing
```
2. Download file zip yang sudah diberikkan menggunakan wget
```bash
wget "https://drive.google.com/uc?export=download&id=1lV1HVmPTY_BOAK6ToXymRu7V5eVfR0ut" -O tutorials.zip
```
3. Buat folder baru dan unzip file pada folder tersebut
```bash
unzip tutrials.zip -d singing_tutorials
```
4. menampilkan list file
```bash
ls -la
```
5. Mencari flag
```bash
find . -name "*_opera_*_NBAYoungboy*" | grep -rIh "FLAG{.*}" | grep "catbox" > ../flag.txt
```
6. download file dari flag tersebut
```bash
wget "https://files.catbox.moe/9l4qu8" -O plsrunmeiamnotamalwarefr
```
7. Ubah permission terhadap file tersebut untuk dapat dijalankan
```bash
chmod +x plsrunmeiamnotmalwarefr
```
8. jalankan 
```bash
./plsrunmeiamnotamalwarefr && ps aux
```
9. Membuat file untuk menghentikan
```bash
touch ransom.moolah
```
10. Mematikan anomaly
```bash
Kill <PID>
```
