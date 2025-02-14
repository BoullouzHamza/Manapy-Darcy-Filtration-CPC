# Manapy-Darcy-Filtration-CPC

## Requirements

***Python3**:
```bash
sudo apt-get install python3 python3-dev
```

***pip3**:
```bash
sudo apt-get install python3-pip
```

*All *non-Python* dependencies can be installed by following the [instructions for the pyccel library](https://github.com/pyccel/pyccel#Requirements)

## Installing the library
-----

***Development mode**:
```bash
python3 -m pip install --user -e .
```

## Uninstall
-----
***Whichever the install mode**:
```bash
python3 -m pip uninstall manapy
```

## Intall MUMPS

```sh
sudo apt install libmumps-ptscotch-dev && pip install pymumps
```

## pyccelize functions

```python
./run_pyccel.sh
```

## Running tests
All the test cases are presented in the folder **tests**


### Test 1 (Analytical: unidirectional case):
```bash
cd tests/Test1
python Test1.py
```


### Test 2 (Analytical: radial case):
```bash
cd tests/Test2
python Test2.py
```

### Test 3 (Experimental: Test1):
```bash
cd tests/Test3
python Test3.py
```

### Test 4 (Experimental: Test2):
```bash
cd tests/Test4
python Test4.py
```

### Test 5 (Complex geometry):
```bash
cd tests/Test5
python Test5.py
```
### Test 6 (T-shaped structure with delta empty):
```bash
cd tests/Test6
python Test6.py
```

### Test 7 (T-shaped structure with delta filled):
-----
```bash
cd tests/Test7
python Test7.py
```

To use Mumps solver

```sh
sudo apt install libmumps-ptscotch-dev && pip install pymumps
```
