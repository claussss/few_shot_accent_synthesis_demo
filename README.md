# Few-Shot Synthetic Accented Speech for ASR Fine-Tuning: What Helps and When?

Demo page (audio samples) for the paper **"Few-Shot Synthetic Accented Speech for ASR
Fine-Tuning: What Helps and When?"** by Yurii Halychanskyi, Nimet Beyza Bozdag,
Mark Hasegawa-Johnson, Dilek Hakkani-Tür, and Volodymyr Kindratenko.

- 📄 Paper: https://arxiv.org/abs/2604.27273
- 🌐 Live demo: https://claussss.github.io/few_shot_accent_synthesis_demo
- 💻 Code: https://github.com/claussss/accented_Speech_for_ASR_what_helps_and_when
- 🔊 Open `index.html` to listen to the audio samples.

The page presents Indian English and Korean English samples for each Table 1 condition
(American TTS, Adapt-only, Adapt + LLM, Adapt + Random, Adapt + GT, and real accented speech),
together with the full LLM phoneme-editing prompt.

## Contents

- `index.html` — the demo page.
- `audio/<accent>/<condition>/*.wav` — audio samples (`accent` ∈ {`indian`, `korean`};
  `condition` ∈ {`american_tts`, `adapt_only`, `adapt_llm`, `adapt_random`, `adapt_gt`, `real`}).
- `llm_prompt_indian.txt` — the LLM prompt used for the Indian English condition.

## Local preview

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```
