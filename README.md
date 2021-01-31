![Banner](banner.png)

# Perintah-perintah dasar pada docker

- Melihat versi docker

```bash
$ docker version
```

- Melihat informasi tentang docker yang telah di instal

```bash
$ docker info
```

- Melihat daftar images

```bash
$ docker images
```

- Download images

```bash
$ docker pull mysql
```

perintah di atas merupakan contoh untuk mendownload images mysql, dengan menggunakan perintah seperti di atas secara default akan mendownload mysql dengan tag _latest_ atau versi paling baru, jika ingin mendownload versi lain dapat menggunakan perintah seperti berikut:

```bash
$ docker pull mysql:5.6 #tambahkan tag :5.6
```

- Melihat daftar container yang sedang running

```bash
$ docker container ls
```

- Melihat daftar semua container

```bash
$ docker container ls --all
```

- Membuat container

```bash
$ docker container create mysql:5.6
```

Setiap container memiliki nama, dengan perintah di atas by default container tersebut akan memiliki random name, untuk memberikan nama secara spesifik gunakan perintah berikut:

```bash
$ $ docker container create --name mysqlserver mysql:5.6 #menambahkan nama container
```
