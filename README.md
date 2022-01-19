# corgi_for_expt

```
from corgi import start_corgi as corgi
corgi()
```

|                    | mT5_DS_B_BASE | mT5_DS_B_BASE+exp     | mT5_DS_B_BASE_tuned_by_exp  | 
| :------------------: | :-------------: | :---------------------: | :---------------------------: | 
| command          | start_corgi   | start_BASE_expt_corgi | start_tuned_by_expt_corgi   | 
| pretrained-model | mT5-small     | mT5-small             | mT5_DS_B_BASE               | 
| corpus          | DS_B_BASE.tsv | DS_B_BASE+expt.tsv    | DS_B_BASE+expt.tsv          | 
