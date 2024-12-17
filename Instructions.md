# FPS-Boost Guide for Marvel Rivals

Denne guiden hjelper deg med å øke FPS og forbedre performance plus deaktivering av mus akselerasjon i Marvel Rivals. Vær oppmerksom på at enkelte innstillinger kan redusere grafikkvaliteten, men de vil gi deg høyere FPS.



## 1) Endringer i in-game innstillinger

- Anti-Aliasing og Super Resolution Type: Sett til `TAAU`.
- Render Scaling: Sett til 50-60%.
 ### Eller
- AMD FSR
- Render scaling: sett til 100%.

Merk: Disse endringene kan redusere grafikkvaliteten, men vil gi deg en betydelig FPS-økning. AMD FSR metoden for deg til å droppe litt fps men er best til en competetivt advantage

## 2) INI-justeringer

1. Naviger til konfigurasjonsmappen:
   - Gå til `C:\Users\DITT_NAVN\AppData\Local\Marvel\Saved\Config\Windows`.

2. Opprett en fil kalt "Engine.ini":
   - Lag en ny tekstfil i denne mappen og gi den navnet `Engine.ini`.

3. Lim inn en av følgende konfigurasjoner:\
[Standard Konfigurasjon](https://pastebin.com/DGiLxGgp)\
[Mer performance orientert Konfigurasjon](https://pastebin.com/GpwmPxpc)


5. Lagre filen:
   - Husk å lagre filen som en `.ini`-fil, ikke en `.txt`-fil.

Merk: Disse endringene kan redusere grafikkvaliteten, men vil gi deg en stor FPS-økning.
Merk: Hvis systemet ditt er CPU-bundet, legg til følgende under `[SystemSettings]` i `Engine.ini`:

```ini
r.RHICmdUseParallelAlgorithms=1
r.RHICmdAsyncCompute=1
```

Hvis systemet ditt er GPU-bundet, legg til følgende i `Engine.ini`:

```ini
r.RHICmdUseParallelAlgorithms=0
r.RHICmdAsyncCompute=0
```

## 3) Deaktiver museakselerasjon

1. Naviger til konfigurasjonsmappen:
   - Gå til `C:\Users\DITT_NAVN\AppData\Local\Marvel\Saved\Config\Windows`.

2. Opprett en fil kalt "Input.ini":
   - Lag en ny tekstfil i denne mappen og gi den navnet `Input.ini`.

3. Lim inn følgende innhold i `Input.ini`:

   ```ini
   [/script/engine.inputsettings]
   bEnableMouseSmoothing=False
   bViewAccelerationEnabled=False
   bDisableMouseAcceleration=False
   RawMouseInputEnabled=1
   ```

4. Lagre filen:
   - Husk å lagre filen etter at du har limt inn innholdet.

Merk: Disse innstillingene deaktiverer museakselerasjon og glatting, noe som kan forbedre presisjonen i spillet.

For en visuell veiledning om hvordan du deaktiverer museakselerasjon i Marvel Rivals, kan du se denne videoen:
[Deaktiver museakselerasjon i Marvel Rivals](https://www.youtube.com/watch?v=2-5MKrcgk1A)

Merk: Personen i videon bruker et annet metode men merk at begge metoder funker og begge er effektive, grunnen til at jeg valgte å lage et egen fil er så at man for ha mer kontroll på hvor filene ligger og ikke accidentally trykker på helt feil konfig settings.

## 4) Andre tips for FPS-forbedringer

- Installer spillet på en SSD: Dette kan forbedre laste- og lastetider betydelig.
- Deaktiver overlays: Skru av overlays fra Steam, Nvidia/AMD, Discord, etc.
- Oppdater drivere: Installer de nyeste driverne fra NVIDIA eller AMD.
- Lukk unødvendige programmer: Lukk nettleseren og andre programmer mens du spiller, spesielt hvis du har mindre enn 32 GB RAM.
- Juster NVIDIA Control Panel-innstillinger:
  - Sett Low Latency til `On`.
  - Sett V-Sync til `Fast`.
  - Øk Shader Cache Size til 100 GB.
- Øk sidefilen: Hvis du har 16 GB RAM, kan du øke sidefilen for å redusere stuttering og krasjer.
- Sjekk XMP i BIOS: Sørg for at XMP er aktivert i BIOS for å sikre optimal RAM-hastighet.
- Start spillet på nytt: Start spillet på nytt hver noen timer for å unngå minnelekkasje og ytelsesforringelse over tid.

Merk: Noen av disse endringene kan redusere grafikkvaliteten, men vil gi deg en betydelig FPS-økning.

## Avslutning

Skriptet er fullført. Husk at enkelte endringer kan påvirke grafikken negativt, men vil gi bedre FPS. Husk å lagre og sikkerhetskopiere konfigurasjonsfilene før du gjør endringer.


## Denne guiden gir en strukturert tilnærming til å øke FPS i Marvel Rivals, med klare trinn og merknader for å sikre at brukeren forstår konsekvensene av hver endring.



 
