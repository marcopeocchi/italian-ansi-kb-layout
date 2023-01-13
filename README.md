# italian-ansi-kb-layout

Layout Italiano per tastiere ANSI

# Overview
Ho sempre usato tastiere con layout US ANSI.

Windows non mette a disposizione un layout ANSI per i paesi in cui è adottato il layout ISO (al contrario di macOS).

Dopo centinaia di migliaia di `win+space` per cambiare mappatura e scrivere questi 4 caratteri infami (< > ` ~) urgeva una soluzione.

Con [Microsoft Keyboard Layout Creator (MSKLC)](https://www.microsoft.com/en-us/download/details.aspx?id=102134) ho creato questo layout
per riuscire a scrivere un pezzo di JSX senza cambiare 12000 volte layout.

### Layout default
![layout1](/img/layout.jpg)

### Layout shift
![layout1](/img/LayoutShft.jpg)

### Layout AltGr (ctrl+alt)
![layout1](/img/layoutAltGr.jpg)

### Layout Shift+AltGr
![layout1](/img/layoutShftAltGr.jpg)


# Setup

1. Impostazioni Windows
2. Data/ora e lingua
3. Lingua
4. Italiano > Opzioni
5. Aggiungi tastiera
6. Selezionare layout **Italiano - Custom**
7. Riavvia sistema

![setup1](/img/setup-1.png?raw=true)
![setup2](/img/setup-2.png?raw=true)
![setup3](/img/setup-3.png?raw=true)

# Build manuale del layout

Per utenti più esperti, o per chiunche non volesse (giustamente) scaricare un esegubile e qualche dll precompilate, nella cartella `src` è presente il layout nel formato `klc`.

Con MSKLC è possibile generare il setup della mappatura.
