# Esperienza Preliminare

## Punto 1,2,3

- Alimentazione PMT  a 1200V
Visualizzazione forma d'onda con oscilloscopio.
    Scala orizzontale 25ns/div
    Trigger negative edge -30.4mV 
    Impulso circa 1 divisione
    rate trigger 6kHz

- Alimentazione a 1000V
    "Il segnale è più carino"
    Diminuita l'ampiezza ma difficile da quantificare
    rate trigger in basso a destra 980-1100 Hz

- Alimentazione 900V
rate trigger 150-300

- Alimentazione 800V
rate triggger 40-120 circa 100 Hz

Si può fare la media del segnale! (non è una buona idea)

Presi 6 valori del rate osciloscopio variando l'alimentazione per farne la media 
abbiamo tenuto 4 cifre
A 700V già si hanno rate <10Hz 
A 600V non si rileva niente

Morale: il punto di lavoro deve essere sopra i 700V, sopra i 1300V si blocca.



NOTA! Schiacciare seuenza singola per stoppare su frame singolo

## Punto 4
Collegamento PMT1 a discriminatore per visualizzare segnale PMT1 e segnale discriminato su oscilloscopio.
Vediamo ritardo del segnale discriminato, vediamo traccia orizzontale (il discriminatore non scatta sempre)
Misura della soglia del segnale del disciminatore:
Variazione della soglia con in cacciavite
(Problema: multimetro e discriminatore non stanno andando d'accordo)


Tanti scatti solo colpa del noise rate.
Trovare punto di lavoro in cui vediamo solo i raggi cosmici (frequenza raggi cosmici circa 80-100 Hz) 
per vedere solo raggi cosmici sarebbe 800-900V ma così ne vediamo pochi, a ddp più alta c'è più noise ma poi si abbatte con le coincidenze.


Misura tempo impulso discriminatore: da 10ns a 58ns =48ns
Misura ritardo discriminatore: 14ns da inizio discesa a inizio discesa. 12ns invece se consideriamo che il segnale deve scendere a -20mV prima di far scattare il discriminatore. (misure con cursori)

Effetto soglia discriminatore: triggerando su CH2, negative edge -540 mV.
soglia -0.23 V rate 365 460 355
soglia -0.24 V rate 385 464 448
soglia -0.30 V rate 275 292 307 345
soglia -0.46 V rate 107 110 140 118
soglia -0.60 V rate 66 26 55 56 26 49



### problema incontrato
L'alimentatore era alimentato nel crate e rubava tutta la corrente agli altri moduli :/

## Punto 5
soglia discriminatore -0.30V
Conteggi PMT1 2765, 2765, 2754 in 10s
Conteggi PMT2 

## Giorno 2

alimentazioni PMT
1104 V
1104 V
1104 V

I cavi con qui stiamo collegando i pmt a discriminatori e i discriminatori allo scaler sono con ritardo uguale.

Problema: al pmt 1 entrano fotoni non autorzzati e boh contava 800 eventi in 1 secondo quando dovevanoe ssere 200. (è stato coperto con un telo e ci hanno abbassato la luce ora siamo a 280 circa :) ).

Nota: rilevatore 1 più lontano da 2 da quanto lo sia 2 rispetto a 3. (ci aspettiamo 12 < 23)

Misura ritardo introdotto dal modulo di coincidenza: visualizzando con l'oscilloscopio i segnali del discriminatore e dell'unità di coincidenza e misurando con i cursori il ritardo. 12.2 ns, 14.2, 14.2, 14.4 ns. Di questi, 2ns sono di cavo.

Cavi tra dscriminatore a coincidenza 2ns e da coicidenza a oscilloscopio 2 ns.


Misura con due moduli di coincidenze per l'efficienza. Siamoa ncora a 1104V

L'output dei tre PMT sono stati collegati ai discriminatori con cavi da 3ns, e allo scaler con cvi da 4ns
Cavi da 2ns tra discriminatore e coincidenze.