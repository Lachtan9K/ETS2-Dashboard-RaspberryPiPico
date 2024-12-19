# ETS2-Dashboard-RaspberryPiPico

## INFORMACE

### Projekt do školy SPŠ-ELIT Dobruška na předmět MPS 

Autor: Vojtěch Duben

Třída: T3A

Školní rok: 2024/2025

# O co se jedná ?

Udělal jsem si dashboard pro hry/simulátory, kterým se dají ovládat určité prvky např. řežim osvětlení vozů atd. Na dashboardu je 10 tlačítek a 1 vypínač na klíček, který slouží k nastartování vozu.


# CÍL

Mým cílem bylo si vytvořit něco, co bych využíval a nebylo to zbytečné. Mým cílem též bylo se naučit novým věcem co se týče programování a troubleshootingu. 


# ZÁVĚR  

Celý tento program je dělaný v CircuitPythonu. Bylo potřeba kompletně reinstalovat (stačilo nukenout) Raspberry Pi Pico na Circuit. Instalace jsem provedl prostřednictvím aplikace Thonny.
Přidávám zde i samotný dokončený program, prototyp programu, youtube odkaz k vysvětlení, návrh krabičky a knihovny které byly potřeba dát externě do Pica. Mužete je najít v druhém branchy.

Poprvé jsem neměl vůbec páru jak programovat v CircuitPythonu, avšak je to velice podobné MicroPythonu až na maličkosti( Je to více rozšířenější ). Čerpal jsem jak z videí programování v CircuitPythonu, ale také i z videí přesně zamřený na můj projekt a i ze zdroje ChatGPT k doladění programu k dokonalosti. Z mého výtvoru by se mohla také udělat i macro klávesnice, ale já jsem se rozhodl si udělat dashboard pro Euro Truck Simulator 2, jelikož si ho někdy zahraju a bude super mít nový přístroj pro můj simulátor. Nějaké velké problémy při projektu nebyly, avšak jsem měl problém si detekováním vstupu tlačítka. Zjistil jsem, že stačilo jen pozměnit tvar programu a vše už probíhalo v pořádku. Na projektu je 11 tlačítek, takže je jasné, že program bude celkem dlouhý, tyto tlačítka jsem nakopírovával do doby než jich tam bylo 11 a vše pokračovalo v pořádku. Program jsem poupravil tak, když podržím jakékoliv tlačítko, tak se dále bude vypisovat nějaká daná funkce. Ale u jediného tlačítko to tam není, vlastně to není ani tlačítko, ale je to vypínáč na klíček a ten bylo potřeba, aby se furt a stále nespouštěl. Projekt funguje skvěle a jsem rád, že jsem si ho opravdu udělal ( K tomu hrání to dodává ten "šmak" :) ). Každopádně celý program bude vysvětlen ve videu a v něm i představení jak to funguje ve hře. Samozřejmě projekt může fungovat v jakékoliv hře s nastevním keybindings.



# FOTKY PROJEKTU

### Projekt jako celek

![image](https://github.com/user-attachments/assets/eb41b2ec-d559-47f7-aa27-f7b4efc86015)

### Dashboard

![image](https://github.com/user-attachments/assets/668b3c6e-af29-40a3-85b8-1087e1b4d4a4)

### Držák

![image](https://github.com/user-attachments/assets/c51e9e60-e60e-414d-b1b5-0dc01085a4db)

### Schéma zapojení 

![image](https://github.com/user-attachments/assets/2c65e6ab-b055-41fc-aa3a-bae970531edd)

### Zapojení uvnitř

![image](https://github.com/user-attachments/assets/86264d0c-7c8f-4a7e-8736-069acabeef8c)


## ZDROJE A LITERATURA

HUI, Don. Raspberry Pi Pico - DIY Macro Keyboard. Online. 2021. Dostupné z: https://www.youtube.com/watch?v=aEWptdD32iA&t=596s. [cit. 2024-12-19].


## PODĚKOVÁNÍ

Chtěl bych zde poděkovat Petrovi Horníkovi za 3D vytisknutí držáku ke stolu. Moc mi to pomohlo. DĚKUJI.


