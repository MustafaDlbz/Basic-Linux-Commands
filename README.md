# Basic-Linux-Commands
Basic linux commands sıkça kullandığım temel Linux komutlarını içeren bir depodur.

### ls, ls -la komutu
ls -> List - Mevcut dizindeki dosya ve dizinleri gösterir.

ls -la -> Mevcut dizindeki gizli dosya ve dizinleri detaylı olarak gösterir.
```bash
  ls
  ls -la
```
### pwd komutu
Print working directory - Mevcut calışma dizinini gösterir.
```bash
  pwd
```
### cd komutu
Change directory - Dizini değiştirir.
```bash
  cd directory_name
```
### cd .. komutu
Change directory to parent - Bir üst dizine geçer.
```bash
  cd ..
```
### clear komutu
Clear the terminal screen - Terminal ekranını temizler.
```bash
  clear
```
### mkdir komutu
Make directory - Yeni bir dizin oluşturur.
```bash
  mkdir new_directory
```
### touch komutu
Create a new file or update the timestamp of an existing file - Yeni bir dosya oluşturur veya mevcut bir dosyanın zaman damgasını günceller.
```bash
  touch new_file.txt
```
### mv komutu
Move or rename - Dosyaları, dizinleri taşımak veya yeniden adlandırmak için kullanılır.
```bash
  mv old_filename new_filename
  mv source_file destination file/
```
### cp komutu
Copy - Dosyaları veya dizinleri kopyalamak için kullanılır
```bash
  cp source_file destination_file
  cp -r source_directory destination_directory
```
### rm komutu
Remove - Dosyaları siler
```bash
  rm file_to_remove.txt
```
### rm -rf komutu
Remove recursively and forcefully - Dizinleri ve içeriğini zorla siler.
```bash
  rm -rf directory_to_remove
```
### cat komutu
Concatenate and display file content - Dosya içeriğini birleştirir veya görüntüler. 
```bash
  cat file_to_view.txt 
```
### wget komutu
Web get - Web'den dosya indirir.
```bash
  wget http://example.com
```
### curl komutu
Client url - Veri transferi için bir araçtır.
```bash
  curl http://example.com
```
### nano  komutu
Nano editor - Basit bir metin düzenleyicisidir.
```bash
  nano filename
```
### vim komutu
Vi improved - Gelişmiş bir metin düzenleyicisidir.
```bash
  vim filename
```
### ssh komutu
Secure shell - Uzak bir makineye güvenli bir şekilde bağlanır.
```bash
  ssh user@hostname
```
