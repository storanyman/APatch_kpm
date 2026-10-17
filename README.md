# APatch KPM

```text
       /\_/\
      ( •̀ ω •́ )   Traditionell programmering är ganska tråkigt, eller hur?
       / >⌨️

     ✨ Projektet är destillerat ✨
     Vill du ha något, skriv det själv.
```

## **Projektets Önskebrunn**

Förr var det "vill du ha något, skriv det själv", och nu är det "vill du ha något, skriv det själv". Du ansvarar för att ställa kraven, AI:n ansvarar för att skriva koden, och testmaskinen ansvarar för att se om den bara skryter.

[`zram_zstd`](zram_zstd/README.md) har redan gått igenom den här processen: AI-utveckling, oberoende granskning, testning på riktig enhet, och slutligen godkännande och signering av underhållaren. En ansvarar för att skriva, en för att hitta fel och en annan för godkännande på enheten.

## Skapa en önskan

Berätta för AI:n om din enhetsmodell, Android-/kärnversion, APatch-/KernelPatch-version och den funktion du vill implementera, och förklara vad som krävs för att det ska anses vara klart. Låt den sedan börja arbeta enligt [projektreglerna](AGENTS.md).

Ju mer specifik önskan är, desto snabbare förverkligas den. När det gäller "hjälp mig att skriva en universell modul", föreslår jag att du först frågar den magiska lampan om den har någon kontextkvot kvar.

## Användning

Detta är ett arkiv för APatch-/KernelPatch-moduler för personligt bruk. För modulanvändning, se README i respektive katalog. För färdiga versioner, se [Releases](https://github.com/lzghzr/APatch_kpm/releases). Kompatibilitetsomfånget baseras på motsvarande instruktioner och verifieringsposter.

Om du stöter på en bugg, vänligen tillhandahåll boot.img och APatch-loggar; innan du publicerar dem, se till att ta bort enhetens serienummer, nycklar och lokala sökvägar.

Välkommen att komma med dina behov för att önska, och du är också välkommen att komma med reproduktionsloggar för att kritisera. För den detaljerade processen, se [Process för tredjepartsleverans](docs/README.md).

### Alla moduler är för personligt bruk och har inte anpassats för alla enheter. Jag ansvarar inte för några förluster orsakade av användningen av modulerna.
