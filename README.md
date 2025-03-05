# Speciaal onderwijs

Kleine repository om data en code te delen over de ontwikkelingen in het speciaal onderwijs in Nederlandse gemeenten. Het doel van de code is om een betrouwbaar beeld van de trends over tijd te geven, waarbij rekening wordt gehouden met gemeentelijke herindelingen.

Alle data zijn afkomstig van het CBS:

- [[De gebiedsindelingen]](https://www.cbs.nl/nl-nl/dossier/nederland-regionaal/geografische-data/cbs-gebiedsindelingen)
- [[De onderwijsgegeven]](https://opendata.cbs.nl/statline/#/CBS/nl/dataset/85701NED/table?dl=A6B65)

De data hebben een aantal beperkingen.

Ten eerste: de gemeenten van 2025 zijn niet de gemeenten van 2013, het moment vanaf we zijn gaan rekenen. Er zijn herindelingen geweest waarin gemeenten zijn samengevoegd, of zijn opgesplitst. In [[notebooks/gemeenten.ipynb]] staat de code waarmee we die herindelingen hebben verwerkt. Bij de opsplitsingen zijn we ervan uitgegaan dat het aantal leerlingen evenredig over het aantal gemeenten is verspreid waarin de gemeente is opgegaan.

Ten tweede: het CBS verstrekt ni de exacte statistieken, maar getallen afgerond op tientallen. Bij grote gemeenten maakt dat vrijwel niets uit, maar bij kleine gemeenten kan er een kleine verstoring zijn, omdat er soms maar twintig of dertig leerlingen in het speciaal onderwijs zitten. We hebben de trends vergeleken met data over de samenwerkingsverbanden en geconstateerd dat de trends nog steeds hetzelfde zijn.

Ten derde: het is noodzakelijk om te weten dat het speciaal onderwijs in verschillende wetten is geregeld. Lees daarom eerst goed de documentatie bij de tabel van het CBS voordat je zelf met de data aan de slag gaat.
