# VCFAD - Voice Cloning and Fake Audio Detection

**Background:**

We are a technology company working in the Cyber Security industry. We focus on building systems that help individuals and organizations to have safe and secure digital presence by providing cutting edge technologies to our customers. We create products and services that ensure our customers security using data driven technologies to understand whether audio and video media is authentic or fake.
Our goal in this project is to build algorithms that can synthesize spoken audio by converting a speaker’s voice to another speaker’s voice with the end goal to detect if any spoken audio is pristine or fake.

**Data Description:**

There are two datasets you can utilize in this project. Both datasets are publicly available sources.
TIMIT Dataset:
The TIMIT corpus of read speech is designed to provide speech data for acoustic-phonetic studies and for the development and evaluation of automatic speech recognition systems. TIMIT contains a total of 6300 sentences, 10 sentences spoken by each of 630 speakers from 8 major dialect regions of the United States.
#CommonVoice Dataset:
Common Voice is part of Mozilla's initiative to help teach machines how real people speak. Common Voice is a corpus of speech data read by users on the Common Voice website (https://commonvoice.mozilla.org/), and based upon text from a number of public domain sources like user submitted blog posts, old books, movies, and other public speech corpora. Its primary purpose is to enable the training and testing of automatic speech recognition (ASR) systems.
**Methdology**

A machine learning system is created to detect if a spoken audio is synthetically generated or not. For that we build a voice cloning system given a speaker’s spoken audio that clones the source speaker’s voice to the target speaker’s voice. We are using TIMIT dataset for this and we use voice cloning functions to create synthetic voices.
For the fake audio detection system (FAD) we utilize the CommonVoice dataset as it consists of thousands of naturally spoken audio which could be used as golden spoken audio by humans as positive examples and creating negative examples using the voice cloning system as automatic data/label generator. After which we train.
