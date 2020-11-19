# NIM
while True:
        hasil = int(input("Masukkan nim anda: "))
        d = 1
        a = 1
        while d <= hasil:
            print (a)
            a += 1
            if a == 10:
                a -= 9
            d += 1
