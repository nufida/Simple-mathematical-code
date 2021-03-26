# Mencari rata-rata dari kumpulan angka yang diinput user (Python)

data_angka = list()
banyaknya = input("Masukkan jumlah data angka:")
print("Masukkan data angka:")
for i in range(int(banyaknya)):
    n = input("angka:")
    data_angka.append(float(n))
print("Data angka=", data_angka)

hasil = sum(data_angka)

mean = hasil / int(banyaknya)
print("Rata-rata yang dihasilkan =", mean)


