## imagetoarraycpp

Gunakan alat ini secara online di http://nanaperm12.github.io/imagetoarraycpp/ image2cpp adalah alat sederhana untuk mengubah gambar menjadi array byte (atau array Anda kembali menjadi gambar) untuk digunakan dengan tampilan (monokrom) seperti OLED, seperti itu dari Adafruit atau Sparkfun. Saat mencari cara untuk menghasilkan array ini, saya kebanyakan menemukan tautan ke perangkat lunak Windows. Baik hasil yang tidak jelas dan kerumitan karena harus mem-boot mesin virtual hanya untuk mengonversi gambar membuat saya menulis solusi html + javascript murni ini.

Atau Anda juga dapat memasukkan array byte sebagai input untuk mengubahnya kembali menjadi gambar. Ini mungkin berguna untuk debugging, atau ketika Anda ingin menulis array byte sendiri. Aku tidak tahu.

Apakah menurut Anda alat ini berguna? Jangan ragu untuk mendukung perangkat lunak sumber terbuka saya:

![GitHub Sponsor](https://img.shields.io/github/sponsors/nanaperm12?label=Sponsor&logo=GitHub)


### Running the tool
kamu tidak membutuhkan dependencies khusus / koneksi internet ; seluruh bagian terdapaat dalam file html. jadi hanya cukup dengan membukan file index.html  secara langsung di browser
atau dapat mengunjungi versi online di http://nanaperm12.github.io/imagetoarraycpp/

### EContoh ardino kode
kamu dapat menggunakan contoh sketch Arduino [disini](https://github.com/nanaperm12/imagetoarraycpp/blob/master/oled_example/oled_example.ino) di repository.

### Jenis Layar
I wrote the code with my 128x64 pixel monochrome OLED display in mind, but it should work with most similar displays. You might need to change some export settings; those are explained in the tool.

### Credit
Initial code by [javl](https://github.com/javl) with aditional code by (in alphabetical order):
* [akumpf](https://github.com/akumpf)
* [Daniyal Warraich](https://github.com/Daniyal-Warraich)
* [davidalim](https://github.com/davidalim)
* [dotcypress](https://github.com/dotcypress)
* [Harry48225](https://github.com/harry48225)
* [hurricaneJoef](https://github.com/hurricaneJoef)
* [jochenderwae](https://github.com/jochenderwae)
* [plewka](https://github.com/plewka)
* [Sebski123](https://github.com/Sebski123)
* [whoisnian](https://github.com/whoisnian)
* [wiredolphin](https://github.com/wiredolphin).

The example sketch is based on code by [Adafruit](https://github.com/adafruit). Dithering code from [stellar-L3N-etag](https://github.com/reece15/stellar-L3N-etag).

### License
image2cpp is released under GPL v3. This means you can use the project in any way you want (use, adapt, distribute, etc.) as long as you share any changes and link back to this repo. See [LICENSE.md](https://github.com/javl/image2cpp/blob/master/LICENSE.md) for more info.
