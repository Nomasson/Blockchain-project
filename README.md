**Activate the virtual environment**

```buildoutcfg
source blockchain-env/Scripts/activate
```
**Install all packages**

```
pip3 install -r requirements.txt
```

**Run the tests**

Make sure to activate the virtual environment.

```buildoutcfg
python3 -m pytest backend/tests
```