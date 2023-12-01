MAJ = input ( " Ekri an MAJISKIL : ")
Min = MAJ.lower()
print (Min)

Fraz= input ( " Ekri yon fraz: ")
mo = Fraz.split()
print (mo)

fraz = input ( " Ekri yon fraz:")
frazM= fraz.title()
print (frazM)

fraz = input ( " Ekri yon fraz:")
inisyal = [mo[0].upper() for mo in fraz.split()]
inisyal = ' '.join(inisyal)
print(inisyal)

fraz = input ( " Ekri yon fraz:")
nouvo_fraz = fraz.replace('a','@')
print(nouvo_fraz)

fraz = input ( " Ekri yon fraz:")
mo_nv = fraz[::-1].upper()
print (mo_nv)

fraz = input ( " Ekri yon fraz:")
nospace= fraz.replace(' ','')

