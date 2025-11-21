

nama = input("Masukkan nama siswa: ")
nilai_uts = float(input("Masukkan nilai UTS: "))
nilai_uas = float(input("Masukkan nilai UAS: "))
nilai_tugas = float(input("Masukkan nilai Tugas: "))


rata_rata = (nilai_uts + nilai_uas + nilai_tugas) / 3


if rata_rata >= 75:
    status = "Lulus"
else:
    status = "Tidak Lulus"


print("\n--- HASIL ---")
print("Nama Siswa :", nama)
print("Rata-rata  :", round(rata_rata, 2))
print("Status     :", status)
