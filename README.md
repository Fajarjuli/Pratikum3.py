# Pratikum3.py
# LUAS DAN KELILING LINGKARAN

import math

def hitung_luas_lingkaran(jari_jari): 
    return math.pi * jari_jari ** 2

def hitung_keliling_lingkaran(jari_jari): 
    return 2 * math.pi * jari_jari

# INPUT JARI JARI

jari_jari = float(input("Masukkan panjang jari-jari lingkaran: "))

# HITUNG LUAS DAN KELILING 

luas = hitung_luas_lingkaran(jari_jari) 
keliling = hitung_keliling_lingkaran(jari_jari)

# TAMPILAN HASIL

print(f"Luas lingkaran dengan jari-jari {jari_jari} adalah {luas:.2f}") 
print(f"Keliling lingkaran dengan jari-jari {jari_jari} adalah {keliling:.2f}")
