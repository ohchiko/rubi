# Panduan Merakit Numpad Rubi

## Instalasi Firmware

Rubi menggunakan firmware [QMK](https://qmk.fm/). Instalasi firmware Rubi dapat
dilakukan melalui aplikasi [QMK Toolbox](https://github.com/qmk/qmk_toolbox/releases).

Instruksi instalasi dapat dilihat di [halaman dokumentasi QMK](https://docs.qmk.fm/#/newbs_flashing).

> Catatan: Jika Anda menerima numpad Rubi melalui Group Buy lokal IMKG, maka
> seharusnya firmware sudah terinstall dan langkah di atas tidak diperlukan.

## Merakit PCB

### Komponen

Komponen yang dibutuhkan untuk merakit PCB Rubi adalah sebagai berikut:
- 1x PCB Rubi
- 1x LED 3mm satu warna
- 1x Layar OLED 0.91in 128x32
- 1x Rotary Encoder EC11
- 17x Switch MX
- (Opsional) 17x Kailh/Gateron Hotswap Socket

### Langkah Perakitan

#### Hotswap Socket

Jika Anda akan menggunakan fitur hotswap pada PCB Rubi, maka yang pertama kali
perlu Anda lakukan adalah memasang hotswap socket pada PCB. Jika tidak, maka
langkah ini dapat Anda lewati.

**1. Beri timah pada salah satu pad tempat hotswap socket pada PCB.**

![hotswap-1](https://media.discordapp.net/attachments/854190316465815553/863148975279702057/IMG20210708135559.jpg?width=901&height=676)

**2. Letakkan hotswap socket pada tempatnya, kemudian panaskan timah pada pad.**

![hotswap-2](https://media.discordapp.net/attachments/854190316465815553/863148974709932052/IMG_20210708_135823.jpg?width=676&height=676)

Letakkan hotswap socket pada tempatnya, sesuaikan dengan lubang yang ada pada PCB.
Kemudian gunakan alat bantu seperti tweezer untuk menahan dan sedikit menekan
hotswap socket pada tempatnya sembari memanaskan timah yang telah diberikan pada pad.
Jika hotswap socket sudah menempel dengan PCB, lepaskan solder dan biarkan timah
hingga dingin sehingga dapat menahan posisi hotswap socket.

**3. Beri timah pada pad yang lain.**

![hotswap-3](https://media.discordapp.net/attachments/854190316465815553/863148974097956924/IMG20210708140915.jpg?width=676&height=676)

#### LED

**1. Beri timah pada pad negatif.**

![led-1](https://media.discordapp.net/attachments/854190316465815553/863148972301352970/IMG_20210708_141952.jpg?width=676&height=676)

Letakkan LED pada pin **D19** pada PCB. Kaki LED yang lebih panjang adalah pin
positif, sesuaikan dengan tanda positif/negatif pada sisi PCB di sebaliknya.
Solder pin negatif pada LED, sembari sesuaikan posisi LED agar menempel pada PCB.

**2. Beri timah pada pad lainnya.**

![led-2](https://media.discordapp.net/attachments/854190316465815553/863148972675432488/IMG_20210708_141933.jpg?width=676&height=676)

Setelah dipastikan posisi LED sudah sesuai, maka selanjutnya solder pin positif.
Kemudian potong kaki LED yang tersisa menggunakan alat bantu seperti tang potong.

#### OLED

**1. Solder pin header.**

![oled-1](https://media.discordapp.net/attachments/854190316465815553/863148973183467570/IMG_20210708_141911.jpg?width=676&height=676)

Letakkan pin header OLED pada lubang di PCB (pin dengan tanda SDA, SCL, VCC, GND.
Pin yang lebih panjang menghadap ke bawah/ke PCB. Kemudian solder salah satu pin
terlebih dahulu sembari menyesuaikan posisi pin header agar menempel pada PCB.
Lalu, solder pin yang lain.

**2. Solder OLED pada pin header.**

![oled-2](https://media.discordapp.net/attachments/854190316465815553/863148973542604820/IMG_20210708_141901.jpg?width=676&height=676)

Setelah pin header terpasang, letakkan layar OLED pada pin header, pastikan
letak pin pada OLED sesuai dengan tanda yang ada pada PCB. Kemudian solder
salah satu pin sembari menyesuaikan posisi OLED agar tegak lurus. Kemudian solder
pin yang lainnya.

Jika telah terpasang, lepaskan lapisan pelindung layar pada OLED.

#### Rotary Encoder

**1. Solder pin pada rotary encoder.**

![encoder](https://media.discordapp.net/attachments/854190316465815553/863148971794104370/IMG_20210708_142243.jpg?width=676&height=676)

Letakkan rotary encoder sesuai dengan posisi pin pada PCB. Kemudian solder setiap
pin pada rotary encoder. Jika diperlukan, Anda dapat juga menyolder kaki rotary
encoder yaitu yang terletak pada sebelah kiri dan kanan rotary encoder. Hal ini
dapat memperkuat posisi rotary encoder pada PCB agar tidak mudah lepas.

#### Switch

Setelah semua komponen terinstal pada PCB, hal yang diperlukan adalah memasang switch.

**1. Pasang switch pada plate.**

![switch-1](https://media.discordapp.net/attachments/854190316465815553/860806722440527892/IMG20210628011039.jpg?width=507&height=676)

Jika Anda menggunakan plate akrilik, gunakan pasang switch pada layer plate 1.5mm,
kemudian tumpuk di atas layer plate 3mm.

![switch-2](https://media.discordapp.net/attachments/854190316465815553/860807083285020682/IMG20210628012744.jpg?width=507&height=676)

Jika Anda menggunakan plate brass/stainless steel/polycarbonate, pasang switch
pada plate tersebut, dan layer plate 3mm tidak diperlukan.

**2. Pasang switch pada PCB.**

![switch-3](https://media.discordapp.net/attachments/854190316465815553/863168332647890964/IMG20210628011258.jpg?width=507&height=676)
![switch-4](https://media.discordapp.net/attachments/854190316465815553/860807083683348510/IMG20210628012845.jpg?width=507&height=676)

Setelah memasang switch pada plate, pasang switch tersebut pada PCB. Jika
tidak menggunakan fitur hotswap, maka solder switch tersebut pada PCB.

> Catatan: Perhatikan pada langkah sebelumnya. Jika menggunakan plate akrilik,
> layer plate 3mm sebaiknya digunakan. Hal ini untuk menghindari plate akrilik
> retak ketika digunakan.

### Memasang Case

![case-1](https://media.discordapp.net/attachments/854190316465815553/860806718748753940/IMG_20210628_004831.jpg?width=901&height=676)

Layer/lapisan case yang diterima adalah seperti pada gambar. Penjelasan dari atas
kiri ke kanan bawah adalah sebagai berikut:
- 3x mid layer
- 1x top layer 1
- 1x top layer 2
- 1x bottom layer
- 1x 3mm plate layer
- 1x 1.5mm plate layer

Komponen yang dibutuhkan untuk memasang case Rubi adalah sebagai berikut:
- 8x baut M2x5mm
- 4x standoff M2x12mm female-to-female
- 2x baut M2x12mm

**1. Lepaskan kertas pelapis.**

![case-2](https://media.discordapp.net/attachments/854190316465815553/860806719571492864/IMG20210628004942.jpg?width=507&height=676)

Lepaskan kertas pelindung yang melapisi akrilik terlebih dahulu.

**2. Pasang baut dan standoff pada bottom layer**

![case-3](https://media.discordapp.net/attachments/854190316465815553/860806720711557130/IMG20210628010616.jpg?width=507&height=676)

Pasang baut dan standoff pada bottom layer dan atur posisi segilima standoff agar
mid layer dapat diletakkan.

**3. Letakkan mid layer.**

![case-4](https://media.discordapp.net/attachments/854190316465815553/860806721898938388/IMG20210628010721.jpg?width=507&height=676)

Jika Anda menggunakan plate akrilik, maka letakkan 2x mid layer di atas bottom
layer.

![case-5](https://media.discordapp.net/attachments/854190316465815553/860807082600169472/IMG20210628012507.jpg?width=507&height=676)

Jika menggunakan plate brass/stainless steel/polycarbonate, letakkan 3x
mid layer di atas bottom layer.

**4. Susun plate dan top layer.**

![case-6](https://media.discordapp.net/attachments/854190316465815553/860806722938994708/IMG20210628011831.jpg?width=901&height=676)

![case-7](https://media.discordapp.net/attachments/854190316465815553/860807084207898654/IMG20210628013331.jpg?width=901&height=676)

Susun plate layer di atas mid layer, kemudian diikuti dengan meletakkan top layer
1 dan 2 di atas plate layer. Selanjutnya, kencangkan case dengan baut.

> Perhatian: Case ini terbuat dari bahan akrilik. Sebaiknya kencangkan case
> secukupnya dengan baut untuk menghindari retak pada case.

**5. Pasang kaki case.**

Langkah terakhir yaitu memasang kaki case. Susun ketiga layer kaki case, dari
yang paling lebar menempel pada bottom layer. Kemudian kencangkan dengan baut
12mm pada lubang yang telah disediakan pada bottom layer.

> Perhatian: Lubang baut pada bottom layer yang diperuntukkan untuk kaki case
> memiliki ulir. Sebaiknya kencangkan kaki case secukupnya untuk menghindari
> retak dan menghindari ulir menjadi rusak sehingga tidak dapat dibaut.

## Selesai
