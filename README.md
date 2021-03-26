# Belajar CSS Flexbox & Grid (not finished yet)

## Flexbox

Flexbox Layout atau Flexible Box adalah sebuah jalan kemudahan bagi para web designer untuk membuat layout, arah, dan pendistribusian ruang antar item.

Dalam penggunaannya, flexbox memerlukan beberapa properti. Baik yang digunakan dalam parent element (flex container)maupun dalam children element (flex items).

Sehingga kita perlu mendefinisikan properti "display" menjadi flex pada parent elementnya.

### Contoh penggunaan awal (display)

Class container menggunakan display:flex; sehingga semua anak turunannya akan menggunakan flex.

.container {
display: flex;
}

### flex-direction

Kita dapat mendefinisikan arah sumbu dari container dengan menambahkan properti flex-direction.

- row (default): dari kiri ke kanan.
- row-reverse: dari kanan ke kiri.
- column: sama seperti row tapi berubah menjadi vertikal, atas ke bawah.
- column-reverse: dari bawah ke atas.

.container {
flex-direction: row | row-reverse | column | column-reverse;
}
