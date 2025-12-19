Slika vezja
![alt text](vaja1_vezje.jpeg)



Slika Pinout
![alt text](vaja1_PINOUT.png)


Odgovori na vprašanja:

__b)__ Zelena LED je priključena na pin PA5, modra tipka pa na pin PC13


__c)__ Nucleo-L476RG ima 3 pretvornike ADC


__d)__ Da je vmes med njimi konflikt, ker so že zasedeni, to odpravimo tako, da ostalim ADC pinom, ki jih ne uporabljamo, izklopimo funkcije 


__e)__ Vseh vodnih kanalov je 4


__f)__ Poleg pina se izpiše ADC3_IN1, to je pin PC0


__i)__ 

       6-bit, od 0 do 63,

       8-bit, od 0 do 255,

       10-bit, od 0 do 1023,

       12-bit, od 0 do 4095




__Komentar:__
Stvar je delovala kot je morala, z vrtenjem potenciometra se je spreminjala 8.bitna vrednost od 0 do 255 kot bi morala, izpisovala se je v debugger načinu.
