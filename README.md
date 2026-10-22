# prak.algoritma
#input nilai mahasiswa
tugas = int(input("Nilai Tugas : "))
uts = int(input("Nilai UTS : "))
uas = int(input("Nilai UAS : "))
kehadiran = int(input("Kehadiran : "))

#proses
nilai_akhir = (20/100 * tugas) + (30/100 * uts) + (50/100 * uas)

print("Nilai Akhir :", nilai_akhir)

if nilai_akhir >= 85 and kehadiran >= 90 and nilai_akhir % 2 == 0:
    print("Status : LULUS DENGAN PREDIKAT")
elif nilai_akhir >= 75 and kehadiran >= 80:
    print("Status : LULUS")
else:
    print("Status : BELUM LULUS")