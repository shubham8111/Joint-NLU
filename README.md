# Joint-NLU
Joint Slot and Intent Extraction implementation in Tensorflow2.0

Implementation of Bi-LSTM based NLU baseline, evaulated on Snips and ATIS datasets.

Preprocessing modules reused from following repo:
https://github.com/MiuLab/SlotGated-SLU/



##Results

###Atis Dataset:
Milli seconds per query for batch of 893 queries: 1.894574023516392
slot f1: 95.08138711960368	  intent accuracy: 94.62486002239642	    semantic_accuracy: 81.97088465845465

###Snips Dataset:
Milli seconds per query for batch of 700 queries: 2.7127075114289516
slot f1: 84.3046896177826     intent accuracy: 96.57142857142857	    semantic_accuracy: 66.42857142857143
