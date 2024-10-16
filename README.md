# Yomitan Dictionaries

A collection of Yomitan dictionaries created or modified by me. Check out [MarvNC's Dictionaries](https://github.com/MarvNC/yomitan-dictionaries) for a more general list.

## JPDB v2.2 Frequency

Frequency list scraped from JPDB's enormous corpus of Japanese media.

Coverage of the corpus is 99.99% up to 25000, 99.5% up to 70000, and 98.6% up to 100000. This far exceeds the coverage of the original JPDB frequency dictionary.

**Quality:** High

### JPDB v2.2 Frequency Kana (Recommended)

Displays the frequency of the word and the frequency of the word being written in kana (denoted by `㋕`). Matches the format of the original JPDB frequency dictionary.

**Preview:** `読む` -> `JPDBv2㋕ 395, 19886㋕`, `よむ` -> `JPDBv2㋕ 19886㋕`, `仮名` -> `JPDBv2㋕ 117㋕, 34102`

**Download:** [JPDB v2.2 Kana](https://github.com/Kuuuube/yomitan-dictionaries/raw/main/dictionaries/JPDB_v2.2_Frequency_Kana_2024-10-13.zip)

### JPDB v2.2 Frequency Kana Display Only

Displays the frequency of the word and the frequency of the word being written in kana (denoted by `㋕`). But does not use the kana frequency internally in sorting or in frequency handlebars.

This version is suitable to be used as a frequency sorting dictionary.

**Preview:** `読む` -> `JPDBv2㋕ 395, 19886㋕`, `よむ` -> `JPDBv2㋕ 19886㋕`, `仮名` -> `JPDBv2㋕ 34102, 117㋕`

**Download:** [JPDB v2.2 Kana Display Only](https://github.com/Kuuuube/yomitan-dictionaries/raw/main/dictionaries/JPDB_v2.2_Frequency_Kana_Display_Only_2024-10-13.zip)

### JPDB v2.2 Frequency

Only displays the frequency of the exact word. Does not display the frequency of the word being written in kana.

**Preview:** `読む` -> `JPDBv2 395`, `よむ` -> `JPDBv2 19886`, `仮名` -> `JPDBv2 34102`

**Download:** [JPDB v2.2](https://github.com/Kuuuube/yomitan-dictionaries/raw/main/dictionaries/JPDB_v2.2_Frequency_2024-10-13.zip)

**Source:** https://jpdb.io/

**Data files:** [JPDB CSV](https://github.com/Kuuuube/yomitan-dictionaries/raw/main/data/jpdb_v2.2_freq_list_2024-10-13.csv)

## BCCWJ SUW LUW Combined

BCCWJ SUW and BCCWJ LUW combined into one dictionary to save space on the Yomitan popup.

**Quality:** High

**Preview:** `読む` -> `BCCWJ 292, 375`

**Download:** [BCCWJ SUW LUW Combined](https://github.com/Kuuuube/yomitan-dictionaries/raw/main/dictionaries/BCCWJ_SUW_LUW_combined.zip)

**Source:** https://github.com/toasted-nutbread/yomichan-bccwj-frequency-dictionary

## H Frequency

Frequency dictionary created using data from 13000 H work voice scripts. Much smaller corpus than other frequency lists.

**Quality:** Medium

**Preview:** `読む` -> `H Freq 976`

**Download:** [H Freq](https://github.com/Kuuuube/yomitan-dictionaries/raw/main/dictionaries/H_Freq.zip)

**Source:** https://pyonpyon.moe/h2k/list.txt

**Data files:** [H Freq List](https://github.com/Kuuuube/yomitan-dictionaries/raw/main/data/h_freq_list.tsv)

## JMdict Frequency

Frequency dictionary created based off of the data used by JMdict's news frequency tags. This is included just for reference and I recommend against using it.

JMdict has great word meaning/definition data but their frequency data is terrible.

**Quality:** Low

**Download:** [JMdict Frequency](https://github.com/Kuuuube/yomitan-dictionaries/raw/main/dictionaries/jmdict_freq.zip), [JMDict Kanji Frequency](https://github.com/Kuuuube/yomitan-dictionaries/raw/main/dictionaries/jmdict_kanji_freq.zip)

**Source:** http://ftp.usf.edu/pub/ftp.monash.edu.au/pub/nihongo/edict_doc.html

**Data files:** [JMdict Wordfreq](https://github.com/Kuuuube/yomitan-dictionaries/raw/main/data/jmdict_wordfreq.zip)
