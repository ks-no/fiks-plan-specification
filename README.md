# Kontrakter og dokumentasjon for Fiks Plan

> Fiks Plan er en modernisering av GI Plan 1.1 og det nye grensesnittet som skal benyttes når kommunen skal sette opp kommunikasjonen med kommunens planregister og mellom et fagsystem og planregister.

I dette github repositoriet finner man json schemas og dokumentasjon for Fiks Plan protokollen.

### Andre steder å finne informasjon om Fiks Plan:

- ### [KS.no - Fiks Plan](https://www.ks.no/fagomrader/digitalisering/felleslosninger/verktoykasse-plan--og-byggesak/verktoy/sammenhengende-tjenester---integrasjoner/fiks-plan/)
- ### [KS Digital - developer dokumentasjon](https://developers.fiks.ks.no/tjenester/fiksprotokoll/plan/)

## [Wiki for Fiks Plan spesifikasjonen](https://github.com/ks-no/fiks-plan-specification/wiki)
Gå til [wiki](https://github.com/ks-no/fiks-plan-specification/wiki) for å lese mer om protokollen.

## Schemas, eksempler og Nuget-pakke
Eksempler, schemas samt genererte models basert på schemas er tilgjengelig for .NET, og dette finner man i Github prosjektet [her](https://github.com/ks-no/fiks-plan-models-dotnet).

## Diagrammer i github repository

For hver versjon av protokollen vil det følge en egen dokumentasjon som baserer seg på Markdown og PlantUML.
Modeller ligger i dette repositoriet mens dokumentasjonen ligger i [wiki](https://github.com/ks-no/fiks-plan-specification/wiki).

Når man gjør endringer i PlantUML koden kan man kjøre `generate-png-from-puml.sh` scriptet for å generere png filer ut av PlantUML koden. Dette forutsetter at man har installert PlantUML og graphviz.

### [Sekvensdiagrammer](Dokumentasjon/V2/SequenceDiagrams/README.md)
Sekvensdiagram for meldingsutveksling (f.eks. for "registrer planbehandling") med lenke til tilhørende klassediagrammer.

### [Klassediagrammer](Dokumentasjon/V2/ClassDiagrams/README.md)
Klassediagrammer for meldingstypene/skjema.

### [Forklaring for overgang GI til Fiks-Plan](Dokumentasjon/V2/GI/Innsyn)



