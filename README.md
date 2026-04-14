<style>
  .wrapper, .container-lg {
    max-width: 1200px !important;
  }
  audio {
    width: 220px;
    height: 40px;
  }
  td:nth-child(2) {
    min-width: 300px;
  }
</style>

# Supplementary Material: Audio Samples

This repository contains the audio samples referenced in the paper **"Adapting a Multilingual Zero-Shot Text-to-Speech Model for High-Fidelity Synthesis in Polish Despite Limited Training Data"**. The samples demonstrate the results of our cross-lingual fine-tuning strategy for adapting a foundational non-autoregressive TTS model to the Polish language.

## Models Compared
These samples represent the amateur speech subset used for the subjective MUSHRA (MUltiple Stimuli with Hidden Reference and Anchor) evaluation:
* **Original (Ground Truth):** Professional studio recordings used as the reference.
* **XTTS-v2 (Baseline):** The current local state-of-the-art autoregressive model for Polish.
* **F5-TTS (Proposed):** Our fine-tuned, Polish TTS model.

---

## Amateur Speech Samples (MUSHRA Evaluation)

|       Sample       | Text | Original (Ground Truth) | XTTS-v2 (Baseline) | F5-TTS (Proposed) |
|:------------------:| :--- | :--- | :--- | :--- |
| **Sample&nbsp;1**  | Roman Gutek miał znakomity pomysł. | <audio controls src="original/b_0.wav"></audio> | <audio controls src="output_xtts/b_0.wav"></audio> | <audio controls src="output_f5_tts/b_0.wav"></audio> |
| **Sample&nbsp;2**  | Jak pan ją ocenia jako celnik, jako osoba, która nadzoruje sprawy celne i sprawy graniczne? | <audio controls src="original/b_1.wav"></audio> | <audio controls src="output_xtts/b_1.wav"></audio> | <audio controls src="output_f5_tts/b_1.wav"></audio> |
| **Sample&nbsp;3**  | Co ma oznaczać na przykład kontrola marsz hurtowych? | <audio controls src="original/b_2.wav"></audio> | <audio controls src="output_xtts/b_2.wav"></audio> | <audio controls src="output_f5_tts/b_2.wav"></audio> |
| **Sample&nbsp;4**  | Czy zagrożenia te mogą spowodować kryzys rodziny? | <audio controls src="original/b_3.wav"></audio> | <audio controls src="output_xtts/b_3.wav"></audio> | <audio controls src="output_f5_tts/b_3.wav"></audio> |
| **Sample&nbsp;5**  | A zgadnijcie jeszcze, w kim się wkrótce zakochuje. | <audio controls src="original/b_4.wav"></audio> | <audio controls src="output_xtts/b_4.wav"></audio> | <audio controls src="output_f5_tts/b_4.wav"></audio> |
| **Sample&nbsp;6**  | Albo naginać małe prawdy historyczne po to, aby lepiej przedstawić jakąś wyższą prawdę. | <audio controls src="original/b_5.wav"></audio> | <audio controls src="output_xtts/b_5.wav"></audio> | <audio controls src="output_f5_tts/b_5.wav"></audio> |
| **Sample&nbsp;7**  | Czy wzór Einsteina ma wciąż jakieś praktyczne znaczenie? | <audio controls src="original/b_6.wav"></audio> | <audio controls src="output_xtts/b_6.wav"></audio> | <audio controls src="output_f5_tts/b_6.wav"></audio> |
| **Sample&nbsp;8**  | Rozważmy, czy rejs żyje jako obiekt kultu. | <audio controls src="original/b_7.wav"></audio> | <audio controls src="output_xtts/b_7.wav"></audio> | <audio controls src="output_f5_tts/b_7.wav"></audio> |
| **Sample&nbsp;9**  | Jak z tych wytartych strzępów, symboli, głupstwa i tandety można ułożyć ważną myśl? | <audio controls src="original/b_8.wav"></audio> | <audio controls src="output_xtts/b_8.wav"></audio> | <audio controls src="output_f5_tts/b_8.wav"></audio> |
| **Sample&nbsp;10** | Znowu zaczyna królować zło. Żegnaj cnoto, żegnaj myśli. | <audio controls src="original/b_9.wav"></audio> | <audio controls src="output_xtts/b_9.wav"></audio> | <audio controls src="output_f5_tts/b_9.wav"></audio> |

---

## Professional Speech Samples

| Sample | Text                                                              | Original (Ground Truth) | F5-TTS (Proposed) |
| :---: |:------------------------------------------------------------------| :--- | :--- |
| **Sample&nbsp;1** | Filipek bardzo często i bez wyraźnego powodu gościł w Bydgoszczy. | <audio controls src="original_clarin/sample1.wav"></audio> | <audio controls src="output_f5_tts_clarin/sample1.wav"></audio> |
| **Sample&nbsp;2** | Francuzi nie zapomnieli o skromnych, acz smakowitych detalach. | <audio controls src="original_clarin/sample2.wav"></audio> | <audio controls src="output_f5_tts_clarin/sample2.wav"></audio> |
| **Sample&nbsp;3** | Zwłaszcza że tacy Anglicy są o wiele bardziej pewni awansu niż my. | <audio controls src="original_clarin/sample3.wav"></audio> | <audio controls src="output_f5_tts_clarin/sample3.wav"></audio> |
| **Sample&nbsp;4** | A przecież gdyby tego nie uczynił, badania byłyby opóźnione. | <audio controls src="original_clarin/sample4.wav"></audio> | <audio controls src="output_f5_tts_clarin/sample4.wav"></audio> |
| **Sample&nbsp;5** | Ale przed nami, oprócz wzgórza i rzadkich krzaków, nie było nic. | <audio controls src="original_clarin/sample5.wav"></audio> | <audio controls src="output_f5_tts_clarin/sample5.wav"></audio> |

> **Note:** These recordings originate from the CLARIN dataset and were not included in the MUSHRA evaluation. Consequently, XTTS-v2 samples were not generated for this professional speech subset.

---

<small>
**Acknowledgments:** The CLARIN-PL-Biz male corpus was used for research purposes. For access inquiries, please contact Prof. Maciej Piasecki via [https://clarin.biz/about](https://clarin.biz/about). This work was financed by the European Regional Development Fund as a part of the 2014-2020 Smart Growth Operational Programme, CLARIN - Common Language Resources and Technology Infrastructure, project no. POIR.04.02.00-00C002/19.
</small>


