# California Housing – modellering som beslutsunderlag 
## Spår B – Klassificering (identifiera “högpris-områden”)

Ett maskininlärningsprojekt som bygger ett beslutsstöd för att hjälpa kommuner och fastighetsaktörer att fatta beslut om dem ska lägga tid och resurser på ett nytt område.
Kunden vill bygga ett verktyg som kan användas när ett nytt område (eller ett område som inte är analyserat ännu) dyker upp. De har tillgång till områdets egenskaper (geografi, hushåll, inkomstnivåer osv.) men de vet inte bostadsvärdet än.
För att prioritera var man ska lägga tid och resurser vill de kunna få en snabb klassning: ”ser detta ut som ett högpris-område?”


## Installation
Klona repot och installera beroenden:
git clone https://github.com/emanuelssonlinnea-rgb/ML_Individuell_Uppgift.git

Skapa och aktivera virtuell miljö:
python -m venv .venv

Windows PowerShell:
.venv\Scripts\Activate

macOS/Linux:
source .venv/bin/activate

installera beroenden:
cd ML_Grupp5 python -m pip install -r requirements.txt
Användning

Öppna och kör följande notebook:

    ML_Uppgift1_Linnea.Emanuelsson.ipynb — Innehåller EDA, preprocessing och pipeline

## Miljö

Python: 3.13.7
Paket: Numpy, Pandas, Matplotlib, Jupyter, scikit-learn (se requirements.txt)
