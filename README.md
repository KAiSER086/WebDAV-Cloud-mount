# WebDAV Cloud Storage in Windows mounten

## Methode 1: Native Windows-Funktion "Netzwerkadresse hinzufügen" (weniger stabil, kein auto-mount on boot)

1. Öffne den **Datei-Explorer** und wechsle zu **Dieser PC**.

2. Rechtsklick und **"Netzwerkadresse hinzufügen"** auswählen.

![Dieser PC im Explorer](/Images/explorer_7s24JIiuf1.png)

3. Netzwerkadresse einfügen [https://465480-sub1.your-storagebox.de]

![Netzwerkadresse](/images/rundll32_BcEz3SxjmT.png)

4. Im **Credential Broker** deine Nutzerdaten eingeben.

![Credential Broker](/Images/CredentialUIBroker_2PguIYVMh1.png)

5. Dem **WebDAV Mount** einen Namen geben und das Setup abschließen.

![Explorer](/Images/explorer_6DDFmsxbGd.png)


## Methode 2: AirLiveDrive (Cloud-Speicher als lokales Laufwerke an, auto-mount on boot)

1. **AirLiveDrive** herunterladen und installieren.
    (https://www.airlivedrive.com/downloads/AirLiveDrive-Installer.exe)

2. Laufwerk hinzufügen.

![Laufwerk hinzufügen](/Images/AirLiveDrive_ERsOvAyc7N.png)

3. **WebDAV** auswählen.

![WebDAV auswählen](/Images/AirLiveDrive_HwsmWWRcma.png)

4. **Netzwerkadresse** und **Benutzerdaten** eingeben.

![Credentials](/Images/AirLiveDrive_LbcknIECrp.png)

5. Dem **Laufwerk** einen beliebigen **Laufwerbuchstaben** vergeben und verbinden.

![Laufwerbuchstabe](/Images/AirLiveDrive_pEAT74HKKk.png)

6. Auf das Zahnradsymbol klicken und **Verbindung beim Start herstellen** und bei belieben **Anzeigenamen** ändern.

![Settings](/Images/AirLiveDrive_AwKyOmcD6Q.png)

7. **AirLiveDrive Einstellungen** öffnen und Einstellungen anpassen.

![Settings](/Images/AirLiveDrive_VmINLHve5Q.png)

8. Der **Explorer** sollte jetzt so aussehen:

![Explorer](/Images/explorer_7qbybxZwVV.png)
