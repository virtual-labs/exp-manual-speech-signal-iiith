### Link your observations in here

- Marking boundaries at the phoneme-level is the most diffcult compared to using larger units such as syllables or words.

- It is difficult to mark, listen and perceive unambiguously shorter units of sound such phonemes, as compared to syllables or words.

- The boundaries between subword units are fuzzy due to the coarticulation effect.

- The spoken form of a speech utterance (especially spontaneous speech) may not always contain all the phonemes used in the written form. But while listening we use the higher-level language and context information to fill in these sounds and perceive the intended word or phrase.

- The above observations highlight the complexity of the task involved in speech signal-to-symbol transformation, even for human beings who are endowed with the ability to produce and comprehend natural speech.

- Choice of subword unit is one of the important issues in designing an automatic speech signal-to-symbol transformation system.

Word seems to be a good choice, but the number of words in a language run up to several tens of thousands. Devising a pattern recognition/classification strategy for such a large number of classes is a tough task. Also, collecting a large number of examples for each of the words to be used within a statistical framework is difficult.

Syllables are a better option as the number of classes will be in a few hundreds. The context of a sound is inherently captured in the syllable. But the number of classes are still large, and getting enough examples for all possible syllables in a language is difficult.

Choice of phoneme as the subword unit makes the design of a system using statistical framework easier, due to the smaller number of classes (a few tens of classes) and the ease of collecting large number of examples for each class. But handling the variability of phones occuring in different contexts caused by the coarticulation effect is difficult.



