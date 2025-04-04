# Language Standard Code Proposal
Language Code standard draft that illustrates hierarchies and similarities.

# Advantage
- Made for Humans and Machine.
  - Read multiples code and relate between them.
- Flexible - This way achieves what ISO does and is more human friendly and can contain as-mush or as-less infomation you need.

# Problem
- IETF and ISO 3166-1 alpha-2 has a codes like en-US American_English
- ISO 639-2 includes not only individual language codes but also broader language group codes that represent families or groups of related languages. These group codes are used to categorize languages that share a common origin, linguistic features, or historical relationship. For example, consider the Afro-Asiatic language family, which includes languages such as Arabic, Hebrew, Amharic, and Hausa, among others.
- ISO 639-2 assigns the language group code "afa" to represent the Afro-Asiatic language family as a whole. Each individual language within this family has its own unique three-letter code, such as "ara" for Arabic, "heb" for Hebrew, "amh" for Amharic, and "hau" for Hausa.
- ISO 639-3 - Only has 3 letter for each "dialect".
- Current stadard don't have codes for “French- Parisian” or “French-Quebecois” and some people use and it's not very standard languge and not programming friendly.

# Standard Specs

## 4 Level                                    (Lanaguge - Dialect - Sub Dialect - Sub Dialect v2)
- En-GB-Ln-S (South London English) -            English: En Dialect: En-GB (British English) Sub-Dialect: En-GB-Ln (London English) Another Sub-Dialect: S
- En-US-Tx-Ho (Houston Texas English)
- En-GB-Sc-Ed (Edinburgh Scottish English)
- En-CA-Qc-Mt (Montreal Quebec English)
- Es-ES-Ca-Md (Madrid Castilian Spanish) -            Spanish - European Spanish- Sub-Dialect: Es-ES-Ca (Castilian Spanish) - Sub-Dialect 2 : Md
  
- Hi-IN-UP-Al (Allahabad Uttar Pradesh Hindi) -            Hindi: Hi Dialect: Hi-IN (Indian Hindi) Sub-Dialect: Hi-IN-UP (Uttar Pradesh Hindi) Another Sub-Dialect: Al
  
- Zh-CN-Sh-Js (Jiangsu Shanghai Dialect) -            Chinese Zh Dialect: Zh-CN (Simplified Chinese) Sub-Dialect: Zh-CN-Sh (Shanghai Dialect) Another Sub-Dialect:  Js
  
- Ar-MA-Rb-Mq (Meknes Rabat Moroccan Arabic) -            Moroccan Arabic - Rabat Moroccan Arabic

## 3 Level

Wiki - https://en.wikipedia.org/wiki/List_of_dialects_of_English

En-GB-Sc (Scottish English)
- English: En Dialect: En-GB (British English) Sub-Dialect: Sc

### Ar-Mb-Al
Algerian Arabic is Arabic - Maghrebi Arabic - Algerian Arabic. ISO 639-3	`arq`

 - "Ar" represents Arabic, the main language family or group.
 - "Mb" represents Maghrebi Arabic, the broader dialect group that includes Algerian Arabic.
 - "Al" represents Algerian Arabic, the specific sub-dialect within the Maghrebi Arabic group.

# Creole are listed after Dialects

#### Example

- https://en.wikipedia.org/wiki/Bajan_Creole
- https://en.wikipedia.org/wiki/Jamaican_Patois

# City Dialects

Cities with similar Dialects are griuped together with `/`

#### Example

1. *3 Level* - En-IN-Dl/Mm (Mumbai/Delhi English)
2. *2 Level* - En-AU/Ns/Sy (Sydney New South Wales English)

# Accent

Wiki - https://en.wikipedia.org/wiki/Regional_accents_of_English

#### Example - For English US

`En-US-[US]`

# Langua Franka

Always Group Langue frank together

Explaination - https://en.wikipedia.org/wiki/Lingua_franca TLDR 2 different Languages but mutually intelligible

[Hindustani](https://en.wikipedia.org/wiki/Hindustani_language) [Hindi](https://en.wikipedia.org/wiki/Hindi) [Urdu](https://en.wikipedia.org/wiki/Urdu)

# Languge Groups

#### Example

1. English - Indo-European - Germanic - West Germanic - North Sea Germanic - Anglic - English


## Internationalisaition 

Languges are own differently in other languages, prefer Native Language name.

#### Example

Persian - Farsi

## Scrit

1st Standardize in [Latin](https://en.wikipedia.org/wiki/Latin_script) Script than can add localization for other languages



### Who codes for city level dialects

it suits both use cases and info is there is you want it

## Also See

- https://www.iso.org/iso-639-language-code
- https://www.loc.gov/standards/iso639-2/
- https://iso639-3.sil.org/

- https://www.ietf.org/

- https://en.wikipedia.org/wiki/List_of_countries_and_territories_where_English_is_an_official_language
