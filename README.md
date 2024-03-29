Welkom op deze repo. Hier wordt alle informatie gebundeld die je al beginner kan gebruiken om binnen HBO-ICT (en specifiek gericht op TI) met Linux aan de slag kunt. Stel gerust vragen in de issues, of draag toevoegingen aan via een PR.

## Linux gebruiken voor BMPTK/HWLIB (OOPC en verder)
Wouter heeft hiervoor een [speciale repository](https://github.com/wovo/installers) ingericht. Volg de instructies in de README.

## FAQ
- **Hoe maak ik verbinding met eduroam?**
  - Bij security heb je bij security de volgende instellingen nodig:
    - Kies voor "WPA & WPA2 Enterprise"
    - Authentication is "Protected EAP (PEAP)"
    - Anonymous Identity mag leeg blijven
    - Certificate staat [elders in de repo](https://github.com/HU-TechLab-Projects/TI-Linux/blob/master/DigiCert%20Assured%20ID%20Root%20CA.crt), deze kun je downloaden en hier naar verwijzen (het werkt ook zonder certificate, maar dat is minder veilig)
    - PEAP version mag "Automatic" blijven
    - Inner authentication is "MSCHAPv2"
    - Username is je HU-email
    - Password is je HU-wachtwoord
- **Op Ubuntu kan ik niet met de rechtermuisknop klikken?**
  - Gnome heeft als standaardinstelling "2-finger click" als rechtermuisknop ingesteld staan; dit kun je bij Settings aanpassen?
