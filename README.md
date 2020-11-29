# Translations for CodeIgniter 4 System Messages

![build](https://github.com/codeigniter4/translations/workflows/build/badge.svg?branch=develop)
[![Latest Stable Version](https://poser.pugx.org/codeigniter4/translations/v)](//packagist.org/packages/codeigniter4/translations)
[![Total Downloads](https://poser.pugx.org/codeigniter4/translations/downloads)](//packagist.org/packages/codeigniter4/translations)
[![License](https://poser.pugx.org/codeigniter4/translations/license)](//packagist.org/packages/codeigniter4/translations)

This project contains translations for CodeIgniter 4 localization, e.g. **system/Language/en/**.

Copy the folder(s) for the locales you are interested in, from inside the **Language** folder of
this project to your **app/Language/** folder.

You may then use the CodeIgniter Language class to reference the translations
directly. See the [User Guide](https://codeigniter4.github.io/CodeIgniter4/outgoing/localization.html).

Localization in CodeIgniter 4 follows the [ISO 639-1 conventions](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes). Each translation set would go inside a folder named following the two-letter language code from here.

Localization variants are provided for, as folders named with the two-letter ISO 639-1 language code in
lowercase, followed by the two-letter [ISO 3166 country code](https://en.wikipedia.org/wiki/ISO_3166-1)
capitalized, and with the two parts separated by a hyphen.

An example would be "en" for English, and "en-US" for the variations appropriate to the United States.

## Repository Information

Each language is maintained by a community member, per the table below. The role of maintainers is to
provide a single authority for vetting translations for a given language, since the framework team
claims no expertise beyond English.

| Locale   | Language             | As of       | Github User       | Maintainer
| -------- | -------------------- | ----------- | ----------------- | -------------------------
| ar       | Arabic               | 4.0.0       | daif              | Daif Alotaibi
| cs       | Czech                | 4.0.4       | PavelTajdus       | Pavel Tajduš
| de       | German               | 4.0.0       | sba               | Stefan Bauer
| en       | English              | 4.0.0       | n/a               | CI team
| es       | Spanish              | 4.0.0*      | nachoaguirre      | Ignacio Aguirre
| fa       | Farsi                | 4.0.0       | smhnaji           | Mohammad Naji
| fr       | French               | 4.0.0*      | amuratet          | Amuratet?
| id       | Indonesian           | 4.0.0*      | ridho1991         | Mutasim Ridlo
| it       | Italian              | 4.0.0       | luk3b8            | Luca Rasia
| ja       | Japanese             | 4.0.0       | kohenji01         | Shoji Ogura
| ko       | Korean               | 4.0.2       | codeigniter-kr    | codeigniter-kr
| lt       | Lithuanian           | 4.0.0*      | dgvirtual         | Donatas Glodenis
| lv       | Latvian              | 4.0.0*      | davislasis        | Dāvis Lasis
| ml       | Malayalam            | 4.0.0       | rakheshthayyur    | Rakhesh Thayyur
| nl       | Dutch                | 4.0.0       | JohanSmolders     | JohanSmolders
| no       | Norwegian            | 4.0.0       | LA3QMA            | Kai Günter Brandt
| pl       | Polish               | 4.0.0       | DEVELPL           | Maciej Jasiewicz
| pt       | Portuguese           | 4.0.0       | rbm0407           | Rodrigo Borges
| pt-BR    | Brazilian            | 4.0.0       | natanfelles       | Natan Felles
| ru       | Russian              | 4.0.0       | DigitalWolf98     | Vladislav Rykhtikov
| sk       | Slovak               | 4.0.0       | xbotkaj           | Jozef Botka
| sv-SE    | Swedish - Sweden     | 4.0.4       | tangix            | Mattias Sandström
| tr       | Turkish              | 4.0.0       | obozdag           | obozdag
| uk       | Ukrainian            | 4.0.0       | flybot            | Serhii Kosyi
| vi       | Vietnamese           | 4.0.0       | xuandung38        | XuanDung38
| zh-CN    | Simple Chinese       | 4.0.0       | bangbangda        | bangbangda
| zh-TW    | Traditional Chinese  | 4.0.0 *     | monkenWu          | monkenWu

## Requirements

These translations are intended for use with CodeIgniter 4.x applications.

## License

These translations are licensed under the [LICENSE](LICENSE).
