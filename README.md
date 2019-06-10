# Joint-NLU
Joint Slot and Intent Extraction implementation in Tensorflow2.0

Implementation of Bi-LSTM based NLU baseline, evaulated on Snips and ATIS datasets.

Preprocessing modules reused from following repo:
https://github.com/MiuLab/SlotGated-SLU/


## Results

**Atis Dataset:**

Inference time per query for batch of 893 queries: 1.89 ms

* Slot_f1: 95.08	  
* Intent_accuracy: 94.62	    
* Semantic_accuracy: 81.97

**Snips Dataset:**

Inference time per query for batch of 700 queries: 2.71 ms

* Slot_f1: 84.30     
* Intent_accuracy: 96.57	    
* Semantic_accuracy: 66.43
