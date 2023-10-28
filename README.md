# datasets
Datasets for Deep Learning and Machine Learning

* neural_lemmatizer.csv --- Indian author's dataset (Context Sensitive Neural Lemmatizer for Bangla)
* word_pos_final.csv --- Human annotated pos tags (word-->pos)
* word_pos_lemma_gold2.csv --- (word, pos, lemma) form above dataset (uncleaned)
* sentences_gold_2914.csv --- (sentences from POS gold)
* buet_nmt
  * rising_news_test_1000.csv ---> (sentence, lemmas) cleaned without corrections

# Resources
* Bengali_Dataset.txt (https://github.com/Hyperparticle/neural-lemmatizer-allennlp)

# Summary
# Dataset Summary BanglaNMT:
* [All Uncleaned Sentences - 2664142](https://drive.google.com/file/d/1uqo4pCVo4AGXZVSw4_KRJf6gnVD703Wu/view?usp=sharing)
* [All Cleaned Sentences - 2664142](https://drive.google.com/file/d/1-6wUAiA2nqJ2IKXEUiYpabVaYO4s-c_D/view?usp=sharing)
* [All Vocabulary (uncleaned) - 2671 ](https://drive.google.com/file/d/1-4lCTM0fWNyC_gMFolt9-AeH4gUI4qJc/view?usp=sharing)
* [Pure Vocabulary for Bangla - 72](https://drive.google.com/file/d/1-5RpRvD3gkdbgITc91HPlWeKsIzgPPiY/view?usp=sharing)
* [All Words with frequency 649042](https://drive.google.com/file/d/1MZ_gIDYZ2bshe31f-nFel3b8bvN2wJju/view?usp=sharing)
* [vocab_bangla_108_nltk - initial chosen char for cleaning](https://drive.google.com/file/d/1UrArHD7qbW7L26QyZXMkk1F8n5apaiBH/view?usp=sharing)
* [Jakir Arnob 18000+](https://github.com/Jak57/datasets/tree/main/buet_nmt/Annotation_JA_18000)
* [sentencewise lemmatization dataset 11k](https://github.com/Jak57/datasets/tree/main/sentencewise_lemmatization_dataset)

# BaNeL
1. [banel dataset as txt file - only unique words for tokenization](https://github.com/Jak57/datasets/blob/main/banel/banel.txt)
2. [bpe tokenizer for banel - 30k](https://github.com/Jak57/datasets/blob/main/banel/tokenizer-banel.json)

# Tools
* [Bangla nltk for vocabulary list](https://pypi.org/project/bltk/)

```
Vowels = ['অ', 'আ', 'ই', 'ঈ', 'উ', 'ঊ', 'ঋ', 'ঌ', 'এ', 'ঐ', 'ও', 'ঔ']
Vowel_signs = ['া', 'ি', 'ী', 'ু', 'ূ', 'ৃ', 'ৄ', 'ে', 'ৈ', 'ো', 'ৌ']
Consonants = ['ক', 'খ', 'গ', 'ঘ', 'ঙ', 'চ', 'ছ', 'জ', 'ঝ', 'ঞ', 'ট', 'ঠ', 'ড', 'ঢ', 'ণ', 'ত', 'থ', 'দ', 'ধ', 'ন', 'প', 'ফ', 'ব', 'ভ', 'ম', 'য', 'র', 'ল', 'শ', 'ষ', 'স', 'হ', 'ড়', 'ঢ়', 'য়', 'ৎ', 'ং', 'ঃ', 'ঁ']
Digits = ['০', '১', '২', '৩', '৪', '৫', '৬', '৭', '৮', '৯']
Operators = ['=', '+', '-', '*', '/', '%', '<', '>', '×', '÷']
Punctuation_marks = ['।', ',', ';', ':', '?', '!', "'", '.', '"', '-', '[', ']', '{', '}', '(', ')', '–', '—', '―', '~']
Others = ['৳', '৺', '্', 'ঀ', 'ঽ', '#', '$']

BANGLA_VOCAB = Vowels + Vowel_signs + Consonants + Digits + Operators + Punctuation_marks + Others

vocab = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z', 'A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z']
digits = ['0', '1', '2', '3', '4', '5', '6', '7', '8', '9']
ENGLISH_VOCAB = vocab + digits
```

# BDSL - Dataset
1. [All sign names from book - 3915](https://github.com/Jak57/datasets/blob/main/BDSL/BDSL_word_list_from_book_3915%20-%20BDSL_word_list.csv)
2. [BDSL_dataset_3951.csv - All words taken from Book of BDSL](https://github.com/Jak57/datasets/blob/main/BDSL/BDSL_dataset_3951.csv)
3. [filenames_from_seniors_4787.csv - ALL Word annotated from seniors](https://github.com/Jak57/datasets/blob/main/BDSL/filenames_from_seniors_4787.csv)

# DataTemp
1. [common_19328.csv - word present in both test and trainset](https://github.com/Jak57/datasets/blob/main/dataverse-2023/updated_dataset/common_19328.csv)
2. [uncommon_28725.csv - only present in test not train](https://github.com/Jak57/datasets/blob/main/dataverse-2023/updated_dataset/uncommon_28725.csv)
3. [previous dataset - word-ipa mapping 37807](https://raw.githubusercontent.com/Jak57/datasets/main/dataverse-2023/previous_trainset_word_ipa_map_37807.csv)
4. [updated_dictionary_training_set38522.csv - updated dataset training set dictionary](https://github.com/Jak57/datasets/blob/main/dataverse-2023/updated_dataset/updated_dictionary_training_set38522.csv)
5. [updated_dictionary_test_set_48053.csv - test set dictionary](https://github.com/Jak57/datasets/blob/main/dataverse-2023/updated_dataset/updated_dictionary_test_set_48053.csv)
6. [models prediction on test set - submission 2](https://docs.google.com/spreadsheets/d/1Vw2NNfo8xFxvegYktlLFuzGQryRlVLXHBtGS1gX0szA/edit?usp=sharing)
7. [model prediction on test set - submission 3](https://raw.githubusercontent.com/Jak57/datasets/main/dataverse-2023/sub3_words_ipa_previous_dataset_48053_testset.csv)
8. [numbers in test data - 2603](https://github.com/Jak57/datasets/blob/main/dataverse-2023/number_temp_cleaned_2603.csv)
9. [previous dataset - train test split](https://github.com/Jak57/datasets/tree/main/dataverse-2023/previous_dataset_train_test_split)
10. [updated dataset train test split](https://github.com/Jak57/datasets/tree/main/dataverse-2023/updated_dataset_train_test_split)
11. [cleaned test data - numbers are normalized 27k from kaggle user](https://raw.githubusercontent.com/Jak57/datasets/main/dataverse-2023/cleaned_test_data.csv)
12. [char set - train, test and demo submission](https://github.com/Jak57/datasets/tree/main/dataverse-2023/previous_dataset/vocab_charset)
13. [cleaned numbers in the dataset with freq. count](https://raw.githubusercontent.com/Jak57/datasets/main/dataverse-2023/number_with_freq_870.csv)
14. [model's prediction on test set - submission 4](https://raw.githubusercontent.com/Jak57/datasets/main/dataverse-2023/words_ipa_previous_dataset_48053_test_set_submission_4.csv)
15. [updated training dataset dictionary](https://raw.githubusercontent.com/Jak57/datasets/main/dataverse-2023/train_u_dictionary_37812.csv)
16. [dataset-char-level-pretrained model mt5, mbart](https://github.com/Jak57/datasets/tree/main/dataverse-2023/pretrained_model)
17. [previous dataset word ipa mapping](https://raw.githubusercontent.com/Jak57/datasets/main/dataverse-2023/previous_trainset_word_ipa_map_37807.csv)
