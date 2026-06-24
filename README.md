# M3-Transformers-Survey
### A Systematic Survey of Modality Fusion Strategies in Multimodal Multilingual Multitask SpeechText Transformers


###### This survey reviews recent advances in Multimodal Multilingual Multitask (M3) transformers that jointly process speech and text, with a focus on their role as information fusion systems. We introduce a six‑dimensional taxonomy covering architecture type, pre‑training objectives, modality integration strategies, training data regimes, language coverage and task support. By using it we organised more than forty representative models ranging from encoder‑only self supervised learning encoders (wav2vec 2.0, XLS‑R) to unified encoder-decoder systems (mSLAM, Mu2SLAM, SeamlessM4T, Whisper) and emerging audio‑aware large language models (SpeechGPT, SALMONN, Qwen‑Audio, SpeechLM). Benchmarks such as LibriSpeech, CoVoST 2, MuST‑C, FLEURS, VoxPopuli, Multilingual LibriSpeech, Common Voice, ML‑SUPERB 2.0, AudioBench, BLASER and HPSU, were used to compare these architectures across speech-text tasks, and quantify where current designs succeed and where they fail, especially on low‑resource and typologically distant languages, code‑switched speech, long‑form audio and paralinguistic cues. We then analyse key limitations like speech-text modality gap, quadratic computational cost, data imbalance, evaluation fragmentation and fairness concerns. It also proposes a research road-map spanning improved cross‑modal alignment, more efficient and modular fusion architectures, stronger low‑resource support and standardised multilingual benchmarks. Overall, the survey provides an architectural and algorithmic perspective on speech-text fusion that outlines concrete steps towards robust, equitable and real‑time multimodal communication systems.

![](Figure-7.png)

### Supporting Materials

| S.No | Materials                                              |
|:-----|:-------------------------------------------------------|
| 1    | [Acronyms](Acronyms.md)                                |
| 2    | [Models](Models.md)                                    |
| 3    | [Corpus and Benchmarks](Corpus-Benchmarks.md)          |
| 4    | [Metrics](Metrics.md)                                  |






