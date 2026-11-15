# BarberSafe – Downloads & Updates

Dieses Repository enthält **ausschließlich** die Installationsdateien von BarberSafe und die
signierten Update-Informationen. Der Quellcode ist nicht öffentlich.

| Datei (je Release) | Zweck |
|---|---|
| `BarberSafe_Setup.exe` | Installationsprogramm für Windows 10/11 (64 Bit) |
| `latest.json` | Update-Information, digital signiert (Ed25519) |

## Echtheit prüfen

BarberSafe installiert Updates nur nach Bestätigung durch die Inhaberin/den Inhaber und nur, wenn:

- die Signatur von `latest.json` mit dem im Programm hinterlegten öffentlichen Schlüssel übereinstimmt
  (Schlüssel `prod-2026`, Fingerabdruck `1572-2a39-6c63-a0f6`),
- die heruntergeladene Datei exakt die signierte Größe und SHA-512-Prüfsumme hat,
- die Datei von `github.com` über HTTPS geladen wurde.

Vor jedem Update erstellt BarberSafe automatisch eine Datensicherung. Ihre Daten bleiben auf Ihrem Computer.

Windows SmartScreen kann beim ersten Start „Unbekannter Herausgeber“ melden, weil noch kein
Code-Signing-Zertifikat verwendet wird.

---

**TR:** Bu depo yalnızca BarberSafe kurulum dosyalarını ve imzalı güncelleme bilgilerini içerir. Kaynak kod herkese açık değildir.
