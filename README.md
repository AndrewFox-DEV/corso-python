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

#### **NOTA**: Nel risultato, le interruzioni di riga vengono inserite nella stessa posizione del codice.

### **STRINGHE AFFETTATE**

Puoi restituire un intervallo di caratteri usando la sintassi della sezione puoi specificare l'indice iniziale e l'indice finale, separati da due punti, per restituire una parte della stringa.

```python
stringa = 'ciao sei veramente bello'
# Stampo l'intervallo dalla prima posizione alla nona
print(stringa[1:9])
# OUTPUT: iao sei
```

#### **NOTA**: La stringa è un array quindi il primo carattere ha indice 0.

Tralasciando l'indice iniziale, l'intervallo inizierà dal primo carattere:

```python
stringa = 'ciao sei veramente bello'
# Stampo l'intervallo dall'inizio fino all'ottavo carattere
print(stringa[:9])
# OUTPUT: ciao sei v
```

Tralasciando l' indice finale , l'intervallo andrà alla fine:

```python
stringa = 'ciao sei veramente bello'
# Stampo l'intervallo fino alla fine dal secondo carattere
print(stringa[2:])
# OUTPUT: ao sei veramente bello
```

Usa gli indici negativi per iniziare la sezione dalla fine della stringa:

```python
stringa = 'ciao sei veramente bello'
# Stampo l'intervallo fino alla fine dal secondo carattere
print(stringa[-10:-3])
# OUTPUT: ente be
```

### **MODIFICA LE STRINGHE**

Python ha una serie di metodi integrati che puoi usare sulle stringhe.

Il metodo `upper()` restituisce la stringa in maiuscolo:

```python
stringa = 'testo...'
print(stringa.upper())
# OUTPUT: TESTO...
```

Il metodo `lower()` restituisce la stringa in minuscolo:

```python
stringa = 'TESTO...'
print(stringa.lower())
# OUTPUT: testo...
```

Il metodo `strip()` rimuove qualsiasi spazio bianco dall'inizio o dalla fine:

```python
stringa = ' testo. . .'
print(stringa.strip())
# OUTPUT: testo...
```

### **SOSTITUZIONE STRINGHE**

Il metodo `replace()` sostituisce una stringa con un'altra stringa:

```python
stringa = 'TESTO'
print(stringa.replace('T', '4'))
# OUTPUT: 4ES4O
```

Il metodo `split()` restituisce un elenco in cui il testo tra il separatore specificato diventa gli elementi dell'elenco, quindi divide la stringa in sottostringhe se trova istanze del separatore:

```python
stringa = 'testo paragrafo'
print(stringa.strip(','))
# OUTPUT: ['testo', ' paragrafo!']
```

### **CONCATENAZIONE DI STRINGHE**

Per concatenare o combinare due o più stringhe è possibile utilizzare l'operatore `+`.

```python
stringa1 = 'ciao'
stringa2 = ' '
stringa3 = 'mondo'
# Stringhe concatenate
print(stringa1 + stringa2 + stringa3)
# OUTPUT: ciao mondo
```

### **FORMATTA STRINGHE**

Combinare due tipi di dati non è possibile, quindi il seguente esempio non è possibile:

```python
anni = 36
testo = "Ho " + anni + " anni"
print(testo)
```

Ma possiamo combinare stringhe e numeri usando il metodo `format()`, che prende gli argomenti passati, li formatta e li inserisce nella stringa in cui si trovano i segnaposto `{}`:

```python
anni = 36
testo = "Ho {} anni."
# Inseriamo i numeri della variabile anni nella stringa testo tramite {}
print(testo.format(anni))
```

### **SEQUENZE DI FUGA (ESCAPE SEQUENCES)**

Per inserire caratteri non validi in una stringa, utilizzare un carattere di escape, esso è una barra rovesciata `\` seguita dal carattere che si desidera inserire.

Un esempio di carattere illegale è una doppia virgoletta all'interno di una stringa racchiusa tra virgolette doppie:

```python
testo = 'Questo è 'un testo tra virgolette'.'
print(testo)
# ERRORE
```

Per risolvere questo problema, usa il carattere di escape `\'`; esso consente di utilizzare l'apice singolo quando normalmente non sarebbe consentito:

```python
testo = 'Questo è \'un testo tra virgolette\'.'
print(testo)
# OUTPUT: Questo è 'un testo tra virgolette'.
```

### **BOOLEANI**

I booleani rappresentano uno dei due valori: `True` o `False`. Nella programmazione è spesso necessario sapere se un'espressione è booleana; puoi valutare qualsiasi espressione in Python e ottenere una delle due risposte.

Quando si confrontano due valori, l'espressione viene valutata e Python restituisce la risposta booleana:

```python
print(10 > 0)
# Stamperà True perché 10 è maggiore di 0
```

La funzione `bool()` consente di valutare qualsiasi valore e di dare `True` o `False` in cambio:

```python
print(bool('Hello')
# Stamperà True
```

Quasi ogni valore viene valutato `True` se ha una sorta di contenuto, quindi qualsiasi stringa è `True`, eccetto le stringhe vuote, qualsiasi numero è `True`, tranne 0 e qualsiasi elenco, tupla, set e dizionario sono `True`, tranne quelli vuoti. In effetti, non ci sono molti valori che restituiscono `False`, tranne valori vuoti, come `()`, `[]`, `{}`, `""`, il numero `0` e il valore `None`, e ovviamente il valore `False` è `False`.

