# Joint-NLU
Joint Slot and Intent Extraction implementation in Tensorflow2.0

Implementation of Bi-LSTM based NLU baseline and SlotGated-SLU  (Goo et al, 2018)(https://www.csie.ntu.edu.tw/~yvchen/doc/NAACL18_SlotGated.pdf) 
Models are evaulated on Snips and ATIS datasets.

Experiments did not reproduce improvements by SlotGated model over Basline model, the way suggested in paper.

Preprocessing modules reused from following repo:
https://github.com/MiuLab/SlotGated-SLU/

## Results

### Snips Dataset:


| Model      | Slot F1 | Intent accuracy | Semantic Accuracy |
|------------|---------|-----------------|-------------------|
| Baseline   | 84.30   | 96.57           | 66.43             |
| Slot Gated | 83.5    | 95.57           | 66.85             |

### Atis Dataset:

| Model    | Slot F1 | Intent accuracy | Semantic Accuracy |
|----------|---------|-----------------|-------------------|
| Baseline | 95.08   | 94.62           | 81.97             |
