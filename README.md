# b0mb3r 💣
SMS-Bomber mit einem schönen Webinterface.

> Ich bin nicht verantwortlich für Ihre Handlungen. Durch das Herunterladen von Software aus diesem Repository stimmen Sie der [Lizenz] zu.(https://github.com/crinny/b0mb3r/blob/master/LICENSE).
# Installation
## Linux
1. Öffne ein Terminal und installiere Python und git mit deinem Paketmanager:
     Bogen / Manjaro / Antergos:
    ```bash
    pacman -S git python --needed
    ```
    Ubuntu/Debian/Deepin/any_apt_based:
    ```bash
     apt install git python
    ```
     Fedora:
    ```bash
     yum install git python
    ```
2. Klone die Repository mit "git" und navigieren Sie zum extrahiertem Ordner:
    ```bash
    git clone https://github.com/crinny/b0mb3r
    cd b0mb3r
    ```
3. Installieren Sie die Abhängigkeiten:
    ```bash
    python -m pip install -r requirements.txt
    ```
4. Binary starten
    ```bash
    python main.py
    ```
5. Wenn das Webinterface in Ihrem Browser nicht geöffnet wird, klicken Sie auf den Link im Terminal.
    
## Windows
1. Installieren Sie Python die Version 3.6, indem Sie das Installationsprogramm von der [offiziellen Website] herunterladen (https://www.python.org/downloads/).
2. Installieren Sie git für Windows, indem Sie es [von hier] herunterladen (https://git-scm.com/download/win).
3. Öffnen Sie eine Eingabeaufforderung und klonen Sie das Repository mit git. Danach wechseln Sie in den Ordner:
    ```bash
    git clone https://github.com/crinny/b0mb3r
    cd b0mb3r
    ```
4. Installieren Sie alle erforderlichen Abhängigkeiten und führen Sie das Skript aus:
    ```bash
    python -m pip install -r requirements.txt
    python main.py
    ```
5. Wenn das Webinterface in Ihrem Browser nicht geöffnet wird, klicken Sie auf den Link in der Konsole.

## Android
1. Installieren Sie [Termux] (https://play.google.com/store/apps/details?id=com.termux&hl=de).
2. Geben Sie die folgenden Befehle ein, um die erforderlichen Komponenten zu installieren:
    ```bash
    pkg install python
    pkg install git
    ```
3. Befolgen Sie die Schritte ab Schritt 3 der Installationsanweisungen für Windows.

# Update 
## Windows
1. Geben Sie den folgenden Befehl ein, um die vorherige Version zu deinstallieren:
   ```bash
   rmdir /S /Q b0mb3r
   ```
2. Befolgen Sie die Schritte ab Schritt 3 der Installationsanweisungen für Windows.
## Linux/Android
1. Führen Sie diesen Befehl aus:
   ```bash
   cd b0mb3r
   git pull
   ```
# Screenshots
⁣                           |  ⁣
:-------------------------:|:-------------------------:
![](https://github.com/crinny/b0mb3r/blob/master/assets/screenshot.png)  |  ![](https://github.com/crinny/b0mb3r/blob/master/assets/screenshot_mobile.png)
