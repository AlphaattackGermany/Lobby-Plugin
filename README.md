## Installation

1. Entpacke den Ordner.
2. Öffne die Eingabeaufforderung oder Microsoft Powershell.
3. Navigiere in den Ordner:
   ```shell
   cd C:\LobbyPlugin
   ```
4. Baue das Plugin mit Maven:
   ```shell
   mvn clean package
   ```
5. Gehe in den `target`-Ordner.
6. Kopiere die Datei `Lobby-<version>.jar`  
   **(NICHT `lobby.02.3.1.jar(ORIGINAL)` oder ähnliche, sondern nur die erstellte `Lobby-<version>.jar`!)**
7. Füge die `.jar`-Datei in den `plugins`-Ordner deines Servers ein.
