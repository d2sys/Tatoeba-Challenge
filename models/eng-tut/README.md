# opus-2020-07-06.zip

* dataset: opus
* model: transformer
* source language(s): eng
* target language(s): aze_Latn bak chv crh crh_Latn kaz_Cyrl kaz_Latn kir_Cyrl kjh kum mon nog ota_Arab ota_Latn sah tat tat_Arab tat_Latn tuk tuk_Latn tur tyv uig_Arab uig_Cyrl uzb_Cyrl uzb_Latn xal
* model: transformer
* pre-processing: normalization + SentencePiece (spm32k,spm32k)
* a sentence initial language token is required in the form of `>>id<<` (id = valid target language ID)
* download: [opus-2020-07-06.zip](https://object.pouta.csc.fi/Tatoeba-MT-models/eng-tut/opus-2020-07-06.zip)
* test set translations: [opus-2020-07-06.test.txt](https://object.pouta.csc.fi/Tatoeba-MT-models/eng-tut/opus-2020-07-06.test.txt)
* test set scores: [opus-2020-07-06.eval.txt](https://object.pouta.csc.fi/Tatoeba-MT-models/eng-tut/opus-2020-07-06.eval.txt)

## Benchmarks

| testset               | BLEU  | chr-F |
|-----------------------|-------|-------|
| Tatoeba-test.eng-aze.eng.aze 	| 25.6 	| 0.559 |
| Tatoeba-test.eng-bak.eng.bak 	| 9.7 	| 0.327 |
| Tatoeba-test.eng-chv.eng.chv 	| 3.4 	| 0.281 |
| Tatoeba-test.eng-crh.eng.crh 	| 13.7 	| 0.326 |
| Tatoeba-test.eng-kaz.eng.kaz 	| 10.3 	| 0.351 |
| Tatoeba-test.eng-kir.eng.kir 	| 18.0 	| 0.464 |
| Tatoeba-test.eng-kjh.eng.kjh 	| 1.7 	| 0.030 |
| Tatoeba-test.eng-kum.eng.kum 	| 1.7 	| 0.024 |
| Tatoeba-test.eng-mon.eng.mon 	| 9.8 	| 0.358 |
| Tatoeba-test.eng.multi 	| 17.5 	| 0.431 |
| Tatoeba-test.eng-nog.eng.nog 	| 1.1 	| 0.057 |
| Tatoeba-test.eng-ota.eng.ota 	| 0.3 	| 0.043 |
| Tatoeba-test.eng-sah.eng.sah 	| 0.5 	| 0.040 |
| Tatoeba-test.eng-tat.eng.tat 	| 9.4 	| 0.295 |
| Tatoeba-test.eng-tuk.eng.tuk 	| 6.1 	| 0.315 |
| Tatoeba-test.eng-tur.eng.tur 	| 31.6 	| 0.600 |
| Tatoeba-test.eng-tyv.eng.tyv 	| 6.9 	| 0.201 |
| Tatoeba-test.eng-uig.eng.uig 	| 0.1 	| 0.148 |
| Tatoeba-test.eng-uzb.eng.uzb 	| 2.8 	| 0.261 |
| Tatoeba-test.eng-xal.eng.xal 	| 0.1 	| 0.040 |
