# README

This is a text corpus in progress based on collection of Livonian folksongs *Volkslieder der Liven* by Oskar Loorits, published in 1936 and scanned at the Tartu University Library https://hdl.handle.net/10062/100817 with the licence Attribution-NonCommercial-NoDerivs 3.0 Estonia. The library is not allowed to change the lisence but the permission needs to be asked from Loorits' relatives. Until permission, the corpus cannot be shared or opened, but can be used for research purposes.

## The source material

*Volkslieder der Liven* is the most comprehensible collection of Livonian folk songs. According to *Valts Ernštreits* (oral communication), it comprises most of the known Livonian song types. In addition to songs, it also contains nursery rhymes, games and some prose stories. Most of the material was recorded by Loorits himself in handwriting, but the book also contains contributions from other early collectors and some phonograph transcriptions. This corpus includes all the poetic material with metadata in xml format.

## Included files

- **Volkslieder der Liven.xml** — The full corpus (i.e. all the poetic texts).
- **Livonian female singers.xml** — List of female singers represented in the corpus.
- **Livonian male singers.xml** — List of male singers represented in the corpus.
- **Collectors, Volkslieder der Liven.xml** — List of collectors appearing in the metadata.

## Corpus processing

The corpus has been processed within projects FILTER (PI. Kati Kallio & Eetu Mäkelä, Finnish Literature Society & University of Helsinki, in collaboration with the Estonian Folklore Archives) and REFOP (Kati Kallio, Finnish Literature Society) funded by the Finnish Research Council at the Finnish Literature Society in 2023–2026. Research assistant Sakari Korpikallio created the first version and the xml structure, research assistant Mirjami Sipilä trained a Transcribus model for the book with the help of research assistant Jakob Lindström, and then Sipilä transcribed most of the book, and completed the metadata fields.

## Contents of the corpus

The publication is in German. The song texts are mostly in Livonian, with some versions of similar songs or stanzas in Latvian when performed by the same informants. German translations are provided, often one translation for several variants, and many songs also contain musical notations.

This corpus only contains song texts in Livonian and their occational parallel versions in Latvian. The translations in German are not included. The book also contains lengthy introduction and appendix with contextual information about Livonians, collecting and the singers. These parts of the book are not included in the corpus. We recommend reading the contextual information in the book before using the corpus.

## The structure of the publication

The book is ordered by poem genres, poem types, and their versions. The poem types and their versions are numbered, very similar versions marked with alphabets (e.g. 18: 3a): this is also the main reference used for the items. Some Latvian parallel versions are given their own number while others are just given as parallels to the Livonian texts without numbering. In the corpus, the main signum for each item is the poem type and version number in the book. Also the ID number is based on these.

### Example

| Element | Description |
|---------|-------------|
| Id number | vl515A07 |
| Vl | = *Volkslieder der Liven* |
| 515 | = poem type number in the publication |
| A | = subtype in the publication |
| 07 | = variant number in the publication |

If a variant exists only in Latvian, it has no variant number in the original publication. In the corpus, a small *a* is added after the variant number.

Latvian poems are typically parallel versions for the Livonian variant performed by the same singer. In this case they have not been separated by variant numbers. If the Latvian poem has been considered to be its own variant, it has been added with alphabet a (in lower case).

The parish code for the entire Livonian coast is `vl001`.

## Signums and metadata

In the original publication, signums given under each poem. For example, "Kr Melngailis 27 (38)" is a typical code that gives an abbreviation of the village where the text has been recorded (Kr.), the surname of the collector if someone else than Loorits (Melngailis), and the number of the song (27) in the song index at the end of the book.

### Examples:
- `Kr Melngailis 27 (38)` — village abbreviation (Kr.), collector (Melngailis), song number in the index.
- `ERA III 7, 268 (29) u. Fon. 325-e` — references to archival collections.
- `Kr, 10. VIII 1934 < G. S., 1863 (V)` — village abbreviation (Kr.), date (10.8.1934), informant initials, birth year, village.

The number of song collected by Loorits from a certain village or a reference to another collector. The list of these is provided at the end of the book, and these lists are further organised by recording trips and informants.

If a poem has only one variant, which is then not numbered in the publication, the corpus assigns it a variant number (1).

## Characters used in the corpus

In the corpus there has been used latin alphabets and these characters:

- `r̄ t̄ n̄ s̄ l̄` — consonants marked as long or geminated
- `Ā ā ē ī Ī ō Ō ū Ū ǖ ǟ å̄ Å̄ Ǟ ȫ ȭ` — long vowels
- `ā́ ī́ ṍ` — long vowels with an acute accent
- `Š š Ž ž` — sibilants
- `š́ ž́` — palatalized or otherwise modified sibilants
- `č Č` — affricate
- `ń ņ ľ ļ ť Ť ď ģ ŕ ŗ ķ ḱ` — palatalized or otherwise modified consonants
- `n̥ g̥ m̥` — voiceless or weakly articulated consonants
- `á` — vowel with acute accent
- `ă` — short vowel
- `ė` — close or central e‑vowel
- `‿` — linking mark between words
- `~` — indicates an alternative form
- `ʼ` — apostrophe
- `—` — em dash
- `← →` — reference arrows
- `„ "` — quotation marks (matching the original publication)
- `: , :` — used to mark repetition of a line or phrase.

## Village abbreviations

In the corpus, the village name is provided in Livonian (and in Latvian). In the original publication these are expressed as abbreviations, and at the end of the book the items are listed by the villages, years and singers.

| Abbreviation | Livonian name | Latvian name |
|--------------|---------------|-------------|
| Uu | Ūžkilā | Jaunciems |
| Kl | Kūolka | Kolka |
| Kr | Kūoštrõg | Košrags |
| Ii | Īra | Lielirbe |
| Ir | Irē | Mazirbe |
| L | Lūžkilā | Lūžņa |
| M | Mustānum | Melnsils |
| Pz | Pizā | Miķeļtornis |
| Pr | Pitrõg | Pitrags |
| Sn | Sǟnag | Saunags |
| Sr | Sīkrõg | Sīkrags |
| V | Vaid | Vaide |

## Notes on special cases

In the corpus, duplicate poems, errors in the code, existence of a musical notation, or longer prose passages not included in the corpus are noted in the `INF` field.

Musical notation is not included in the corpus but marked in metadata. Notation is often based on recordings by Emilis Melngailis; if no signum is given, it is probably written by Loorits.

## XML tagging

The XML coding is done according to existing Finnish folklore corpora. The tags are partly based on Finnish, partly on English. Additional new information eg. in the INF field is given in English.

- `<TEOS>`: publication name (*Volkslieder der Liven*)
- `<LOC>`: location of the item (usually the home village of the informant) as indicated in the publication: area name (Līvõd Rānda) and village in Livonian and, in parentheses, in Latvian
- `<COL>`: name of the recorder(s) of the poem
- `<SGN>`: song number in the publication
- `<TMP>`: time of recording
- `<INF_NIMI>`: name of the informant
- `<INF_ELINAIKA>`: lifetime of the informant
- `<INF_SYNNYINKYLÄ>`: birthplace of the informant
- `<INF>`: additional information
- `<PUB>`: publisher
- `<YOP>`: year of publication
- `<TOS>`: the chapter name in the publication corresponding to the main genre
- `<TOS_ALALUKU>`: the subchapter name in the publication corresponding the subgenre / poem type

