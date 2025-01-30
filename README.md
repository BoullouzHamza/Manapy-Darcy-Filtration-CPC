# Manapy-Darcy-Filtration-CPC

## Requirements

***Python3**:
```bash
sudo apt-get install python3 python3-dev
```

## Installing the library
-----

***Standard mode**:
```bash
python3 -m pip install .
```
   
***Development mode**:
```bash
python3 -m pip install --user -e .
```

## pyccelize functions

```python
./run_pyccel.sh
```
## Running tests
All the test cases are presented in the folder **tests**


### Test 1 (Analytical: unidirectional case):
```bash
cd manapy/tests/Test1
python file.py
```


### Test 2 (Analytical: radial case):
```bash
cd manapy/tests/Test2
python file.py
```

### Test 3 (Experimental: Test1):
```bash
cd manapy/tests/Test3
python file.py
```

### Test 4 (Experimental: Test2):
```bash
cd manapy/tests/Test4
python file.py
```

### Test 5 (Complex geometry):
```bash
cd manapy/tests/Test5
python file.py
```
### Test 6 (T-shaped structure with delta empty):
```bash
cd manapy/tests/Test6
python file.py
```

### Test 7 (T-shaped structure with delta filled):
```bash
cd manapy/tests/Test7
python file.py
```



