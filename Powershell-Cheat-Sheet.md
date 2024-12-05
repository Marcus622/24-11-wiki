# Wichtige PowerShell-Befehle

## 1. **Systeminformationen anzeigen**
   - **`Get-ComputerInfo`**  
     Zeigt detaillierte Informationen über das System an.
     
   - **`Get-Process`**  
     Listet alle laufenden Prozesse auf.

   - **`Get-Service`**  
     Zeigt alle installierten und laufenden Dienste auf dem Computer an.

   - **`Get-EventLog -LogName System`**  
     Zeigt Systemereignisprotokolle an.

## 2. **Verwalten von Dateien und Verzeichnissen**
   - **`Get-ChildItem`** (alias `dir` oder `ls`)  
     Listet Dateien und Ordner im aktuellen Verzeichnis auf.

   - **`Set-Location`** (alias `cd`)  
     Wechselt das Verzeichnis.

   - **`Copy-Item`**  
     Kopiert eine Datei oder ein Verzeichnis.

   - **`Move-Item`**  
     Verschiebt eine Datei oder ein Verzeichnis.

   - **`Remove-Item`** (alias `del`)  
     Löscht eine Datei oder ein Verzeichnis.

   - **`New-Item`**  
     Erstellt eine neue Datei oder ein neues Verzeichnis.

## 3. **Verwaltung von Benutzern und Gruppen**
   - **`Get-LocalUser`**  
     Listet alle lokalen Benutzerkonten auf.

   - **`Get-LocalGroup`**  
     Listet alle lokalen Gruppen auf.

   - **`New-LocalUser`**  
     Erstellt ein neues Benutzerkonto.

   - **`Add-LocalGroupMember`**  
     Fügt einen Benutzer einer Gruppe hinzu.

   - **`Remove-LocalUser`**  
     Löscht ein Benutzerkonto.

## 4. **Netzwerk und IP-Informationen**
   - **`Get-NetIPAddress`**  
     Zeigt die IP-Adressen des Systems an.

   - **`Test-Connection`** (alias `ping`)  
     Testet die Netzwerkverbindung zu einer IP-Adresse oder einem Hostnamen.

   - **`Get-NetAdapter`**  
     Listet alle Netzwerkadapter auf.

   - **`Set-NetIPAddress`**  
     Konfiguriert die IP-Adresse eines Adapters.

## 5. **Prozessmanagement**
   - **`Start-Process`**  
     Startet einen neuen Prozess (z.B. ein Programm).

   - **`Stop-Process`**  
     Beendet einen laufenden Prozess.

   - **`Get-Process`**  
     Zeigt eine Liste der laufenden Prozesse an.

   - **`Get-Process -Name <Prozessname>`**  
     Zeigt spezifische Prozesse anhand des Namens an.

   - **`Stop-Process -Name <Prozessname>`**  
     Beendet einen Prozess anhand des Namens.

## 6. **Pipelines und Skripting**
   - **`|`** (Pipeline)  
     Leitet die Ausgabe eines Befehls als Eingabe an den nächsten Befehl weiter.

   - **`ForEach-Object`**  
     Wird verwendet, um Elemente einer Sammlung zu iterieren und für jedes Element eine Aktion auszuführen.

   - **`Select-Object`**  
     Wählt bestimmte Eigenschaften oder Objekte aus einer Sammlung aus.

## 7. **Verwalten von Software und Updates**
   - **`Get-WmiObject -Class Win32_Product`**  
     Zeigt installierte Programme auf dem System an.

   - **`Get-HotFix`**  
     Zeigt die installierten Windows-Updates an.

   - **`Install-Package`**  
     Installiert Pakete mit einem Paket-Manager wie `nuget` oder `chocolatey`.

   - **`Uninstall-Package`**  
     Deinstalliert ein Paket.

## 8. **Fehlerbehandlung**
   - **`Try-Catch`**  
     Fängt Fehler ab und ermöglicht eine benutzerdefinierte Behandlung.
     ```powershell
     try {
         # Code, der Fehler verursachen könnte
     } catch {
         # Fehlerbehandlungscode
     }
     ```

   - **`$Error`**  
     Zeigt die letzte Fehlermeldung an.

   - **`$?`**  
     Gibt an, ob der letzte Befehl erfolgreich war (True/False).

## 9. **Verwalten von Tasks und Zeit**
   - **`Get-ScheduledTask`**  
     Listet geplante Aufgaben auf.

   - **`Start-ScheduledTask`**  
     Startet eine geplante Aufgabe.

   - **`New-ScheduledTask`**  
     Erstellt eine neue geplante Aufgabe.

   - **`Stop-ScheduledTask`**  
     Stoppt eine geplante Aufgabe.

## 10. **Verwaltung von Systemressourcen**
   - **`Get-VM`** (für Hyper-V)  
     Listet alle virtuellen Maschinen auf.

   - **`Start-VM`**  
     Startet eine virtuelle Maschine.

   - **`Stop-VM`**  
     Stoppt eine virtuelle Maschine.
Dieses Markdown-Format stellt eine strukturierte Übersicht der wichtigsten PowerShell-Befehle dar. Du kannst es in eine Markdown-Datei kopieren oder in einem geeigneten Editor verwenden.


