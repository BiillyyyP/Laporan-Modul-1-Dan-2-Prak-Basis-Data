# Laporan-Modul-1-Dan-2-Prak-Basis-Data

### Nama: M Billy Putra Pratama
### Kelas: XI RPL 2
### Absen: 02

## MODUL 1

#### 1.Install XAMPP terlebih dahulu
![image](https://user-images.githubusercontent.com/113566181/190311711-6a14d07c-9ffe-46bc-9102-7f830dd7feee.png)
#### 2.Aktifkan mysql di XAMPP
![image](https://user-images.githubusercontent.com/113566181/190312393-d153197c-135f-46f0-a951-21ba53d5e450.png)
#### 3.Kemudian masuk ke commad prompt
c
#### 4.Masuk direktori mysql
```
cd xampp/mysql/bin
```
![image](https://user-images.githubusercontent.com/113566181/190315393-d1b8edbc-f3c8-429c-8a41-600497fff331.png)
#### 5.Ketik syntak berikut untuk masuk untuk ke MariaDB
```
mysql -u root
```
![image](https://user-images.githubusercontent.com/113566181/190316210-25bd19cb-63e7-4b4f-99f3-7535c1f48bd4.png)


## MODUL 2


#### 1.Cara melihat daftar database
```
show database;
```
![image](https://user-images.githubusercontent.com/113566181/190316514-bc8f6977-1059-4315-8a70-bb8384109311.png)
#### 2. Cara memilih dan masuk dafar database yang kita inginkan 


use nama_database;

![image](https://user-images.githubusercontent.com/92255670/190312060-2618fb47-49b7-4242-b6ad-1e2ffc73719f.png)

- ### Cara membuat table

create table name_table(nama varchar(50)not null,no int(3)not null);


![image](https://user-images.githubusercontent.com/92255670/190313876-73124c48-987b-467d-b775-a94d8cd51a73.png)

- ### Cara melihat daftar table

show tables;

![image](https://user-images.githubusercontent.com/92255670/190314476-a41bb5ec-8393-4404-aa93-6e3f2c6fbff8.png)

- ### Cara melihat isi (struktur) di sebuah tabel


desc name_table;


![image](https://user-images.githubusercontent.com/92255670/190314810-773e8af2-cd89-4cdf-827b-3016b01c41cf.png)
