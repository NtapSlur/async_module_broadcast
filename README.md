#  Reflection
## 2.1 Original Code of Broadcast Chat
- Client
![Foto 1](image.png)
![Foto 2](image-1.png)
![Foto 3](image-2.png)
- Server
![Foto 4](image-3.png)

Untuk menjalankan satu server, kita perlu menjalankan perintah sebagai berikut
```
cargo run --bin server
```

Untuk menjalankan satu client, kita perlu menjalankan perintah sebagai berikut
```
cargo run --bin client
```

Setelah meng-run server dan client dan kita mengetikkan sesuatu dari client, server akan menerima pesan tersebut dari client dan server akan meneruskan pesan dari client tersebut ke seluruh client yang terhubung ke server tersebut. 
