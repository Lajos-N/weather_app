# Java Wetter-Anwendung

Dieses Projekt ist eine in Java entwickelte, plattformunabhängige Wetter-Anwendung, die sich aktuell in der Planungsphase befindet. Ziel ist es, eine moderne, leicht erweiterbare und skalierbare Anwendung zu erstellen, welche Echtzeit- sowie Vorhersagedaten von verschiedenen Wetterdiensten bereitstellt.

## Inhaltsverzeichnis
- [Java Wetter-Anwendung](#java-wetter-anwendung)
  - [Inhaltsverzeichnis](#inhaltsverzeichnis)
  - [Beschreibung](#beschreibung)
  - [Geplante Hauptfunktionen](#geplante-hauptfunktionen)
  - [Entwicklungspläne und Ablauf](#entwicklungspläne-und-ablauf)
  - [Struktur und Entwicklungs-Branches](#struktur-und-entwicklungs-branches)
  - [Systemvoraussetzungen](#systemvoraussetzungen)
  - [Installation](#installation)
  - [Verwendung](#verwendung)
  - [Mitarbeit](#mitarbeit)
  - [Lizenz](#lizenz)

---

## Beschreibung
Dieses Projekt ist eine Java-basierte Wetter-Anwendung, die darauf abzielt, eine modulare und skalierbare Architektur zu bieten. Sie soll sich problemlos mit verschiedenen Wetter-APIs (z. B. OpenWeatherMap, WeatherAPI, etc.) verbinden lassen und Echtzeit- sowie Vorhersageinformationen aus mehreren Datenquellen anzeigen.

Da sich das Projekt noch in der Planungsphase befindet, können sich die genauen Funktionen und technischen Details noch ändern.

## Geplante Hauptfunktionen
- **Echtzeit-Wetterdaten** aus mehreren APIs (z. B. OpenWeatherMap, WeatherAPI usw.)  
- **Stündliche und tägliche Wettervorhersage**  
- **Benutzeroberfläche** (möglicherweise als Desktop- und/oder Webanwendung)  
- **Erweiterbares Modulkonzept** zur einfachen Integration neuer Anbieter  
- **Warnmeldungsfunktion** für extreme Wetterbedingungen  

## Entwicklungspläne und Ablauf
1. **Recherche** und Anforderungsanalyse – Auswahl der zu nutzenden APIs, Klärung von Lizenz- und Nutzungsbedingungen.  
2. **Planung** – Architekturdesign der Anwendung, modulare Struktur, Datenmodelle.  
3. **Proof of Concept (PoC)** – Erste Implementierung der API-Aufrufe und Datenverarbeitung/-speicherung.  
4. **Benutzeroberfläche** (GUI) – Entwurf (Desktop/Web), Erstellung von Layouts und Mockups.  
5. **Funktionsentwicklung** – Schrittweiser Ausbau der Funktionalität (Vorhersagen, Warnungen, automatische Synchronisierung etc.).  
6. **Testen und Fehlerbehebung** – Unit-Tests, Integrationstests, kontinuierliche Überprüfung der Endpunkte.  
7. **Dokumentation** – Aktualisierung von README, Wiki, API-Beschreibungen.  

Dieser Plan kann bei Bedarf flexibel angepasst werden, um auf neue Anforderungen und mögliche technische Grenzen zu reagieren.

## Struktur und Entwicklungs-Branches
- **`main`-Branch**: Enthält den stabilen Code; hier landet nur getesteter und freigegebener Code.  
- **`dev`-Branch**: Hauptentwicklungszweig, in den neue Funktionen und Änderungen eingepflegt werden, bevor sie in `main` gemergt werden.  
- **Weitere Feature-Branches**: Für jede neue Funktion, Bugfix oder experimentelle Entwicklung. Jede Änderung wird in einem eigenen Branch entwickelt und per Pull Request in den `dev`-Branch übernommen.

Es wird empfohlen, für jede neue Funktion bzw. Änderung einen eigenen Branch zu verwenden, um die kontinuierliche Integration zu erleichtern und Merge-Konflikte zu minimieren.

## Systemvoraussetzungen
- **Java 17** oder neuer  
- **Maven** oder **Gradle** (für das Build-Management)  
- **Git** (für die Versionsverwaltung)  
- Zusätzliche Abhängigkeiten für APIs und Module werden später ergänzt  

## Installation

> **Hinweis**: Da sich das Projekt noch in der Planungsphase befindet, kann sich der Installationsablauf ändern.

1. **Repository klonen**

   **Linux**:
   ```bash
   git clone https://github.com/<Benutzername>/<Repo-Name>.git
   cd <Repo-Name>
   ```

   **Windows** (Eingabeaufforderung oder PowerShell):
   ```powershell
   git clone https://github.com/<Benutzername>/<Repo-Name>.git
   cd <Repo-Name>
   ```

2. **Projekt bauen**

   **Linux (Maven)**:
   ```bash
   mvn clean install
   ```
   **Windows (Maven)**:
   ```powershell
   mvn clean install
   ```

   **Linux (Gradle)**:
   ```bash
   gradle build
   ```
   **Windows (Gradle)**:
   ```powershell
   gradle build
   ```

3. (Zukünftig ausführlicher) **Anwendung starten**  
   - Starten Sie das Projekt über die Kommandozeile oder eine IDE (z. B. IntelliJ, Eclipse).

## Verwendung
- Aktuell ist die Anwendung noch nicht lauffähig, da sich das Projekt in der Planungsphase befindet.  
- Geplant ist eine Befehlszeilen- oder GUI-Anwendung, die Wetterdaten und Vorhersagen anzeigt.

Weitere Informationen zu Konfiguration, Argumenten und GUI-Funktionen werden ergänzt, sobald sie verfügbar sind.

## Mitarbeit
Wir freuen uns über alle Arten von Vorschlägen und Entwickler-Beiträgen. Wenn Sie das Projekt unterstützen möchten:

1. Erstellen Sie einen **Fork** des Repositories.  
2. Legen Sie einen neuen Branch an:  
   **Linux**:
   ```bash
   git checkout -b feature/neues-feature
   ```
   **Windows**:
   ```powershell
   git checkout -b feature/neues-feature
   ```
3. Implementieren Sie Ihre Änderungen und committen Sie diese.  
4. **Pushen** Sie den Branch auf GitHub:  
   **Linux**:
   ```bash
   git push origin feature/neues-feature
   ```
   **Windows**:
   ```powershell
   git push origin feature/neues-feature
   ```
5. Erstellen Sie einen **Pull Request** gegen den `dev`-Branch.  

Bitte achten Sie bei Ihren Änderungen auf sauberen, getesteten Code und führen Sie vor der Pull Request ausreichend Tests durch.

## Lizenz
Dieses Projekt wird unter der [MIT License](https://opensource.org/licenses/MIT) bereitgestellt. Den vollständigen Lizenztext finden Sie in der Datei [LICENSE](LICENSE).
