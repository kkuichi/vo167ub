# Text Classification Models: DistilBERT, BERTweet, ConvBERT, ELECTRA 

Tento repozitár obsahuje implementáciu a vyhodnotenie štyroch transformerových modelov určených pre binárnu klasifikáciu krátkeho textu, 
konkrétne na detekciu pôvodu textu – či bol text napísaný človekom (human) alebo vygenerovaný umelou inteligenciou (AI). 
Modely boli trénované a testované na vlastnej dátovej sade, a ich výkon bol meraný pomocou confusion matíc a metrík.
Modely detekovali krátke textové príspevky 

## Použité modely

- **DistilBERT** – odľahčená verzia BERT-u, zachovávajúca vysokú presnosť pri nižších nárokoch na výpočtový výkon.
- **BERTweet** – špecializovaný model pre klasifikáciu krátkych textov, optimalizovaný pre dáta zo sociálnych sietí (napr. Twitter).
- **ConvBERT** – architektúra kombinujúca konvolučné filtre a self-attention mechanizmus pre efektívnejšie spracovanie kontextu.
- **ELECTRA** – efektívna alternatíva k BERT-u, využívajúca diskriminačný prístup k trénovaniu pomocou generátora a diskriminátora.

## Vyhodnotenie

Modely boli porovnávané na základe výstupných confusion matíc. Výpočtom základných metrík ako:
- Accuracy
- Recall
- F1-skóre
- AUC

