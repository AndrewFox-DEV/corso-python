# **CORSO DI PROGRAMMAZIONE IN LINGUAGGIO PYTHON**

Python è un linguaggio di programmazione ad alto livello molto popolare, esso viene utilizzato nel Machine Learning, nello Sviluppo Web, nelle applicazioni desktop e in molti altri campi. Per i principianti, Python ha una sintassi semplice e facile da usare quindi, questo, rende Python un ottimo linguaggio da imparare per chi è alle prime armi.

## **Come iniziare con Python?**

Python è un linguaggio di programmazione multipiattaforma, questo vuol dire che può essere eseguito su più piattaforme come Windows, MacOS, Linux, eccetera, ed è stato persino portato su macchine virtuali Java e .NET. È gratuito e open-source. Oggigiorno, anche se la maggior parte di Linux e Mac odierni hanno Python preinstallato, la versione potrebbe non essere aggiornata, pertanto, è una buona norma installare la versione più recente.

### **Come installare Python?**
1. [Clicca qui](https://www.python.org/downloads/) per andare sul sito di Python nella sezione Downloads.
2. Clicca il pulsantone giallo dove c'è scritto `Download Python 3.11.0`, o nel tuo caso con la versione di quando leggi la guida.
3. Segui tutti i passaggi cliccando semplicemente `Next` e poi alla fine `Finish`, per iniziare non servirà apportare nessuna modifica alla configurazione dell'installazione.

### **Quale editor od IDE utilizzare?**
In questo corso utilizzeremo Idle perché verrà scaricato tramite l'installazione di Python, ma è ottimo utilizzare Visual Studio Code (editor) o PyCharm (IDE) per migliorare la tua esperienza di sviluppo.

### **Come si utilizza Idle?**
1. Cliccare il tasto `WIN`
2. Cercare Idle ed aprirlo
3. Utilizzare la shortcut `CTRL + N` per creare un nuovo file
4. Iniziamo a scrivere codice..
5. Per salvare utiliziamo la shortcut `CTRL + S`
6. Per eseguire il tasto `F5`

# **ADESSO PARTIAMO!!**

Ora che sai utilizzare Idle ed hai scaricato Python iniziamo il corso vero e proprio; iniziamo a scrivere codice!

### **COMMENTI**
I commenti non verranno visualizzati dall'esecutore quindi sentiti libero di prendere appunti ad ogni istruzione che scriverai; man mano te ne serviranno sempre meno, però ti consiglio di scriverli lo stesso, perché, tu conosci il tuo codice, ma se qualcun'altro dovesse modificarlo si potrebbe trovare in grande difficoltà!

```python
# Questo e' un commento
```
Utilizzeremo durante il corso i commenti per aiutarci nella comprensione di ogni istruzione che scriveremo!

### **OUTPUT**
L'output serve per stampare a schermo qualcosa, in questo caso nella console.

```python
# Utiliziamo la funzione print() per stampare a schermo ad esempio la stringa "Hello world!", ossia una stringa
print("Hello world!")
```

### **VARIABILI**
Python non ha un comando per dichiarare le variabili, quindi una variabile viene creata nel momento in cui gli viene assegnato un valore. Le variabili non devono essere dichiarate quindi con un particolare tipo di dato, e possono essere cambiate dopo essere state impostate.

```python
# Creiamo una variabile di tipo stringa di nome var_stringa e gli assegnamo il valore "questa e' una stringa"
var_stringa = "questa e' una stringa"
# E stampiamo a schermo con la funzione print() imparata in precedenza
print(var_stringa)
```

### **ASSEGNAMO PIÙ VALORI A PIÙ VARIABILI**
```python
# Creiamo tre variabili di tipo intero
# Assegnamogli i valori 4, 3 e 10 alle variabili n1, n2, n3
n1, n2, n3 = 4, 3, 10
# Stampiamo a schermo
print(n1)
print(n2)
print(n3)
# Notiamo che quando stampiamo a schermo 
```

### **VARIABILI**

Python non ha un comando per dichiarare le variabili, quindi una variabile viene creata nel momento in cui gli viene assegnato un valore. Le variabili non devono essere dichiarate quindi con un particolare tipo di dato, e possono essere cambiate dopo essere state impostate.

```python
# Creiamo una variabile di tipo stringa di nome var_stringa e gli assegnamo il valore "questa e' una stringa"
var_stringa = "questa e' una stringa"
# E stampiamo a schermo con la funzione print() imparata in precedenza
print(var_stringa)
```

#### **ASSEGNAMO PIÙ VALORI A PIÙ VARIABILI**

```python
# Creiamo tre variabili di tipo intero
# Assegnamogli i valori 4, 3 e 10 alle variabili n1, n2, n3
n1, n2, n3 = 4, 3, 10
# Stampiamo a schermo
print(n1)
print(n2)
print(n3)
# Notiamo che quando stampiamo a schermo i valori vanno a capo
# Per farli stare sulla stessa riga facciamo
print(n1, n2, n3)
# L'utilizzo delle due modalità di output dipende da cosa si sta facendo
```

### **VARIABILI**

Python non ha un comando per dichiarare le variabili, quindi una variabile viene creata nel momento in cui gli viene assegnato un valore. Le variabili non devono essere dichiarate quindi con un particolare tipo di dato, e possono essere cambiate dopo essere state impostate.

```python
# Creiamo una variabile di tipo stringa di nome var_stringa e gli assegnamo il valore "questa e' una stringa"
var_stringa = "questa e' una stringa"
# E stampiamo a schermo con la funzione print() imparata in precedenza
print(var_stringa)
```

#### **ASSEGNAMO PIÙ VALORI A PIÙ VARIABILI**

```python
# Creiamo tre variabili di tipo intero
# Assegnamogli i valori 4, 3 e 10 alle variabili n1, n2, n3
n1, n2, n3 = 4, 3, 10
# Stampiamo a schermo
print(n1)
print(n2)
print(n3)
# Notiamo che quando stampiamo a schermo i valori vanno a capo
# Per farli stare sulla stessa riga facciamo
print(n1, n2, n3)
# L'utilizzo delle due modalità di output dipende da cosa si sta facendo
```

#### **VARIABILI GLOBALI**

Le variabili create al di fuori di una funzione (che poi vedremo, per ora sappi che se vedi scritto `def nome_funzione()` è una funzione) sono note come variabili globali; esse possono essere utilizzate da tutti, sia all'interno delle funzioni che all'esterno.

1. Crea una variabile fuori da una funzione e utilizzala all'interno della funzione

```python
# Dichiarata la variabile n ed assegnato il valore 10
n = 10

# Chiamata (ossia creata) la funzione numero()
def numero():
    # Stampata la variabile
    print(n)

# Richiamata la funzione numero() per farla eseguire (altrimenti non veniva eseguita)
funzione()
```

Se crei una variabile con lo stesso nome all'interno di una funzione, questa sarà locale e potrà essere utilizzata solo all'interno di quella determinata funzione, la variabile globale con lo stesso nome rimarrà com'era, globale e con il valore originale.

```python
# Dichiarata la variabile n ed assegnato il valore 10
n = 10

# Chiama la funzione numero()
def numero():
    # Dichiarata la variabile n (locale) ed assegnato il valore 19
    n = 19
    # Stampa il valore 19 della variabile n
    print(n)

# Richiamata la funzione numero
# Stamperà il valore 19 essendo una variabile locale nella funzione
numero()

# Stamperà il valore 10
print(n)
```

### **PAROLA CHIAVE: global**
Di norma, quando crei una variabile all'interno di una funzione, quella variabile è locale e può essere utilizzata solo all'interno di quella funzione; per creare una variabile globale all'interno di una funzione, puoi utilizzare la parola chiave `global`.

```python
# Chiamta la funzione numero
def numero():
    # Creata la variabile n all'ambito globale
    global n
    # Alla variabile n assegnato il valore 10
    n = 10

# Richiamata la funzione numero()
numero()

# Stampato il valore di n
print(n)
```

Inoltre, utilizzare la parola chiave `global` se si desidera modificare una variabile globale all'interno di una funzione.

```python
# Dichiarata la variabile n ed assegnato il valore 10
n = 10

# Chiama la funzione numero()
def numero():
    # Dichiarata la variabile n (globale)
    global n
    # Assegnamo il valore 19 alla variabile n
    n = 19

# Richiamata la funzione numero
numero()

# Stamperà il valore 19 perché la variabile ha cambiato il suo valore impostato
print(n)
```

### **TIPI DI DATI**

Nella programmazione, il tipo di dato è un concetto importante, le variabili possono memorizzare dati di tipi diversi e tipi diversi possono fare cose diverse, Python ha i seguenti tipi di dati integrati per impostazione predefinita, in queste categorie:

|                   |                                    |
|:-----------------:|:----------------------------------:|
|   TIPO DI TESTO   |                `str`               |
|   TIPI NUMERICI   |      `int`, `float`, `complex`     |
|  TIPI DI SEQUENZA |      `list`, `tuple`, `range`      |
| TIPO DI MAPPATURA |               `dict`               |
|    TIPI DI SET    |         `set`, `frozenset`         |
|   TIPO BOOLEANO   |               `bool`               |
|    TIPI BINARI    | `bytes`, `bytearray`, `memoryview` |
|    NESSUN TIPO    |             `NoneType`             |

Per ottenere il tipo di dato utilizzare la funzione `type()`, come nel seguente esempio:
```python
# Dichiarare la variabile numero_intero ed assegnargli il valore 10
numero_intero = 10
# Stampare a schermo il tipo di dato attraverso la funzione type()
print(type(numero_intero))
# L'output darà <class 'int'> cioè che il tipo di dato è di valore intero
```

### **NUMERI**

Ci sono tre tipi numerici in Python:
1. int
2. float
3. complex

#### **TIPO DI DATO: int**

È un numero intero, positivo o negativo, senza decimali, di lunghezza illimitata.

```python
# Dichiaro la varibile n1 e assegno un valore positivo
n1 = 1
# Dichiaro la varibile n2 e assegno un valore positivo molto lungo
n2 = 43238619021881818
# Dichiaro la varibile n3 e assegno un valore negativo
n3 = -9929318

# Stampo a schermo il tipo di dato di tutti e tre i valori delle variabili
# Essi saranno tutti di tipo intero, quindi l'output sarà <class 'int'>
print(type(n1))
print(type(n2))
print(type(n3))
```

#### **TIPO DI DATO: float**

È un "numero a virgola mobile", può essere positivo o negativo, contenente uno o più decimali. Il float può anche essere utilizzato per numeri scientifici con una "e" per indicare la potenza di 10.

```python
# Dichiaro la varibile n1 e assegno un valore positivo con più decimali
n1 = 1.81
# Dichiaro la varibile n2 e assegno un valore positivo con un decimale
n2 = 1.2
# Dichiaro la varibile n3 e assegno un valore negativo
n3 = -1.91
# Dichiaro la varibile n3 e assegno un valore positivo scientifico
n4 = 35e3
# Dichiaro la varibile n3 e assegno un valore positivo scientifico
n5 = 12E4
# Dichiaro la varibile n3 e assegno un valore negativo scientifico
n6 = -87.7e100

# Stampo a schermo il tipo di dato di tutti e tre i valori delle variabili
# Essi saranno tutti di tipo decimale, quindi l'output sarà <class 'float'>
print(type(n1))
print(type(n2))
print(type(n3))
print(type(n4))
print(type(n5))
print(type(n6))
```

#### **TIPO DI DATO: complex**

I numeri complessi sono scritti con una "j" come parte immaginaria:

```python
# Dichiaro la varibile n1 e assegno un "espressione" positiva complessa
n1 = 3+2j
# Dichiaro la varibile n2 e assegno un valore positivo complesso
n2 = 1j
# Dichiaro la varibile n3 e assegno un valore negativo complesso
n3 = -9j

# Stampo a schermo il tipo di dato di tutti e tre i valori delle variabili
# Essi saranno tutti di tipo decimale, quindi l'output sarà <class 'float'>
print(type(n1))
print(type(n2))
print(type(n3))
```

### **CASTING**

In alcuni momentisi desidera specificare un tipo su una variabile, questo può essere fatto con il casting. Python è un linguaggio orientato agli oggetti e come tale utilizza le classi per definire i tipi di dati, inclusi i suoi tipi primitivi.

Il cast in Python viene eseguito utilizzando le funzioni di costruzione:

- `int()`: Costruisce un numero intero da un intero letterale, un float letterale (rimuovendo tutti i decimali) o una stringa letterale (a condizione che la stringa rappresenti un numero intero)

```python
n1 = int(1)   # n1 sarà 1
n2 = int(2.8) # n2 sarà 2
n3 = int("3") # n3 sarà 3
```

- `float()`: Costruisce un numero float da un intero letterale, un float letterale o una stringa letterale (a condizione che la stringa rappresenti un float o un intero)

```python
n1 = float(1)     # n1 sarà 1.0
n2 = float(2.8)   # n2 sarà 2.8
n3 = float("3")   # n3 sarà 3.0
n4 = float("4.2") # n4 sarà 4.2
```

- `str()`: Costruisce una stringa da un'ampia varietà di tipi di dati, incluse stringhe, letterali interi e letterali float

```python
n1 = str("s1") # n1 sarà 's1'
n2 = str(2)    # n2 sarà '2'
n3 = str(3.0)  # n3 sarà '3.0'
```

### **STRINGHE**

Le stringhe in Python sono racchiuse tra virgolette singole o virgolette doppie.

`"ciao"` è lo stesso di `'ciao'`.

```python
# Stampa la stringa con doppi apici
print("ciao")
# Stampa la stringa con singoli apici
print('ciao')
```

### **STRINGHE MULTILINEA**

È possibile assegnare una stringa multilinea a una variabile utilizzando tre doppi apici:

```python
print("""
Stringa
multilinea
con
doppi
apici
.
""")
```

O tre apici singoli:

```python
print('''
Stringa
multilinea
con
singoli
apici
.
''')
```
