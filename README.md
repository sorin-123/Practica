# Practică — Programare PLC Siemens (TIA Portal, FactoryIO, HMI)

Repository cu proiectele realizate în cadrul stagiului de practică desfășurat la **Alewijnse Marine Galați**.

**Student:** Sorin Gabriel Blaga
**Facultatea de Automatică și Calculatoare — Universitatea Tehnică „Gheorghe Asachi” din Iași**

## Descriere

Activitatea a constat în programarea și testarea automatelor programabile (PLC) Siemens S7-1200 folosind mediul **TIA Portal**, atât pe un stand fizic (module I/O digitale/analogice, panou HMI TP700 Comfort), cât și în simulatorul industrial **FactoryIO**. Proiectele acoperă cele trei limbaje de programare PLC (LAD, FBD, SCL), comunicație PLC–PLC și proiectare de interfețe HMI.

## Conținut

- **Exerciții PLC (LAD/FBD/SCL)** — automenținere, interblocare (interlock), procese start/stop/avarie, citire și scalare semnal analogic (NORM_X/SCALE_X), alarme de nivel cu histerezis.
- **Comunicație PLC–PLC** — schimb de date prin blocurile PUT/GET, tip de date utilizator (UDT), heartbeat și watchdog de comunicație.
- **Exerciții suplimentare de formare** — set de aplicații standard de dificultate crescătoare: bandă transportoare, macara, instalație tanc, ușă rulantă, parcare auto, control de nivel, scări rulante, uși turnante, seră de hobby, iaz de grădină, instalații de extracție/răcire etc.
- **Simulări FactoryIO** — conectare PLC↔FactoryIO prin driverul Siemens S7-1200/1500, depozit automatizat (ASRS) cu macara și rafturi, linie de transport cu braț de sortare și robot de paletizare.
- **Panou HMI (TP700 Comfort)** — ecrane de operare (Garden/Pompa, Semafor etc.), animații, indicatori de stare, configurare conexiune PLC–HMI.

## Tehnologii folosite

| Categorie       | Detalii                                              |
|-----------------|-------------------------------------------------------|
| PLC             | Siemens S7-1200 (CPU 1215C DC/DC/Rly), modul SM 1234 AI/AQ |
| Software        | TIA Portal (Step 7, WinCC)                            |
| Limbaje         | LAD, FBD, SCL                                          |
| HMI             | Siemens TP700 Comfort                                  |
| Simulare        | FactoryIO                                              |
| Rețea           | PROFINET                                               |

## Structură

```
├── Siemens/            
├── Siemens/FactoryIO   # Scene FactoryIO și logica de control asociată
├── Siemens/Project     # Proiecte TIA Portal — exerciții LAD/FBD/SCL
└── docs/              # Raport de activitate și documentație
```



## Raport

Raportul complet de activitate (descrierea standului, a exercițiilor și a simulărilor, cu capturi de ecran) se află în folderul `docs/`.