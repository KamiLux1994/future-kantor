Witam, chcia�bym w paru krokach opisa� proces uruchomienia aplikacji kantor:

1. Zainstaluj najnowsz� wersj� Node.js (je�eli nie masz) "https://nodejs.org/en/download/", (node package manager instalowany jest razem z nim).

2. Zainstaluj najnowsz� wersj� Angular-CLI, u�ywaj�c npm -> "npm install -g @angular/cli".

3. Otw�rz g��wny folder projektu (ten w kt�rym jest package.json).

4. W power shellu lub consoli wejd� w ten folder (przyk�adowa �cie�ka: "C:\Users\user\kantor")
   i wpisz komende -> "npm install", projekt po pobraniu si� bibliotek powinien zajmowa� 267mb.

5. Po pobraniu si� bibliotek w nowo utworzonym folderze node_modules, 
   wpisz w tym samym miejscu komende "ng serve --open --port 4200 --proxy-config proxy.config.json",
   lub uruchom komende (start) z 'npm Scripts'.
