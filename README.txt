Witam, chcia³bym w paru krokach opisaæ proces uruchomienia aplikacji kantor:

1. Zainstaluj najnowsz¹ wersjê Node.js (je¿eli nie masz) "https://nodejs.org/en/download/", (node package manager instalowany jest razem z nim).

2. Zainstaluj najnowsz¹ wersjê Angular-CLI, u¿ywaj¹c npm -> "npm install -g @angular/cli".

3. Otwórz g³ówny folder projektu (ten w którym jest package.json).

4. W power shellu lub consoli wejdŸ w ten folder (przyk³adowa œcie¿ka: "C:\Users\user\kantor")
   i wpisz komende -> "npm install", projekt po pobraniu siê bibliotek powinien zajmowaæ 267mb.

5. Po pobraniu siê bibliotek w nowo utworzonym folderze node_modules, 
   wpisz w tym samym miejscu komende "ng serve --open --port 4200 --proxy-config proxy.config.json",
   lub uruchom komende (start) z 'npm Scripts'.
