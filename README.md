# administrator-
administrator server
# menambah user dan akses
**add user** 
```bash
sudo useradd -m user
```
- **useradd** menambahkan user baru

- **-m** untuk membuat direktori home untuk pengguna baru

<img src="/images/add.png" alt="menambahkan user" width="600">

**memberikan hak administrator untuk user baru**
```bash
sudo usermod -aG sudo user
```
- **usermod** perintah untuk mengubah pengaturan pengguna 

- **-aG** untuk menambahkan pengguna ke grup tanpa menghapusnya dari grup lainny

- **sudo** untuk memberikan akses administrator ke user tersebut agar dapat menjalankan sudo

**password untuk user**
```bash
sudo passwd user
```
- **passwd** untuk mengatur password pengguna 

- **user** adalah pengguna yang dimaksud atau yang akan di ganti password nya
<img src="IMG.jpg" alt="hasil berikut" width="600">
