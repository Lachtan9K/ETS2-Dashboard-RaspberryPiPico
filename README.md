# ETS2-Dashboard-RaspberryPiPico

## INFORMACE

### Projekt do školy SPŠ-ELIT Dobruška na předmět: Mikropočítačové systémy vyučujícím Ing. Jiří Vintera

Autor: Vojtěch Duben

Třída: T3A

Školní rok: 2024/2025

Projekt byl zadaný na základě ročníkové/pololetní práce. 

# O co se jedná ?

Udělal jsem si dashboard pro hry/simulátory, kterým se dají ovládat určité prvky např. řežim osvětlení vozů atd. Na dashboardu je 10 tlačítek a 1 vypínač na klíček, který slouží k nastartování vozu.


# CÍL

Mým cílem bylo si vytvořit něco, co bych využíval a nebylo to zbytečné. Mým cílem též bylo se naučit novým věcem co se týče programování a troubleshootingu. 


# ZÁVĚR  

Celý tento program je dělaný v CircuitPythonu. Bylo potřeba kompletně reinstalovat (stačilo nukenout) Raspberry Pi Pico na Circuit. Instalaci jsem provedl prostřednictvím aplikace Thonny, ale také se dá udělat přes tuto stránku [[3]](#ZDROJE-A-LITERATURA) kde si naistalujete soubor, který dáte do paměti RPIPICO a samo se Circuit Python nainstaluje.
Přidávám zde i samotný dokončený program, prototyp programu, youtube odkaz k vysvětlení [[5]](#YOUTUBE-VIDEO---VYSVĚTLENÍ-A-PŘEDSTAVENÍ) , návrh krabičky a knihovny které byly potřeba dát externě do Pica. Mužete je najít v druhém branchy nebo zde [[4]](#ZDROJE-A-LITERATURA).

Poprvé jsem neměl vůbec páru jak programovat v CircuitPythonu, avšak je to velice podobné MicroPythonu až na maličkosti( Je to více rozšířenější ). Čerpal jsem jak z videí programování v CircuitPythonu, ale také i z videí přesně zamřený na můj projekt a i ze zdroje ChatGPT k doladění programu k dokonalosti, zde je video kde jsem se naučil ovládat v circuit pythonu a celkově pochopit tento projekt [[1]](#ZDROJE-A-LITERATURA) . Z mého výtvoru by se mohla také udělat i macro klávesnice, zde je video kde jsem se též insiporoval [[2]](#ZDROJE-A-LITERATURA), ale já jsem se rozhodl si udělat dashboard pro Euro Truck Simulator 2, jelikož si ho někdy zahraju a bude super mít nový přístroj pro můj simulátor.  Nějaké velké problémy při projektu nebyly, avšak jsem měl problém si detekováním vstupu tlačítka. Zjistil jsem, že stačilo jen pozměnit tvar programu a vše už probíhalo v pořádku. Na projektu je 11 tlačítek, takže je jasné, že program bude celkem dlouhý, tyto tlačítka jsem nakopírovával do doby než jich tam bylo 11 a vše pokračovalo v pořádku. Program jsem poupravil tak, když podržím jakékoliv tlačítko, tak se dále bude vypisovat nějaká daná funkce. Ale u jediného tlačítko to tam není, vlastně to není ani tlačítko, ale je to vypínáč na klíček a ten bylo potřeba, aby se furt a stále nespouštěl. Projekt funguje skvěle a jsem rád, že jsem si ho opravdu udělal ( K tomu hrání to dodává ten "šmak" :) ). Každopádně celý program bude vysvětlen ve videu a v něm i představení jak to funguje ve hře. Samozřejmě projekt může fungovat v jakékoliv hře s nastevním keybindings.



# FOTKY PROJEKTU

### Projekt jako celek:

![dashboardgif](https://github.com/user-attachments/assets/28985b96-4bd9-43a5-b7e7-1019fcb09cff)

## Zapojení projektu

### Schéma zapojení:

![image](https://github.com/user-attachments/assets/2c65e6ab-b055-41fc-aa3a-bae970531edd)

### Zapojení uvnitř:

![image](https://github.com/user-attachments/assets/86264d0c-7c8f-4a7e-8736-069acabeef8c)

## Pinout Raspberry Pi Pico - (pro lepší orientaci)

![obrazek](https://github.com/user-attachments/assets/99b29c87-3fe5-45be-bf2c-7c511e57c76b)

## Úprava - indikátor LED

Napadlo mě, že bych si mohl udělat ještě indikátor přes led diodu, abych věděl, že dashboard funguje tak jak má. Led-ka se rozsvítí ihned po zapojení do sítě. Pro lepší udržitelnost a životnost led-ky jsem zařadil rezistor o hodnotě 500Ohmů do série. Led-ka svítí tak jak má a svítivost není přehnaná.

### Schéma zapojení led:

![image](https://github.com/user-attachments/assets/7bc3c716-b3a2-4357-91c1-003306192788)

### Fotka v realitě:

![image](https://github.com/user-attachments/assets/7e66fe57-0c94-46e7-b862-d3eee0790c95)






## ZDROJE A LITERATURA

[1] HUI, Don. Raspberry Pi Pico - DIY Macro Keyboard. Online. 2021. Dostupné z: https://www.youtube.com/watch?v=aEWptdD32iA&t=596s. [cit. 2024-12-19].

[2] PEENS, Vernon. DIY Macro Keyboard - Raspberry Pi Pico (Affordable & Awesome!). Online. 2023. Dostupné z: https://www.youtube.com/watch?v=7hYTQY_3xUc&t=115s. [cit. 2024-12-19].

[3] Circuit Python - URL. Online. Dostupné z: https://circuitpython.org/. [cit. 2024-12-19].

[4] FoamyGuy. Adafruit HID - Libraries. Online. Dostupné z: https://github.com/adafruit/Adafruit_CircuitPython_HID/releases. [cit. 2024-12-19].


## YOUTUBE VIDEO - VYSVĚTLENÍ A PŘEDSTAVENÍ

[5] DUBEN, Vojtěch. Video DASHBOARD ETS2 ProjektMPS. Online. 2024. Dostupné z: https://www.youtube.com/watch?v=e2bOCh1KB-Q. [cit. 2024-12-19].


## PODĚKOVÁNÍ

Chtěl bych zde poděkovat Petrovi Horníkovi za 3D vytisknutí držáku ke stolu. Moc mi to pomohlo. DĚKUJI.

![image](https://github.com/user-attachments/assets/cd3289b0-3272-491b-a8b9-fc6acfdd8e8b)



