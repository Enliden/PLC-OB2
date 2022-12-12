# PLC-OB2
I det følgende skal udarbejdes et PLC-program, der kan varetage regulering og styring af processen som beskrevet i opgaven. Desuden skal vi skrive en rapport, hvor hver regulering omtales og beskrives, gerne i denne rækkefølge:

 - **Kravspecifikation og test** : En liste over de tekniske test vi har og ikke har gennemført for reguleringen
 - **Kodedesign** : En kort gennemgang af programmets struktur evt. V-modellen
 - **Kodeudfærdigelse** : Her beskrives, hvilke programmeringssprog, der er udnyttet. Omtal også valg af indregulering og process-parametre (dødtid, tidskonstant, indreguleringstid osv)
 

## Opgavefordeling
Her følger den umiddelbare opgavefordeling.
Analyse = Statisk og dynamisk analyse
Udvikling = Design, Implementation og Test

- [x] Overordnede Kundekrav og kundetests
- [x] Analyse af proces: elektrodekammer-process
- [x] Analyse af proces: fødevandskammer
- [ ] Analyse af proces: damp til opsamling
- [ ] Analyse af proces: kondenstank
- [ ] Udvikling af regulator til elektrodekammer
- [ ] Udvikling af Regulator til fødevandskammer
- [ ] Udvikling af Regulator til opsamlingstank
- [ ] Udvikling af Regulator til kondenstank
- [ ] Udvikling af Styring: Kedlens vandkvalitet
- [ ] Udvikling af Styring: Start/Stop/Nødstop
- [ ] Udvikling af Styring: Alarmer
- [ ] Udvikling af Styring: HMI

**Malthe**
- [ ] Regulering - Dampproduktion (Elektrodekammer)
	- [ ] Kravspecifikation og testark
	- [x] Kodedesign
	- [x] Kodeudfærdigelse
	- [ ] Test af kode
	- [ ] Dokumentation (kodekommentar og rapportpunkter)
	- [x] Statisk/Dynamisk Analyse
- [ ] Styring af kedlens vandkvalitet
	- [ ] Kravspecifikation og testark
	- [ ] Kodedesign
	- [ ] Kodeudfærdigelse
	- [ ] Test af kode
	- [ ] Dokumentation (kodekommentar og rapportpunkter)


**Marius**
- [ ] Regulering - Fødevandskammer
	- [x] Kravspecifikation og Testark
	- [ ] Kodedesign
	- [ ] Kodeudfærdigelse
	- [ ] Test af kode
	- [x] Statisk/Dynamisk Analyse
	- [ ] Dokumentation (kodekommentar og rapportpunkter)
- [ ] Start/Stop/Nødstop (Marius)
	- [ ] Testkrav (testark)
	- [ ] Design
	- [ ] Programmering
	- [ ] Test af kode
	- [ ] Dokumentation (kodekommentar og rapportpunkter)
- [x] Udarbejd ark til kundekrav; Udf. Marius og Magnus

**Magnus**
- [ ] Regulering - Damp til opsamlingstank	
	- [x] Kravspecifikation og Testark
	- [x] Kodedesign
	- [x] Kodeudfærdigelse
	- [ ] Test af kode
	- [ ] Dokumentation (kodekommentar og rapportpunkter)
- [ ] Alarmer
	- [ ] Krav
	- [ ] Design
	- [ ] Kode
	- [ ] Test af kode
	- [ ] Dokumentation (kodekommentar og rapportpunkter)

**Bo**
- [ ] Regulering - Kondenstank	
	- [ ] Kravspecificering og testark
	- [ ] Kodedesign
	- [ ] Programmering
	- [ ] Test af kode
	- [x] Statisk/Dynamisk Analyse
	- [ ] Dokumentation (kodekommentar og rapportpunkter)
- [ ] HMI-Projekt
	- [ ] Kravspecifikation
	- [ ] Design
	- [ ] Programmering og opsætning
	- [ ] Test af kode
	- [ ] Dokumentation (kodekommentar og rapportpunkter)

# V-modellen
Ovenstående to-do liste er udarbejdet efter trin 2-4 i V-modellen. V-modellen består af 5 trin.

1. Identifikation af kundekrav: Del og hersk, dvs. opgaven opdeles i de delprogrammer og -opgaver, som skal løses.
2. Identifikation af tekniske krav og design af kode med henblik på at leve op til de krav.
3. Implementering af programkode'
4. Test af programkode ifht. tekniske krav
5. Samling af alt kode, hele programmet og test ifht. kundekrav.
