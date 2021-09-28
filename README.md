# import-pairs
Batch import utility for Jesse ai

Actually it's a empty Jesse project. You can use it by just changing database settings in `config.py`

You can call it with any combination like: 
```console
python import-pairs.py                          # import ftx & Binance perpetual futures pairs for last 2 days
python import-pairs.py ftx binance 2021-09-01   # import ftx & Binance perpetual futures pairs from 2021-09-01
python import-pairs.py ftx 2021-09-01           # import ftx perpetual futures pairs from 2021-09-01
python import-pairs.py 2021-09-01               # import from all exchanges (ftx & Binance perpetual futures) pairs from 2021-09-01
python import-pairs.py ftx                      # import ftx perpetual futures pairs for last 2 days
python import-pairs.py binance 2021-08-01 ftx   # You can enter parameters unsorted
```

and there is two variables in file:

```python
sloMo = False  # Set it True to slow down and debug it
debug = True   # Set it False to mute messages
```

A `template_pairs.py` file is given in project folder. You can select and copy/paste symbols from it.

