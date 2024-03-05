# Finn arealplaner - dokumentasjon

**Meldinger**: 
- `no.ks.fiks.plan.v2.innsyn.arealplaner.finn`
- `no.ks.fiks.plan.v2.innsyn.arealplaner.finn.for.adresse`
- `no.ks.fiks.plan.v2.innsyn.arealplaner.finn.for.flate`
- `no.ks.fiks.plan.v2.innsyn.arealplaner.finn.for.matrikkelenhet`
- `no.ks.fiks.plan.v2.innsyn.arealplaner.finn.resultat`

**Feilmeldinger**:
- `no.ks.fiks.plan.v2.feilmeldinger.ugyldigforespoersel`
- `no.ks.fiks.plan.v2.feilmeldinger.serverfeil` 

### Sekvensdiagram

#### Finne planer med resultat tilbake til fagsystem

![sekvensdiagram](sekvensdiagram-meldingsutveksling.png)

#### Ugyldig forespørsel: Finne planer med ugyldig forespørsel feilmelding tilbake til fagsystem

Feilmeldingen ugyldig forespørsel sendes tilbake hvis noe var galt med forespørselen. 
F.eks. ugyldig json i henhold til skjema, eller noe annet ugyldig innhold.

Feilmeldingen skal inneholde en melding tilbake til avsender som forklarer hva som var galt.

![sekvensdiagram](sekvensdiagram-ugyldigforespoersel.png)

#### Serverfeil: Finne planer med serverfeil feilmelding tilbake til fagsystem

Feilmeldingen serverfeil sendes tilbake hvis noe gikk galt hos mottaker og man klarer å kontrollert sende denne feilmeldingen tilbake.

Feilmeldingen bør inneholde en melding tilbake til avsender som forklarer hva som var galt.


![sekvensdiagram](sekvensdiagram-serverfeil.png)

### Klassediagram

[no.ks.fiks.plan.v2.innsyn.arealplaner.finn](./../../../ClassDiagrams/no.ks.fiks.plan.v2.innsyn.arealplaner.finn/README.md)

[no.ks.fiks.plan.v2.innsyn.arealplaner.finn.for.adresse](./../../../ClassDiagrams/no.ks.fiks.plan.v2.innsyn.arealplaner.finn.for.adresse/README.md)

[no.ks.fiks.plan.v2.innsyn.arealplaner.finn.for.flate](./../../../ClassDiagrams/no.ks.fiks.plan.v2.innsyn.arealplaner.finn.for.flate/README.md)

[no.ks.fiks.plan.v2.innsyn.arealplaner.finn.for.matrikkelenhet](./../../../ClassDiagrams/no.ks.fiks.plan.v2.innsyn.arealplaner.finn.for.matrikkelenhet/README.md)

[no.ks.fiks.plan.v2.innsyn.arealplaner.resultat](./../../../ClassDiagrams/no.ks.fiks.plan.v2.innsyn.arealplaner.finn.resultat/README.md)
