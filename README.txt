VIRBALIS AR – TESTAS NR. 4 / TIKRA SLUOKSNINĖ ANIMACIJA

Ši versija naudoja jau sėkmingai išbandytą virtuvės natural-image target.
Personažas paruoštas Procreate atskirais vienodo dydžio skaidriais PNG sluoksniais:

body.png
wing.png
mouth.png

Visi trys failai išlaiko tą patį 2048 x 2048 canvas ir originalias koordinates.
Todėl jie A-Frame scenoje tiksliai persidengia.

ANIMACIJA
- body.png lieka nejudantis.
- wing.png sukamas apie virtualų pivot tašką ties sparno šaknimi.
- mouth.png sukamas apie virtualų pivot tašką ties snapo prisitvirtinimo zona.
- burna juda tik grojant memory.mp3.
- sparnas juda lėtai ir nepriklausomai nuo garso.

FAILAI
index.html
targets.mind
body.png
wing.png
mouth.png
memory.mp3

ATNAUJINIMAS GITHUB
1. Atidaryti repository virbalistest4.
2. Add file > Upload files.
3. Įkelti VISUS šio paketo failus.
4. index.html ir targets.mind turi pakeisti esamus.
5. Commit changes.
6. Palaukti GitHub Pages persidiegimo.
7. iPhone puslapį geriausia uždaryti ir atidaryti iš naujo, kad nebūtų naudojamas senas cache.

TESTAVIMAS
1. Atsistoti / atsisėsti panašioje vietoje kaip fotografuojant virtuvės target.
2. Atidaryti virbalistest4 GitHub Pages.
3. Leisti kamerą.
4. Spausti „Pradėti“.
5. Nukreipti kamerą į centrinę virtuvės dalį.
6. Atpažinus vietą turi atsirasti personažas.
7. Sparnas turi lėtai judėti.
8. Grojant garsui turi judėti snapo/burnos sluoksnis.

PASTABA
Pivot koordinatės šiame prototipe nustatytos pagal pateiktų 2048x2048 sluoksnių padėtį.
Jei sparnas ar burna sukasi ne visai apie norimą anatominę vietą, koreguojami tik
wingPivot ir mouthPivot position skaičiai index.html faile — Procreate failų perdaryti nereikia.
