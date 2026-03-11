# Dokumentation i md-format

Dette er en mark-down fil.

Markdown-filer bruges ofte af webudviklere til at skrive letlæselige tekster. Det gør det let at lave pænt formatteret dokumentation, blogindlæg og README-filer, uden at skulle skrive html og css. Markdown har en standard-formattering, som du kan se hved at højreklikke på filen i fil-oversigten og vælge 'Open preview'.

Når du bare skriver tekst i afsnit uden særlig formattering vises teksten som almindelige tekstafsnit.

Bemærk hvordan den første linje begynder med #. Det er sådan man laver overskrifter i markdown-filer. Du kan lave Hieraki i din fil ved at tilføje overskrifter med flere # - helt op til seks stk. (h1 - h6).

## Fremhævninger og punktopstillinger

Du kan fremhæve tekst med **bold** eller *italics*.

Du kan bruge bindestreger til at lave en punktopstilling med: 
- her er en pointe at huske.
- her er en anden pointe.

## Kode-eksempler
Sidst men ikke mindst kan du indsætte kode eksempler i både html og css ved at bruge tre såkaldte 'back-ticks':

```html
     <nav>
      <ul>
        <li><a href="">Dame</a></li>
        <li><a href="">Herre</a></li>
        <li><a href="">Børn</a></li>
      </ul>
    </nav>
```

du kan også indsætte css eksempler med back-ticks: 

```css
     nav ul {
        display: flex;
        align-items: center;
        gap: 1rem;
     }
```

Som beskrevet ovenfor, kan du åbne filen i en formatteret udgave i vs-code ved at højreklikke på filen i fil-oversigten og vælge 'Open preview'