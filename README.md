# Data-Model-Evaluation
Claasification Model evualtion,including accuracy,ROC/AUC, precision/recall , lift curve
API:

from scipy import interp  --- used to interpolate
from sklearn import svm,datasets
from sklearn.model_selection import cross_val_score,train_test_split, StratifiedKFold,KFold
from sklearn.metrics import confusion_matrix,precision_recall_curve,average_precision_score,roc_curve,auc
