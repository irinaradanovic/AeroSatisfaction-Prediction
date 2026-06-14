# AeroSatisfaction-Prediction

1. Struktura projekta 
data/ - Folder koji sadrži skupove podataka: 
    train.csv - Skup podataka za obučavanje modela 
    test.csv - Skup podataka za evaluaciju (testiranje) modela 
eda.ipynb - Jupiyter sveska sa eksplorativnom analizom podataka (EDA)  
aerosatisfaction.ipynb - Jupyter sveska sa pripremom podataka, treningom i evaluacijom  modela 
requirements.txt - Spisak svih neophodnih Python biblioteka 

2. Priprema okruženja  
Kako bi se obezbedilo izolovano okruženje, preporučuje se kreiranje virtuelnog okruženja. 
    1. U korenu projekta, otvorite terminal i unesite sledeću komandu: python -m venv venv 
    2. Aktivirajte virtuelno okruženje: 
    Windows: venv\Scripts\activate 
    Linux/macOS: source venv/bin/activate 
    3. Instalirajte potrebne biblioteke 
    Pokrenite komandu u terminalu: pip install -r requirements.txt 
3. Pokretanje i pregled projekta 
Projekat je podeljen u logičke celine koje se mogu pokretati i pregledati kroz razvojna 
okruženja poput Jupyter Notebook, JupyterLab ili VS Code. 
Opcija A: Pregled već pokrenutog koda 
Pošto su sve ćelije unutar datoteka eda.ipynb i aerosatisfaction.ipynb izvršene pre čuvanja, 
možete otvoriti ove datoteke u vašem razvojnom okruženju. 
Opcija B: Ponovno izvršavanje projekta od početka 
Ukoliko želite da ponovo pokrenete projekat ili izvršite izmene: Otvorite svesku po želji I 
pokrenite opet sve ćelije klikom na "Run All" ili selektujte jednu ćeliju I kliknite na ikonicu 
"Play" pored ćelije. 
Napomena za VS Code: Nakon otvaranja sveske, u gornjem desnom uglu kliknite na dugme 
"Select Kernel" i sa liste izaberite Python interpretator iz našeg kreiranog virtuelnog 
okruženja (venv). 