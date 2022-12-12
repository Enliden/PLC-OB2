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
- [ ] Udvikling af Regulator til fødevandskammer
- [ ] Udvikling af Regulator til opsamlingstank
- [ ] Udvikling af Regulator til kondenstank
- [ ] Udvikling af Styring: Kedlens vandkvalitet
- [ ] Udvikling af Styring: Start/Stop/Nødstop
- [ ] Udvikling af Styring: Alarmer
- [ ] Sammensætning af Simulatorer og regulatorer
- [ ] Udvikling af Styring: HMI
- [ ] Rapportafsnit: Indledning
- [ ] Rapportafsnit: Metode
- [ ] Rapportafsnit: Genstandsfelt (Teori)
	- [ ] Kaskaderegulering
	- [ ] 1. ordens og 2. ordenssystemer
- [ ] Rapportafsnit: Genstandsfelt (Statiske og Dynamiske Analyse)
	- [x] Skrevet
	- [ ] Korrekturlæst
- [ ] Rapportafsnit: Genstandsfelt (Regulatorer og indregulering)
	- [ ] Regulator til elektrodekammer
	- [ ] Regulator til fødevandskammer
	- [ ] Regulator til opsamlingstank
	- [ ] Regulator til kondenstank
- [ ] Rapportafsnit: Genstandsfelt (Tests)
- [ ] Rapportafsnit: Genstandsfelt (Opfyldelse af kundekrav)
- [ ] Rapportafsnit: Diskussion
- [ ] Rapportafsnit: Konklusion
- [ ] Rapportafsnit: Abstract


## Fordeling af Udviklingsopgaver
Vi har i de følgende forsøgt at udspecificere udviklingsopgavernes trin jf. V-modellen og fordele dem.
**Malthe**
- [ ] Udvikling af Regulering: Dampproduktion (Elektrodekammer)
	- [ ] Kravspecifikation og testark
	- [x] Kodedesign
	- [x] Kodeudfærdigelse
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
- [ ] Udvikling af Regulering: Fødevandskammer
	- [x] Kravspecifikation og Testark
	- [x] Kodedesign
	- [ ] Kodeudfærdigelse
	- [ ] Test af kode
	- [x] Statisk/Dynamisk Analyse
	- [ ] Dokumentation (kodekommentar og rapportpunkter)
- [ ] Udvikling af styring: Start/Stop/Nødstop
	- [ ] Testkrav (testark)
	- [ ] Design
	- [ ] Programmering
	- [ ] Test af kode
	- [ ] Dokumentation (kodekommentar og rapportpunkter)
- [x] Udarbejd ark til kundekrav; Udf. Marius og Magnus

**Magnus**
- [ ] Udvikling af Regulering: Damp til opsamlingstank	
	- [x] Kravspecifikation og Testark
	- [x] Kodedesign
	- [x] Kodeudfærdigelse
	- [ ] Test af kode
	- [ ] Dokumentation (kodekommentar og rapportpunkter)
- [ ] Udvikling af Styring: Alarmer
	- [ ] Krav
	- [ ] Design
	- [ ] Kode
	- [ ] Test af kode
	- [ ] Dokumentation (kodekommentar og rapportpunkter)

**Bo**
- [ ] Udvikling af Regulering: Kondenstank	
	- [ ] Kravspecificering og testark
	- [ ] Kodedesign
	- [ ] Programmering
	- [ ] Test af kode
	- [x] Statisk/Dynamisk Analyse
	- [ ] Dokumentation (kodekommentar og rapportpunkter)
- [ ] Udvikling af HMI-Projekt
	- [ ] Kravspecifikation
	- [ ] Design
	- [ ] Programmering og opsætning
	- [ ] Test af kode
	- [ ] Dokumentation (kodekommentar og rapportpunkter)
