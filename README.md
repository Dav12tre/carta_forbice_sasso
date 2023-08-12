#carta_forbice_sasso
import random
def carta_forbice_sasso():
    input("inizia")
    print("regole:"
          "c=carta"
          "f=forbice"
          "s=sasso")
    print("carta, forbice, sasso")
    l = ["c", "s", "f"]
    p = input(str())
    ai = random.choice(l)
    print(ai)
    perso="hai perso"
    vinto= "hai vinto"
    if ai=="c" and p=="s":
        print(perso)
    elif ai=="s" and p=="f":
        print(perso)
    elif ai=="f" and p=="c":
        print(perso)
    elif ai==p:
        print("pareggio")
    else: print(vinto)


carta_forbice_sasso()
