# Yomitan Dictionaries

A collection of Yomitan dictionaries created or modified by me. Check out [MarvNC's Dictionaries](https://github.com/MarvNC/yomichan-dictionaries) for a more general list.

## JPDB v2.1 Frequency

Frequency list scraped from JPDB's enormous corpus of Japanese media.

Coverage of the corpus is 99.5% up to 25000, 99% up to 70000, and 98% up to 100000. This far exceeds the coverage of the original JPDB frequency dictionary.

**Quality:** High

### JPDB v2.1 Frequency

**Preview:** `読む` -> `JPDBv2 395`

**Download:** [JPDB v2.1](./dictionaries/JPDB_v2.1_2024-05-26.zip)

### JPDB v2.1 Frequency Kana

Adds the frequency of the word being written in kana, denoted by `㋕`.

**Preview:** `読む` -> `JPDBv2㋕ 395, 19886㋕`, `よむ` -> `JPDBv2㋕ 19886㋕`

**Download:** [JPDB v2.1 Kana](./dictionaries/JPDB_v2.1_kana_2024-05-26.zip)

### JPDB v2.1 Frequency Kana Display Only

Displays the frequency of the word being written in kana, but does not use the kana frequency internally.

If you want to view the frequency of words being kana-only, but also want to use JPDB v2.1 as your frequency sorting dictionary, use this version.

**Preview:** `読む` -> `JPDBv2㋕ 395, 19886㋕`, `よむ` -> `JPDBv2㋕ 19886㋕`

**Download:** [JPDB v2.1 Kana Display Only](./dictionaries/JPDB_v2.1_kana_display_only.zip)

**Source:** https://jpdb.io/

**Data files:** [JPDB CSV](./data/jpdb_v2.1_freq_list_2024-05-26.csv)

## BCCWJ SUW LUW Combined

BCCWJ SUW and BCCWJ LUW combined into one dictionary to save space on the Yomitan popup.

**Quality:** High

**Preview:** `読む` -> `BCCWJ 292, 375`

**Download:** [BCCWJ SUW LUW Combined](./dictionaries/BCCWJ_SUW_LUW_combined.zip)

**Source:** https://github.com/toasted-nutbread/yomichan-bccwj-frequency-dictionary

## H Frequency

Frequency dictionary created using data from 13000 H work voice scripts. Much smaller corpus than other frequency lists.

**Quality:** Medium

**Preview:** `読む` -> `H Freq 976`

**Download:** [H Freq](./dictionaries/H_Freq.zip)

**Source:** https://pyonpyon.moe/h2k/list.txt

**Data files:** [H Freq List](./data/h_freq_list.tsv)

## JMdict Frequency

Frequency dictionary created based off of the data used by JMdict's news frequency tags. This is included just for reference and I recommend against using it.

JMdict has great word meaning/definition data but their frequency data is terrible.

**Quality:** Low

**Download:** [JMdict Frequency](./dictionaries/jmdict_freq.zip), [JMDict Kanji Frequency](./dictionaries/jmdict_kanji_freq.zip)

**Source:** http://ftp.usf.edu/pub/ftp.monash.edu.au/pub/nihongo/edict_doc.html

**Data files:** [JMdict Wordfreq](./data/jmdict_wordfreq.zip)
