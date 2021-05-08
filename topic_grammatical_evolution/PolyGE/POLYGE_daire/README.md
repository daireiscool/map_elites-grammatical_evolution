# PolyGE: Investigation

Rewritting the PolyGE code found at: https://github.com/PonyGE/PonyGE2.git  
This is to better understand the code.

Notes:

Issues:
- In PonyGE2/src/utilities/fitness/error_metric.py
    - Changed *from sklearn.metrics.classifiaction import f1_score as sklearn_f1_score* to *from sklearn.metrics import f1_score as sklearn_f1_score*