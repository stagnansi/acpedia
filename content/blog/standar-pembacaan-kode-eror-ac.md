---
title: "Metodologi Pembacaan Kode Eror Pendingin Udara"
date: 2026-01-18
description: "Interpretasi kode diagnostik sistem self-diagnostic pada modul PCB unit pendingin."
---

Sistem pendingin modern dilengkapi algoritma *self-diagnostic* yang mengirimkan sinyal kesalahan melalui lampu indikator (LED kedip) atau karakter alfanumerik pada panel tampilan.

### Prosedur Pembacaan Eror

* **Metode Remot Kontrol (Daikin):** Tekan dan tahan tombol *Cancel* selama 5 detik hingga indikator temperatur menunjukkan "00". Tekan tombol *Cancel* berulang kali hingga unit indoor berbunyi nada tit panjang (*continuous beep*). Kode yang tertera pada layar saat bunyi panjang adalah kode gangguan aktif.
* **Metode Kedipan LED (Panasonic / LG):** Hitung jumlah interval kedipan lampu *Timer* atau *Power*. Setiap kombinasi jeda menandakan modul yang bermasalah.

### Rujukan Masalah Umum Berdasarkan Kategori

* **Sirkuit Sensor Termistor:** Terputus (*open*) atau korsleting (*short*). Nilai resistansi ohm pada thermistor tembaga (pipa) atau plastik (suhu udara) melenceng dari standar kurva kΩ pabrikan.
* **Motor Kipas Indoor (PG / BLDC Motor):** Modul kontrol tidak menerima sinyal balik *Hall sensor* putaran kipas selama waktu toleransi (umumnya 10–30 detik).
* **Komunikasi Indoor-Outdoor:** Kabel penghubung data (kabel terminal 3) putus atau komponen *optocoupler* pada sirkuit komunikasi PCB rusak.