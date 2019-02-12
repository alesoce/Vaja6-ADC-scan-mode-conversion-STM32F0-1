# Vaja6-ADC-scan-mode-conversion-STM32F0
__________________________________________________________________________________________________________________________________________
ODGOVORI:

a) Glede na vašo razvojno ploščico in razširitveno vezje z tipkami ter potenciometri, izberite ustrezni analogni vhod, na katerem je vezan potenciometer. Kateri pin je to? PC0.
b) Določite in aktivirajte še dva analogna vhoda za zunanja potenciometra. To bosta pina PC1 in PC2.
Izbrani pini naj bodo vsi v isti grupi/skupini! Katera skupina je to? Skupina C.
c) Glede na uporabljene potenciometre izberite-obkljukajte ustrezni kanal/pin. Na zaslonu se vam mora usterzno pobarvati izbrani pin v zeleno barvo. Kaj se izpiše poleg pinov? ADC_IN10, ADC_IN11, ADC_IN12
d) V Configuration kliknemo ADC gumb. V Parameter settings izberite ločljivost pretvorbe na 8-bitno, torej je območje vrednosti od 0 ÷ 255. Clock Prescaler nastavite tako, da bo izračunana frekvenca vzorčenja 4MHz. Koliko bo izbrana vrednost parametra? Synchronous clock mode divided by 4.
e) Čas vzorčenja Sampling Time izberite 239.5 cikla. Koliko je čas vzorčenja v mikro sekundah?
62.875 µs.
f) V zavihku DMA Settings kliknite Add in v nastalem polju »select« izberite možnost ADC. Dolžina podatka pretvorbe bo 1 Byte, zato ustrezno popravite izbirno polje Data Width: Byte.
g) Kaj pomeni kratica DMA? Direct Memory Access.
__________________________________________________________________________________________________________________________________________
KOMENTAR:

S pomočjo pontencijometra ki je vgrajen na STM ploščici in dvema potenciometrama ki smo jih dodali, smo spreminjali vrednosti od 0 do 255. Program deluje brez napak. 
