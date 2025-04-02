# klipper_sovol_sv01
Mina anteckningar om att installera klipper och kllipper firmware för Sovol sv01 silent board
printer.cfg är konfigurerad av chatgpt. Kolla noga att allt verkar rimligt innan du flashar firmware.

Att använda sig av chattgpt var en mixad upplevelse. Det mesta blev fel. Chatgpt fick till rätt pinnar till bl-touch
en gång. Det hade gått snabbare att börjat med https://github.com/Klipper3d/klipper/blob/master/config/printer-sovol-sv01-2020.cfg.
Den saknar bl-touch inställningar men det löste chatgpt till min stora förvåning. Det svåra var att hitta rätt pinnar.
Jag tillbringade alldes för lång tid med detta. Klipper klagade på att pinne PD3 användes flera gånger i printer.cfg.
Därför trodde jag att det var fel pinne. Till slut insåg jag att den pinnen så klart användes till microbrytaren som man
tar bort när man installerar bl-toush-sensorn.
