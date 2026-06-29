# 🎲 Seven Segment Dice Roller Menggunakan Arduino dan Push Button

Proyek ini merupakan simulasi dadu elektronik menggunakan **Arduino Uno**, **Seven Segment Display**, dan **Push Button**. Setiap kali tombol ditekan, seven segment akan menampilkan angka acak dari **1 hingga 6**, menyerupai hasil lemparan dadu.

---

## 📸 Preview

<img width="930" height="567" alt="image" src="https://github.com/user-attachments/assets/d2e87749-d970-4784-9438-66eda2ee0787" />

---

## ✨ Fitur

- 🎲 Menghasilkan angka acak 1–6.
- 🔘 Menggunakan satu push button sebagai tombol lempar dadu.
- 💡 Menampilkan hasil pada seven segment.
- ⚡ Mudah dipahami dan cocok untuk pemula.

---


## 🛠️ Komponen yang Digunakan
1. arduino uno smd + USB kabel B (52k)
2. kabel jumper male to male 11pcs (1,7k)
3. push button 1pcs (1,2k)
4. breadboard 400 point (6,5k)
5. resistor 220 ohm 8 pcs dan resistor 10k ohm 1 pcs (900)
6. common anode 0.56 inch 1pcs (1,7k)

TOTAL = 64k

---

## 🔌 Diagram Rangkaian

<img width="1095" height="653" alt="image" src="https://github.com/user-attachments/assets/b7fbe0f6-d09c-4aa7-beca-7e9fc07f1696" />

---

## 🚀 Cara Menjalankan

1. Rangkai seluruh komponen sesuai diagram.
2. Buka file `.ino` menggunakan Arduino IDE.
3. Pilih Board **Arduino Uno**.
4. Pilih Port yang sesuai.
5. Upload program ke Arduino.
6. Tekan tombol untuk menghasilkan angka dadu secara acak.

---

## ⚙️ Cara Kerja

1. Arduino mendeteksi saat push button ditekan.
2. Program menghasilkan angka acak dari **1 sampai 6** menggunakan fungsi `random()`.
3. Seven segment menampilkan angka sesuai hasil yang diperoleh.
4. Setiap penekanan tombol akan menghasilkan angka baru.

---

## 💻 Dibuat Menggunakan

- Arduino IDE
- Bahasa C++
- Arduino Uno

---



