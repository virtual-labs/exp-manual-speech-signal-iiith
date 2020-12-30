### Theory  

The main objective of this experiment is to make the student understand and appreciate the difficulties in automating the task of speech signal-to-symbol transformation. The students are expected to understand terms such as phones, phonemes, syllables, transliteration, pitch or fundamental frequency, quasi-periodicity. The student should gain a good understanding of the speech signal by visual inspection. Given a speech waveform one should be able to discriminate between silence and speech, voiced speech and unvoiced speech. The student should be able to draw the speech waveform for a given word with appropriate time durations and relative amplitudes of the constituent phones.

Write down a sentence in any Indian language, preferably your native language, on a piece of paper or your note book. Also, write down the sentence in English the way you would probably write it if you were writing a mail to your friend in your language

Eg: Let us consider a sentence in Hindi:

Utt #1: भारत हमारा देश है

Transliteration in English: Bharat hamara desh hai

or in Telugu: భారత్ హమారా దేశ్ హై

Utt #2: శ్రీ ఎం వెంకయ్య నాయుడు చెప్పెరు

Transliteration in English: Shri M. Venkaiahnaidu chepperu
Transliteration

Transliteration is the process of writing one language using the script of another language. For example, the Hindi utterance considered earlier is also written in English alphabets. The primary advantage of writing Hindi or any other Indian languages in English is that one can read it on a computer even if fonts for Devanagari (Hindi or Sanskrit script) or other Indian languages are not installed or rendered properly. Also, it is easier to write and debug programs using these English alphabets, till the time Indian language support for computers becomes widespread. In such a scenario, all softwares on our computer will be in our native script and one can write programs using our native script instead of English.

The transliteration of the Hindi utterance given above (written using English alphabets or Latin script) uses a convention to write down Hindi alphabets in English. Eg. 'Bha' is used for 'भा'. Somebody else may write it as 'Bhaa' or 'BhA' or 'bhaa' or 'bhA' so that the long vowel 'aa' or 'A' can be easily discriminated from its short vowel 'a'. Also note that 'bh' is used to denote the aspirated sound so as to discriminate from its unaspirated counterpart 'b'. It is fine as long as it does not conflict with any other alphabet which may lead to ambiguity. The point here is that, there is a need for a common rule or convention, if followed by every one, makes life easier and avoids confusion during discussions or when programs are shared. [ITRANS](https://en.wikipedia.org/wiki/ITRANS) code is one such convention used to write Indian language alphabets in English.

Transliteration in English: Bharat hamara desh hai

Transliteration in ITRANS: sri em venkayyanayudu chepperu
Recording and studying the speech signal

Record a speech utterance using any sound recording utility at a sampling rate of 8 kHz or 16 kHz, at 16 bits per sample. A recording utility is provided in the experiment section as part of this virtual lab, which by default records records at 8 kHz and 16 bits per sample. Some of the other recording utilities that can be used for offline recording are [wavesurfer](http://www.speech.kth.se/wavesurfer/index.html), [audacity](https://sourceforge.net/projects/audacity/) or [praat](https://www.fon.hum.uva.nl/praat/), which can be freely downloaded from the net.

It is assumed that the sound card is configured properly on your machine and you are able to record and playback audio signals.

Display the recorded speech signal using any waveform analysis utility. Zoom in, select and listen to shorter segments of the speech waveform. Try to identify regions of speech and nonspeech (silence) by visual inspection.
