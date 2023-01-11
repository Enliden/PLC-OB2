# PLC-OB2
I det følgende skal udarbejdes et PLC-program, der kan varetage regulering og styring af processen som beskrevet i opgaven. Desuden skal vi skrive en rapport, hvor hver regulering omtales og beskrives, gerne i denne rækkefølge:

 - **Kravspecifikation og test** : En liste over de tekniske test vi har og ikke har gennemført for reguleringen
 - **Kodedesign** : En kort gennemgang af programmets struktur evt. V-modellen
 - **Kodeudfærdigelse** : Her beskrives, hvilke programmeringssprog, der er udnyttet. Omtal også valg af indregulering og process-parametre (dødtid, tidskonstant, indreguleringstid osv)


## Todo-liste
Listen viser de identificerede delopgaver til besvarelsen af opgaven. Det muliggør en agil udviklingsproces.

I det følgende menes der med:
Analyse = Statisk og dynamisk analyse udført
Udvikling = Design, Implementation og Test
Rapportafsnit = Skrevet og korrekturlæst af mindst   

- [x] Overordnede Kundekrav og kundetests
- [x] Identifikation og opsætning af Rapportstruktur
- [x] Analyse af proces: elektrodekammer-process
- [x] Analyse af proces: fødevandskammer
- [x] Analyse af proces: damp til opsamling
- [x] Analyse af proces: kondenstank
- [ ] Udvikling af regulator til elektrodekammer
- [ ] Udvikling af kaskade-regulering til elektrodekammer
- [x] Udvikling af Regulator til fødevandskammer
- [x] Udvikling af Regulator til opsamlingstank
- [x] Udvikling af Regulator til kondenstank
- [x] Udvikling af Styring: Kedlens vandkvalitet
- [ ] Udvikling af Styring: Start/Stop/Nødstop
- [ ] Udvikling af Styring: Alarmer
- [x] Sammensætning af Simulatorer og regulatorer
- [x] Udvikling af Styring: HMI
- [x] Rapportafsnit: Indledning
- [x] Rapportafsnit: Metode
- [x] Rapportafsnit: Genstandsfelt (Teori)
	- [x] Kaskaderegulering
	- [x] 1. ordens og 2. ordenssystemer
- [x] Rapportafsnit: Genstandsfelt (Statiske og Dynamiske Analyse)
	- [x] Skrevet
	- [x] Korrekturlæst
- [x] Rapportafsnit: Genstandsfelt (Regulatorer og indregulering)
	- [ ] Regulator til elektrodekammer
	- [x] Regulator til fødevandskammer
	- [x] Regulator til opsamlingstank
	- [x] Regulator til kondenstank
- [x] Rapportafsnit: Genstandsfelt (Tests)
- [x] Rapportafsnit: Genstandsfelt (Opfyldelse af kundekrav)
- [x] Rapportafsnit: Diskussion
- [x] Rapportafsnit: Konklusion
- [x] Rapportafsnit: Abstract


## Fordeling af Udviklingsopgaver
Vi har i de følgende forsøgt at udspecificere udviklingsopgavernes trin jf. V-modellen og fordele dem.


**Malthe**
- [ ] Udvikling af Regulering: Dampproduktion (Elektrodekammer)
	- [ ] Kravspecifikation og testark
	- [x] Kodedesign
	- [ ] Kodeudfærdigelse
	- [ ] Test af kode
	- [ ] Dokumentation (kodekommentar og rapportpunkter)
	- [x] Statisk/Dynamisk Analyse
- [ ] Udvikling af Styring: Kedlens vandkvalitet
	- [ ] Kravspecifikation og testark
	- [ ] Kodedesign
	- [ ] Kodeudfærdigelse
	- [ ] Test af kode
	- [ ] Dokumentation (kodekommentar og rapportpunkter)


**Marius**
- [x] Udvikling af Regulering: Fødevandskammer
	- [x] Kravspecifikation og Testark
	- [x] Kodedesign
	- [x] Kodeudfærdigelse
	- [x] Test af kode
	- [x] Statisk/Dynamisk Analyse
	- [x] Dokumentation (kodekommentar og rapportpunkter)
- [ ] Udvikling af styring: Start/Stop/Nødstop
	- [ ] Testkrav (testark)
	- [ ] Design
	- [ ] Programmering
	- [ ] Test af kode
	- [ ] Dokumentation (kodekommentar og rapportpunkter)
- [x] Udarbejd ark til kundekrav; Udf. Marius og Magnus

**Magnus**
- [x] Udvikling af Regulering: Damp til opsamlingstank	
	- [x] Kravspecifikation og Testark
	- [x] Kodedesign
	- [x] Kodeudfærdigelse
	- [x] Test af kode
	- [x] Dokumentation (kodekommentar og rapportpunkter)
- [ ] Udvikling af Styring: Alarmer
	- [ ] Krav
	- [ ] Design
	- [ ] Kode
	- [ ] Test af kode
	- [ ] Dokumentation (kodekommentar og rapportpunkter)

**Bo**
- [x] Udvikling af Regulering: Kondenstank	
	- [x] Kravspecificering og testark
	- [x] Kodedesign
	- [x] Programmering
	- [x] Test af kode
	- [x] Statisk/Dynamisk Analyse
	- [x] Dokumentation (kodekommentar og rapportpunkter)
- [x] Udvikling af HMI-Projekt
	- [x] Kravspecifikation
	- [x] Design
	- [x] Programmering og opsætning
	- [x] Test af kode
	- [x] Dokumentation (kodekommentar og rapportpunkter)
