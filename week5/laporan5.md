## Laporan Praktikum Jarkom

# Langkah Percobaan

# Lampiran

1. Pilih satu paket UDP yang terdapat pada trace Anda. Dari paket tersebut, berapa banyak
“field” yang terdapat pada header UDP? Sebutkan nama-nama field yang Anda temukan!
![foto](../assets/image/modul5(1).png)

2. Perhatikan informasi “content field” pada paket yang Anda pilih di pertanyaan 1. Berapa
panjang (dalam satuan byte) masing-masing “field” yang terdapat pada header UDP? Setiap field pada header UDP memiliki panjang yang tetap, yaitu 2 byte
![foto](../assets/image/modul5(1).png)

3. Nilai yang tertera pada ”Length” menyatakan nilai apa? Verfikasi jawaban Anda melalui
paket UDP pada trace.
Nilai pada field Length menyatakan panjang total dari Header UDP ditambah dengan Payload (data) dalam satuan byte
![foto](../assets/image/modul5(1).png)
4. Berapa jumlah maksimum byte yang dapat disertakan dalam payload UDP? (Petunjuk:
jawaban untuk pertanyaan ini dapat ditentukan dari jawaban Anda untuk pertanyaan 2)
![foto](../assets/image/modul5(2).png)

5. Berapa nomor port terbesar yang dapat menjadi port sumber? (Petunjuk: lihat petunjuk
pada pertanyaan 4)
![foto](../assets/image/modul5(3).png)

6. Berapa nomor protokol untuk UDP? Berikan jawaban Anda dalam notasi heksadesimal dan
desimal. Untuk menjawab pertanyaan ini, Anda harus melihat ke bagian ”Protocol” pada
datagram IP yang mengandung segmen UDP.
![foto](../assets/image/modul5(4).png)

7. Periksa pasangan paket UDP di mana host Anda mengirimkan paket UDP pertama dan paket
UDP kedua merupakan balasan dari paket UDP yang pertama. (Petunjuk: agar paket kedua merupakan balasan dari paket pertama, pengirim paket pertama harus menjadi tujuan dari
paket kedua). Jelaskan hubungan antara nomor port pada kedua paket tersebut! 

Pada Frame 1 (Request): Source Port adalah 4334 dan Destination Port adalah 161.

Pada Frame 2 (Response): Source Port adalah 161 dan Destination Port adalah 4334.
![foto](../assets/image/modul5(5).png)