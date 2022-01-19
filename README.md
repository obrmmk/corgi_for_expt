# corgi_for_expt 

### corgiの呼び出し
```
from corgi import start_corgi as corgi
corgi()
```

### モデル概要
|                    | mT5_DS_B_BASE | mT5_DS_B_BASE+expt     | mT5_DS_B_BASE_tuned_by_expt  | 
| :------------------: | :-------------: | :---------------------: | :---------------------------: | 
| コマンド          | start_corgi   | start_BASE_expt_corgi | start_tuned_by_expt_corgi   | 
| 事前学習済みモデル | mT5-small     | mT5-small             | mT5_DS_B_BASE               | 
| コーパス          | DS_B_BASE.tsv | DS_B_BASE+expt.tsv    | expt.tsv          | 


