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
$ docker pull mysql:5.6
```
