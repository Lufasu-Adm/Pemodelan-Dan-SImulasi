![Animasi](https://github.com/Lufasu-Adm/PemWeb/blob/main/text.gif)


## Dibuat Oleh
## Nama 
Jordan Wijayanto

## Nim
1203220149

# Pemodelan-Dan-SImulasi

## PENJELASAN ##

1. Fungsi throw_dice(system) digunakan untuk mensimulasikan pelemparan dadu. Menggunakan fungsi np.random.randint(1, 7) untuk menghasilkan nilai acak antara 1 dan 6, yang mewakili sisi dadu yang muncul. Menambahkan hasil pelemparan ke dalam state sistem.

2. Fungsi run_simulation(system, num_rolls) menjalankan simulasi pelemparan dadu sebanyak num_rolls kali. Mengulangi pemanggilan throw_dice(system) sebanyak num_rolls kali.

3. Hasil simulasi disimpan dalam state sistem, yang berisi jumlah kemunculan masing-masing sisi dadu.

4. Hasil simulasi kemudian dicetak untuk menampilkan jumlah kemunculan masing-masing sisi dadu.

5. DataFrame dibuat dari hasil simulasi menggunakan library pandas.

6. Hasil simulasi disimpan ke dalam file Excel menggunakan fungsi save_results_to_excel(results, filename).