```python
print(bool(False))
print(bool(None))
print(bool(0))
print(bool(""))
print(bool(()))
print(bool([]))
print(bool({}))
# Stamperà sempre False
```

### **OPERATORI**

Gli operatori vengono utilizzati per eseguire operazioni su variabili e valori.

Python divide gli operatori nei seguenti gruppi:

- Operatori aritmetici
- Operatori di assegnazione
- Operatori di confronto
- Operatori logici
- Operatori di identità
- Operatori associativi
- Operatori bit a bit

Gli operatori aritmetici vengono utilizzati con valori numerici per eseguire operazioni matematiche comuni:

| **OPERATORE** |     **NOME**    | **ESEMPIO** |
|:-------------:|:---------------:|:-----------:|
|       +       |    addizione    |    x + y    |
|       -       |   sottrazione   |    x - y    |
|       *       | moltiplicazione |    x * y    |
|       /       |    divisione    |    x / y    |
|       %       |      modulo     |    x % y    |
|       **      |   esponenziale  |    x ** y   |
|       //      | divisione piano |    x // y   |

Gli operatori di assegnazione vengono utilizzati per assegnare valori alle variabili:

| **OPERATORE** | **ESEMPIO** | **UGUALE A** |
|:-------------:|:-----------:|:------------:|
|       =       |    x = 3    |     x = 3    |
|       +=      |    x += 4   |   x = x + 4  |
|       -=      |    x -= 6   |   x = x - 6  |
|       *=      |    x *= 4   |   x = x * 4  |
|       /=      |    x /= 8   |   x = x / 8  |
|       %=      |    x %= 4   |   x = x % 4  |
|      **=      |   x **= 2   |  x = x ** 2  |
|      //=      |   x //= 3   |  x = x // 3  |
|       &=      |    x &= 4   |   x = x & 4  |
|      \|=      |   x \|= 3   |  x = x \| 3  |
|       ^=      |    x ^= 3   |   x = x ^ 3  |
|      >>=      |   x >>= 5   |  x = x >> 5  |
|      <<=      |   x <<= 2   |  x = x << 2  |

Gli operatori di confronto vengono utilizzati per confrontare due valori:

| **OPERATORE** |     **NOME**    | **ESEMPIO** |
|:-------------:|:---------------:|:-----------:|
|       ==      |     uguale a    |    x == y   |
|       !=      |     diverso     |    x != y   |
|       >       |     maggiore    |    x > y    |
|       <       |      minore     |    x < y    |
|       >=      | maggiore uguale |    x >= y   |
|       <=      |  minore uguale  |    x <= y   |

Gli operatori logici vengono utilizzati per combinare istruzioni condizionali:

| **OPERATORE** |                          **DESCRIZIONE**                         |      **ESEMPIO**      |
|:-------------:|:----------------------------------------------------------------:|:---------------------:|
|      and      |      restituisce True se entrambe le affermazioni sono vere      |    x < 8 and x < 10   |
|       or      |         restituisce True se una delle affermazioni è vera        |    x < 9 or x < 12    |
|      not      | invertire il risultato, restituisce False se il risultato è vero | not(x < 7 and x < 10) |

Gli operatori di identità vengono utilizzati per confrontare gli oggetti, non se sono uguali, ma se sono effettivamente lo stesso oggetto, con la stessa posizione di memoria:

| **OPERATORE** |                            **DESCRIZIONE**                           | **ESEMPIO** |
|:-------------:|:--------------------------------------------------------------------:|:-----------:|
|       is      |   restituisce True se entrambe le variabili sono lo stesso oggetto   |    x is y   |
|     is not    | restituisce True se entrambe le variabili non sono lo stesso oggetto |  x is not y |

Gli operatori di appartenenza vengono utilizzati per verificare se una sequenza è presentata in un oggetto:

| **OPERATORE** |                                     **DESCRIZIONE**                                    | **ESEMPIO** |
|:-------------:|:--------------------------------------------------------------------------------------:|:-----------:|
|       in      |   restituisce True se nell'oggetto è presente una sequenza con il valore specificato   |    x in y   |
|     in not    | restituisce True se nell'oggetto non è presente una sequenza con il valore specificato |  x not in y |

Gli operatori bit per bit vengono utilizzati per confrontare i numeri (binari):

| **OPERATORE** |                  **NOME**                  |                                              **DESCRIZIONE**                                             |
|:-------------:|:------------------------------------------:|:--------------------------------------------------------------------------------------------------------:|
|       &       |                     AND                    |                              imposta ogni bit su 1 se entrambi i bit sono 1                              |
|       \|      |                     OR                     |                               imposta ogni bit su 1 se uno dei due bit è 1                               |
|       ^       |                     XOR                    |                             imposta ogni bit su 1 se solo uno dei due bit è 1                            |
|       ~       |                     NOT                    |                                            inverte tutti i bit                                           |
|       <<      | spostamento a sinistra di riempimento zero |            sposta a sinistra spingendo gli zeri da destra e lascia cadere i bit più a sinistra           |
|       >>      |           firmato turno di destra          | sposta a destra spingendo le copie del bit più a sinistra da sinistra e lascia cadere i bit più a destra |
