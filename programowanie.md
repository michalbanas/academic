# Lista najczęściej wykorzystywanych elementów programowania *R* i *Python*

W dokumencie znajdują się najczęściej wykorzystywane fragmenty programów do wykorzystania bezpośrednio

## Pliki

### Wczytywanie plików

#### Plik *txt*

**Python**

```Python
# wczytaj plik
file_name = 'powtarzalnosc.nc'
my_file = open(file_name, "r")
document = my_file.readlines()
```

**R**

```R
no code
```

### Zapisywanie plików


## Tabele

### Tworzenie

#### Pusta tabela

**Python**

```Python
df = pd.DataFrame(columns = ['x', 'y'])
```

**R**

```R
no code
```

## Ciągi znaków

### Wyrażenia regularne

#### Znajdowanie

**Python**

```Python
pattern = r"X(-(\d*)|\d*)"
lineX = re.match(pattern, line) # znajdz pierwszy
lineX = re.search(pattern, line) # znajdz wszystkie
if lineX:
	lineX = lineX.group()
	print(lineX)
```

**R**

```R
no code
```



## Pusty szablon

**Python**

```Python
no code
```

**R**

```R
no code
```


