# corgi_for_expt 

### corgiの呼び出し
```
from corgi import start_corgi as corgi
corgi()
```

### モデル比較
|                    | mT5_DS_B_BASE | mT5_DS_B_BASE+expt     | mT5_DS_B_BASE_tuned_by_expt  | 
| :------------------: | :-------------: | :---------------------: | :---------------------------: | 
| コマンド          | start_corgi   | start_BASE_expt_corgi | start_tuned_by_expt_corgi   | 
| 事前学習済みモデル | mT5-small     | mT5-small             | mT5_DS_B_BASE               | 
| コーパス          | DS_B_BASE.tsv | DS_B_BASE+expt.tsv    | expt.tsv          | 

### expt.tsvの生成

```
python3 ~/Git/multiese/multiese.py --pyfirst --out before_expt.tsv --max 3 expt.txt
python3 ~/Git/kolab/kolab/yk/yk.py before_expt.tsv > expt.tsv
```
