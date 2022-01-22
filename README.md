# corgi_for_expt 

### corgiの呼び出し
```
from corgi_for_expt import start_BASE_corgi as corgi
corgi()
```

### モデル概要
|                    | ABCI_BASE | ABCI_BASE_expt     | ABCI_BASE_tuned_by_expt  |  Colab_BASE_tuned_by_expt  | 
| :------------------: | :-------------: | :---------------------: | :---------------------------: |  :---------------------------: | 
| コマンド          | start_BASE_corgi   | start_BASE_expt_corgi | start_abci_tuned_by_expt_corgi   | start_colab_tuned_by_expt_corgi   |
| 事前学習済みモデル | mT5-small     | mT5-small             | ABCI_BASE              |  Colab_BASE               |             
| コーパス          | DS_B_BASE.tsv | DS_B_BASE+expt.tsv    | expt.tsv          |  expt.tsv          | 


