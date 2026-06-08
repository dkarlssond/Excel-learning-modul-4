Excel Modul 4 – Power Query
Fjärde caset i min Excel-träning inför en roll som business controller. Det här handlar om Power Query – att städa och förvandla rörig data, med steg som körs om automatiskt.
Underlaget är en rörig systemexport av leverantörsfakturor från ett påhittat tillverkningsbolag, Nordvik Industri. 100 rader precis som de ofta ser ut i verkligheten: mellanslag som skräpar i texten, datum och belopp lagrade som text, och tio dubblettrader. Uppgiften var att städa den till en tabell som går att analysera.
Vad jag gjorde

Läste in den röriga exporten i Power Query
Trimmade bort onödiga mellanslag i textkolumnerna
Gjorde om Datum från text till riktiga datum
Rensade beloppen ("12 450 kr") från text till tal som går att summera
Tog bort tio dubblettrader
Laddade tillbaka den städade datan till Excel
Slog ihop resultatet med ett leverantörsregister för att hämta in land och leverantörstyp (Power Querys variant av XLOOKUP)

Vad jag tog med mig
Hur Power Query spelar in varje steg, så att en hel städprocess kan köras om automatiskt när ny data kommer in. Skillnaden mot att städa för hand i Excel är stor – man gör jobbet en gång och återanvänder det. Och hur en merge kopplar ihop två tabeller på samma sätt som ett uppslag, fast inbyggt i flödet.
Fil
Övningscase_4_Excel.xlsx – fliken Råexport innehåller den röriga originaldatan, och den städade tabellen plus merge-resultatet ligger på egna flikar.
Byggd i Excel 365
