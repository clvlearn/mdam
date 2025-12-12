# Meneer van Dam

Nederlands info (Meneer van dam)

## Website

Deze repository bevat de broncode voor de website van Meneer van Dam, gebouwd met MkDocs.

Bezoek de live website op: [https://clvlearn.github.io/mdam/](https://clvlearn.github.io/mdam/)

## Lokale Ontwikkeling

### Vereisten

- Python 3.x
- pip

### Installatie

1. Clone deze repository:
```bash
git clone https://github.com/clvlearn/mdam.git
cd mdam
```

2. Installeer de vereiste packages:
```bash
pip install -r requirements.txt
```

### Lokale Server

Start een lokale ontwikkelserver:
```bash
mkdocs serve
```

De website is nu beschikbaar op `http://127.0.0.1:8000`

### Build

Bouw de statische website:
```bash
mkdocs build
```

De output wordt gegenereerd in de `site/` directory.

## Deployment

De website wordt automatisch gedeployed naar GitHub Pages wanneer er wijzigingen worden gepushed naar de `main` branch. De GitHub Actions workflow bouwt en publiceert de site naar de `gh-pages` branch.

## Structuur

- `mkdocs.yml` - MkDocs configuratie
- `docs/` - Markdown bronbestanden voor de website
- `.github/workflows/` - GitHub Actions workflow voor automatische deployment
- `site/` - Gebouwde website (niet in versiebeheer)

## Bijdragen

Bijdragen zijn welkom! Maak een fork van de repository en dien een pull request in met je wijzigingen.
