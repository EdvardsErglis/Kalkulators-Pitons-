import math   # Importē matemātikas programmēšanas bibliotēku

while True: # Izdara bezgalīgas cilpas
    x = int(input("Ievadi Pirmo Nummuru: ")) # Programma pasaka, lai lietotājs ievada pirmo ciparu
    x1 = int(input("Ievadi Otro Nummuru: ")) # Programma pasaka, lai lietotājs ievada otro ciparu
    x2 = input("Ievadi matemātisko veidu (+, -, /, *, //, **, %): ") # Programma liek lietotājam izvēlēties un ievadīt, vienu no matemātiskajām vērtībām.

    if x2 == "+":
        print(f"Result: {x + x1}") # pirmais norādītājs
    elif x2 == "-":
        print(f"Result: {x - x1}")
    elif x2 == "/":
        print(f"Result: {x / x1}")
    elif x2 == "*":
        print(f"Result: {x * x1}")
    elif x2 == "//":
        print(f"Result: {x // x1}")
    elif x2 == "**":
        print(f"Result: {x ** x1}") # elif-i ir otra opcija, ja pirmā opcija (if) nesakrīt.
    elif x2 == "%":
        print(f"Result: {x % x1}")  # "x2" tajos elif un if ir mainīgais, kuram piešķīru datus (skat. koda sākumā) 
    else:
        print("Invalid operator") # else beidz visu koda operāciju

    again = input("Gribi vel turpināt kalkulātoru? (ja/ne): ").lower() # "again" pajautā vai lietotājs grib velreiz turpināt lietot šo programmu. "Input" liek lietotājam vadīt kodu. ".lower()" padara visus ievadītos burtus, mazus, kaut vai, ja ievada "JA".
    if again != "ja": # "if again != "ja"", nozīmē kad, ja atbilde nav "ja", tad programma aktivizēs "break" funkicju un cilpa beigsies un programma ar to arī beigsies. Praktiski sakot, "!" izslēdz jebko, kas ievadīts aiz "=" zīmes, pēdiņās.
        break # Beidz programmas cilpu un, tai skaitā, visu pašu programmu.
