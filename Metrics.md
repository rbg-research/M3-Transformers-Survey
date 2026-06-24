## Evaluation Metrics

| S.No | Metric | Full Name / Expansion | Category / Use Case | Short Description |  References                        |
| :--- | :--- | :--- | :--- | :--- |:-----------------------------------|
| **1** | **WER** | Word Error Rate | Speech Recognition (ASR) | The standard ASR metric defined as the sum of substitutions, deletions, and insertions divided by the number of reference words. | General ASR, LibriSpeech, CoVoST 2 |
| **2** | **CER** | Character Error Rate | Speech Recognition (ASR) | Evaluates error at the character level; preferred for languages with complex morphology or non‑segmented writing systems. | ML-SUPERB 2.0                      |
| **3** | **PER** | Phone Error Rate | Speech Recognition (ASR) | Used for phonetic analysis and low-resource settings where phone inventories are shared but lexicons differ. | UniSpeech                          |
| **4** | **Worst-language metric** | - | Multilingual Benchmarking | Explicitly tracks how much performance drops for the least supported languages to highlight disparities. | ML-SUPERB 2.0                      |
| **5** | **BLEU** | Bilingual Evaluation Understudy | Speech Translation (S2TT) | A standard text-based metric for translation quality; historically used as ASR-BLEU for S2ST outputs. | CoVoST 2, MuST-C, Europarl-ST      |
| **6** | **chrF / chrF++** | Character n-gram F-score | Speech Translation (S2TT) | Computes character-level F-scores; recognized as more robust than BLEU for morphologically rich languages and noisy outputs. | CoVoST 2, MuST-C                   |
| **7** | **BLASER** | - | Speech-to-Speech Translation | A text-free metric that embeds source, system output, and reference speech into a shared space to predict quality scores directly from speech. | SeamlessM4T                        |
| **8** | **MOS** | Mean Opinion Score | Speech Generation (TTS, S2ST) | The main subjective metric for naturalness, where listeners rate generated samples on a 1-5 scale. | VALL-E, AudioPaLM, SeamlessM4T     |
| **9** | **Speaker Similarity** | Cosine Similarity | Speech Generation (TTS, S2ST) | Computes the cosine similarity between embeddings of reference and generated speech to measure faithfulness to the speaker. | x-vectors, ECAPA                   |
| **10** | **MCD** | Mel Cepstral Distortion | Voice Conversion (VC), TTS | Measures frame-level acoustic closeness and spectral distances between reference and generated speech. | SpeechT5                           |