Du:
zeige mir die letzte antwort im markdown an
ChatGPT:
ChatGPT
Hier ist die letzte Antwort im Markdown-Format:

markdown
Code kopieren
# Wichtige PowerShell-Befehle

## 1. **Systeminformationen anzeigen**
   - **`Get-ComputerInfo`**  
     Zeigt detaillierte Informationen über das System an.
     
   - **`Get-Process`**  
     Listet alle laufenden Prozesse auf.

   - **`Get-Service`**  
     Zeigt alle installierten und laufenden Dienste auf dem Computer an.

   - **`Get-EventLog -LogName System`**  
     Zeigt Systemereignisprotokolle an.

## 2. **Verwalten von Dateien und Verzeichnissen**
   - **`Get-ChildItem`** (alias `dir` oder `ls`)  
     Listet Dateien und Ordner im aktuellen Verzeichnis auf.

   - **`Set-Location`** (alias `cd`)  
     Wechselt das Verzeichnis.

   - **`Copy-Item`**  
     Kopiert eine Datei oder ein Verzeichnis.

   - **`Move-Item`**  
     Verschiebt eine Datei oder ein Verzeichnis.

   - **`Remove-Item`** (alias `del`)  
     Löscht eine Datei oder ein Verzeichnis.

   - **`New-Item`**  
     Erstellt eine neue Datei oder ein neues Verzeichnis.

## 3. **Verwaltung von Benutzern und Gruppen**
   - **`Get-LocalUser`**  
     Listet alle lokalen Benutzerkonten auf.

   - **`Get-LocalGroup`**  
     Listet alle lokalen Gruppen auf.

   - **`New-LocalUser`**  
     Erstellt ein neues Benutzerkonto.

   - **`Add-LocalGroupMember`**  
     Fügt einen Benutzer einer Gruppe hinzu.

   - **`Remove-LocalUser`**  
     Löscht ein Benutzerkonto.

## 4. **Netzwerk und IP-Informationen**
   - **`Get-NetIPAddress`**  
     Zeigt die IP-Adressen des Systems an.

   - **`Test-Connection`** (alias `ping`)  
     Testet die Netzwerkverbindung zu einer IP-Adresse oder einem Hostnamen.

   - **`Get-NetAdapter`**  
     Listet alle Netzwerkadapter auf.

   - **`Set-NetIPAddress`**  
     Konfiguriert die IP-Adresse eines Adapters.

## 5. **Prozessmanagement**
   - **`Start-Process`**  
     Startet einen neuen Prozess (z.B. ein Programm).

   - **`Stop-Process`**  
     Beendet einen laufenden Prozess.

   - **`Get-Process`**  
     Zeigt eine Liste der laufenden Prozesse an.

   - **`Get-Process -Name <Prozessname>`**  
     Zeigt spezifische Prozesse anhand des Namens an.

   - **`Stop-Process -Name <Prozessname>`**  
     Beendet einen Prozess anhand des Namens.

## 6. **Pipelines und Skripting**
   - **`|`** (Pipeline)  
     Leitet die Ausgabe eines Befehls als Eingabe an den nächsten Befehl weiter.

   - **`ForEach-Object`**  
     Wird verwendet, um Elemente einer Sammlung zu iterieren und für jedes Element eine Aktion auszuführen.

   - **`Select-Object`**  
     Wählt bestimmte Eigenschaften oder Objekte aus einer Sammlung aus.

## 7. **Verwalten von Software und Updates**
   - **`Get-WmiObject -Class Win32_Product`**  
     Zeigt installierte Programme auf dem System an.

   - **`Get-HotFix`**  
     Zeigt die installierten Windows-Updates an.

   - **`Install-Package`**  
     Installiert Pakete mit einem Paket-Manager wie `nuget` oder `chocolatey`.

   - **`Uninstall-Package`**  
     Deinstalliert ein Paket.

## 8. **Fehlerbehandlung**
   - **`Try-Catch`**  
     Fängt Fehler ab und ermöglicht eine benutzerdefinierte Behandlung.
     ```powershell
     try {
         # Code, der Fehler verursachen könnte
     } catch {
         # Fehlerbehandlungscode
     }
     ```

   - **`$Error`**  
     Zeigt die letzte Fehlermeldung an.

   - **`$?`**  
     Gibt an, ob der letzte Befehl erfolgreich war (True/False).

## 9. **Verwalten von Tasks und Zeit**
   - **`Get-ScheduledTask`**  
     Listet geplante Aufgaben auf.

   - **`Start-ScheduledTask`**  
     Startet eine geplante Aufgabe.

   - **`New-ScheduledTask`**  
     Erstellt eine neue geplante Aufgabe.

   - **`Stop-ScheduledTask`**  
     Stoppt eine geplante Aufgabe.

## 10. **Verwaltung von Systemressourcen**
   - **`Get-VM`** (für Hyper-V)  
     Listet alle virtuellen Maschinen auf.

   - **`Start-VM`**  
     Startet eine virtuelle Maschine.

   - **`Stop-VM`**  
     Stoppt eine virtuelle Maschine.