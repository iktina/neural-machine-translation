# Neural Machine Translation
Neural Machine Translation service for SingularityNET

## Welcome
## What’s the point?
The service process input sentences and returns a translation, accordingly to input parameters.
## Model details:
avaliable languages:
- Acehnese (Arabic script)
- Acehnese (Latin script)
- Mesopotamian Arabic
- Ta'izzi-Adeni Arabic
- Tunisian Arabic
- Afrikaans
- South Levantine Arabic
- Akan
- Amharic
- North Levantine Arabic
- Modern Standard Arabic
- Modern Standard Arabic (Romanized)
- Najdi Arabic
- Moroccan Arabic
- Egyptian Arabic
- Assamese
- Asturian
- Awadhi
- Central Aymara
- South Azerbaijani
- North Azerbaijani
- Bashkir
- Bambara
- Balinese
- Belarusian
- Bemba
- Bengali
- Bhojpuri
- Banjar (Arabic script)
- Banjar (Latin script)
- Standard Tibetan
- Bosnian
- Buginese
- Bulgarian
- Catalan
- Cebuano
- Czech
- Chokwe
- Central Kurdish
- Crimean Tatar
- Welsh
- Danish
- German
- Southwestern Dinka
- Dyula
- Dzongkha
- Greek
- English
- Esperanto
- Estonian
- Basque
- Ewe
- Faroese
- Fijian
- Finnish
- Fon
- French
- Friulian
- Nigerian Fulfulde
- Scottish Gaelic
- Irish
- Galician
- Guarani
- Gujarati
- Haitian Creole
- Hausa
- Hebrew
- Hindi
- Chhattisgarhi
- Croatian
- Hungarian
- Armenian
- Igbo
- Ilocano
- Indonesian
- Icelandic
- Italian
- Javanese
- Japanese
- Kabyle
- Jingpho
- Kamba
- Kannada
- Kashmiri (Arabic script)
- Kashmiri (Devanagari script)
- Georgian
- Central Kanuri (Arabic script)
- Central Kanuri (Latin script)
- Kazakh
- Kabiyè
- Kabuverdianu
- Khmer
- Kikuyu
- Kinyarwanda
- Kyrgyz
- Kimbundu
- Northern Kurdish
- Kikongo
- Korean
- Lao
- Ligurian
- Limburgish
- Lingala
- Lithuanian
- Lombard
- Latgalian
- Luxembourgish
- Luba-Kasai
- Ganda
- Luo
- Mizo
- Standard Latvian
- Magahi
- Maithili
- Malayalam
- Marathi
- Minangkabau (Arabic script)
- Minangkabau (Latin script)
- Macedonian
- Plateau Malagasy
- Maltese
- Meitei (Bengali script)
- Halh Mongolian
- Mossi
- Maori
- Burmese
- Dutch
- Norwegian Nynorsk
- Norwegian Bokmål
- Nepali
- Northern Sotho
- Nuer
- Nyanja
- Occitan
- West Central Oromo
- Odia
- Pangasinan
- Eastern Panjabi
- Papiamento
- Western Persian
- Polish
- Portuguese
- Dari
- Southern Pashto
- Ayacucho Quechua
- Romanian
- Rundi
- Russian
- Sango
- Sanskrit
- Santali
- Sicilian
- Shan
- Sinhala
- Slovak
- Slovenian
- Samoan
- Shona
- Sindhi
- Somali
- Southern Sotho
- Spanish
- Tosk Albanian
- Sardinian
- Serbian
- Swati
- Sundanese
- Swedish
- Swahili
- Silesian
- Tamil
- Tatar
- Telugu
- Tajik
- Tagalog
- Thai
- Tigrinya
- Tamasheq (Latin script)
- Tamasheq (Tifinagh script)
- Tok Pisin
- Tswana
- Tsonga
- Turkmen
- Tumbuka
- Turkish
- Twi
- Central Atlas Tamazight
- Uyghur
- Ukrainian
- Umbundu
- Urdu
- Northern Uzbek
- Venetian
- Vietnamese
- Waray
- Wolof
- Xhosa
- Eastern Yiddish
- Yoruba
- Yue Chinese
- Chinese (Simplified)
- Chinese (Traditional)
- Standard Malay
- Zulu

The user must provide the following inputs:
`gRPC method`: translate.
`source_lang`: the source language in which the sentences were written.
`target_lang`: target language that the sentences will be translated.
`sentences_url`: string or URL file with sentences to be translated.

The output format is:
`translation`: sentences translated by the specific model.

You can use this service from SingularityNET DApp.
## What to expect from this service?
### Inputs:
```
"source_lang": English
"target_lang": Afrikaans
"sentences_url": "I hate cats!"
```
### Outputs:
```"translation": "Ek haat katte!"```
