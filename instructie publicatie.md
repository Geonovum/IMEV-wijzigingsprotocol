# Publiceren van documenten

Wanneer je document klaar is, publiceer je via **GitHub Releases**:

## Pre-release (testomgeving)

* Ga naar het tabblad **Releases** in je eigen repo
* Klik op **“Create a new release”**
* Geef een tag aan bij, Choose a tag (bijv. `v0.1.0`) en klik op **“Create new tag”**
* **Vink aan:** “This is a pre-release” onderop deze pagina
* Klik op **“Publish release”**

💡 Dit publiceert je document automatisch op:
https://test.docs.geostandaarden.nl/

(De exacte URL wordt bepaald door waarden in `config.js`)

### Release (productieomgeving)

* Ga opnieuw naar **Releases**
* Klik op **“Create a new release”**
* Geef een tag aan bij, Choose a tag (bijv. `v0.1.0`) en klik op **“Create new tag”**
* Laat “pre-release” uitgevinkt
* Klik op **“Publish release”**

💡 Dit maakt automatisch een **Pull Request** aan naar:
[`Geonovum/docs.geostandaarden.nl`](https://github.com/Geonovum/docs.geostandaarden.nl/pulls)

Na goedkeuring van de PR wordt het document gepubliceerd op:
https://docs.geostandaarden.nl/