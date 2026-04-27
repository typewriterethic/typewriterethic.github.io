---
layout: post
title: "Dette er en eksempelpost"
date: 2025-01-15
excerpt: "En kort introduksjonssetning som vises på forsiden. Hold den til én setning."
og_image: "/assets/og/default.png"
---

Dette er brødtekst. Lora er en font laget for å leses i lange strekk – på skjerm og på papir. Legg merke til linjeavstanden og tekstbredden. Begge er valgt for å gjøre lesing behagelig, ikke for å fylle plass.

Et nytt avsnitt begynner slik. Ingen innrykk, bare luft mellom avsnittene. Det er den moderne konvensjonen, og den fungerer godt på skjerm.

## En overskrift på nivå to

Overskrifter markerer et skifte i teksten. Bruk dem sparsomt. En god tekst trenger sjelden mer enn to eller tre overskrifter.

Fortsett med vanlig tekst her. Teksten flyter videre under overskriften som vanlig.

### En overskrift på nivå tre

Nivå tre brukes til underavsnitt innen et større avsnitt. Den er kursiv for å skille den fra nivå to, men uten å forstyrre.

> Et sitat settes inn slik. Det skilles ut med en tynn strek til venstre og kursiv skrift. Bruk sitat til å fremheve en idé, ikke til å fylle plass.

Og teksten fortsetter under sitatet som normalt.

## Embedding av eksternt innhold

For å legge inn en YouTube-video, bruk denne strukturen:

```html
<div class="embed-responsive">
  <iframe src="https://www.youtube.com/embed/VIDEO_ID" allowfullscreen></iframe>
</div>
```

For Spotify:

```html
<div class="embed-wrapper">
  <iframe src="https://open.spotify.com/embed/episode/EPISODE_ID" height="152" frameborder="0"></iframe>
</div>
```

For Soundcloud:

```html
<div class="embed-wrapper">
  <iframe height="166" src="https://w.soundcloud.com/player/?url=https://soundcloud.com/BRUKER/SPOR"></iframe>
</div>
```

For Typeform:

```html
<div class="embed-wrapper">
  <iframe src="https://DINBLOGG.typeform.com/to/FORM_ID" height="500"></iframe>
</div>
```

---

En horisontal strek (tre bindestreker i Markdown) lager en diskret skillelinje.
