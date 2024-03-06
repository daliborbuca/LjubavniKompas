# LjubavniKompas

print("Dobrodošli u Ljubavni kompas!")
ime1 = input("Koje je vaše ime? \n")
ime2 = input("Koje je ime vaše simpatije? \n")

kombinovana_imena = ime1 + ime2
mala_slova = kombinovana_imena.lower()
p = mala_slova.count("p")
r = mala_slova.count("r")
a = mala_slova.count("a")
v = mala_slova.count("v")
a = mala_slova.count("a")
prva_cifra = p + r + a + v + a

l = mala_slova.count("l")
j = mala_slova.count("j")
u = mala_slova.count("u")
b = mala_slova.count("b")
a = mala_slova.count("a")
v = mala_slova.count("v")
druga_cifra = l + j + u + b + a + v

skor = int(str(prva_cifra) + str(druga_cifra))

if (skor < 10) or (skor > 90):
  print(f"Vaš skor je {skor}, slažete se kao koka-kola i mentos.")
elif (skor >= 40) and (skor <= 50):
  print(f"Vaš skor je {skor}, prilično ste kompatibilni.")
else:
  print(f"Vaš skor je {skor} , slazete se kao Wuhan i Korona.")
