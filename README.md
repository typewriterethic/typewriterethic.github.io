# Jekyll-blogg

Et rent, tidløst blogg-tema basert på bokdesign-estetikk.

## Kom i gang

### Forutsetninger

- Ruby (2.7 eller nyere)
- Bundler (`gem install bundler`)

### Installer og kjør lokalt

```bash
bundle install
bundle exec jekyll serve
```

Åpne `http://localhost:4000` i nettleseren.

## Tilpass bloggen

### 1. Rediger `_config.yml`

Endre disse feltene:

```yaml
title: "Navnet på bloggen din"
description: "En kort beskrivelse"
author: "Ditt navn"
email: "din@epost.no"
url: "https://dittbrukernavn.github.io"
```

### 2. Skriv poster

Opprett filer i `_posts/` med formatet `ÅÅÅÅ-MM-DD-tittel.md`:

```markdown
---
layout: post
title: "Tittelen på posten"
date: 2025-03-01
excerpt: "Én setning som vises på forsiden."
og_image: "/assets/og/default.png"
---

Teksten din her.
```

### 3. OG-bilder for sosiale medier

Legg bilder i `assets/og/`. Anbefalte mål: **1200 × 630 px**.

Bruk `og_image` i front matter for å velge bilde per post:

```yaml
og_image: "/assets/og/bilde-02.png"
```

Inkluderte plassholdere: `default.png`, `bilde-02.png`, ... `bilde-06.png`

### 4. Rediger om-siden

Åpne `om.md` og skriv om deg selv.

## Deploy til GitHub Pages

1. Opprett et repository på GitHub: `dittbrukernavn.github.io`
2. Push alle filene dit
3. Gå til Settings → Pages → Source: `main` branch

Bloggen er tilgjengelig på `https://dittbrukernavn.github.io`.

## Embedding

Kopier kode-snippets fra eksempelposten for YouTube, Spotify, Soundcloud og Typeform.

## Typografi og farger

Temaet bruker **Lora** (Google Fonts) gjennomgående – en serif font laget for skjermer med røtter i bokdesign.

For å endre farger, rediger variablene øverst i `assets/css/main.scss`.
