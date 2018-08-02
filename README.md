Tur Bahasa Pemrograman Go adalah sebuah pengenalan dari bahasa pemrograman Go.

Cara paling mudah untuk memasang tur secara lokal adalah dengan memasang
[rilis binari dari Go](https://golang.org/dl/)
dan kemudian menjalankan:

    $ go tool tour

Untuk memasang tur dari sumber kode, pertama
[siapkan sebuah _workspace_](https://golang.org/doc/code.html)
dan kemudian jalankan:

    $ go get golang.org/x/tour/gotour

Perintah tersebut akan membuat program `gotour` dalam direktori `bin` di
_workspace_ anda.

Kecuali bila dicantumkan, berkas sumber kode go-tour didistribusikan di bawah
lisensi bermodelkan BSD yang bisa ditemukan pada berkas LICENSE.

Kontribusi sebaiknya mengikuti prosedur yang sama dengan proyek Go:
https://golang.org/doc/contribute.html
