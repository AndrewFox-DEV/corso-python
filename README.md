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

