### DS_B_BASE.tsv
from y-akinobu/corpus_NL-code/DS_B_BASE.tsv

### expt.tsv
実験用に整備したexpt.txtをMultieseによりDA処理したファイル
```
python3 ~/Git/multiese/multiese.py --pyfirst --out before_expt.tsv --max 3 expt.txt
python3 ~/Git/kolab/kolab/yk/yk.py before_expt.tsv > expt.tsv
```

### DS_B_BASE+expt.tsv
DS_B_BASE.tsvとexpt.tsvを結合したファイル
