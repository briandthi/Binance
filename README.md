# Binance

- Créér un clé API : https://www.binance.com/en/support/faq/360002502072
- **Quand elle est créée garder en mémoire l'api key et la secret KEY**

- créer un fichier config.cfg dans le même répertoire que le notebook et remplacer les valeurs par celles de l'API créée

```cfg
[BINANCE]
API_KEY = YOUR KEY                  # A MODIFIER
SECRET_KEY = YOUR SECRET KEY        # A MODIFIER
```

- installer le package python-binance 

```shell
pip install python-binance
ou
py -m pip install python-binance
ou autre
```
- Editer la list my_coins avec vos crypto

```python
#exemple
my_coins = ['BTC','USDT', 'ETH']     # A ADAPTER
```

- Editer le dict stack car l'API ne sait pas encore récupérer les crypto stackées 

```python
#exemple
stack = {'DOT':3, 'ADA':6.1938, 'CAKE':3.125, 'TRX': 67}      # A ADAPTER
```

- et lancer tout les cellules
! Tout est en dollars
