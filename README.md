# geoprism-registry-localization
A repository for sharing opensource GeoPrism Registry language translations.

## Contributing

### Folder Convention
Folders must be named with the following convention:

* [ISO 639-1 language code](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) followed by an underscore followed by the [ISO 3166 country code](https://en.wikipedia.org/wiki/List_of_ISO_3166_country_codes).

The USA english example is *en_US*.

### File Schema Convention
Localization files must follow the standards of the localization files exported from a GeoPrism Registry instance. **When creating a new localization file it is highly recommended to start by exporting a localization file from the GeoPrism Registry instance the effort is intended for.**

See the [GeoPrism Registry documentation](https://docs.geoprismregistry.com/readme/current/deployment-and-setup/3.4-localisation) for more details.

### File Naming Convention
Localization files must be named with the following convention:
* "localization-" followed by the language and country identifiers (same as containing folder) followed by "GPRv" and the GeoPrism Registry version the file is targeting followed by any additional necessary identifiers (optional).

The USA english example is *localization-en_US-GPRv1.0.0.xlsx*.
