# Submissions

| Model | Decision Index | Results | Engine and exact code | Hardware | Declared capacity limits |
|---|---:|---|---|---|---|
| DM-JEPA 1.1 (`DangerLabs/DM-JEPA`) | **23.16** | [full run and scores](https://huggingface.co/datasets/DangerLabs/decision-index-results/blob/aacfb8dc266c75da3cbb13fc4c9bf4ca4c946c2a/runs/dm-jepa/scores.json) | Non-autoregressive JEPA System 1 architecture (`dm-jepa`); kit `87d4650` (0.2.1 scoring) | 1x NVIDIA GB10 (121.7GB) / NVIDIA RTX 3060 | Context 16,384 tokens; options up to 512 tokens. 241 scoreable requests unsupported. No truncation or option filtering. |
