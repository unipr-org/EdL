**INTRODUZIONE AL LINGUAGGIO NATURALE**  
1\. Definizione di proposizione  
Una proposizione è una sentenza dichiarativa che può essere vera o falsa  
Una proposizione composta è formata da più sotto-proposizioni collegate mediante connettivi logici

2\. Connettivi logici  
Abbiamo i connettivi logici estensionali : ∧, ∨, ¬  
e quello condizionale : ⇒  
Il “poiché” non è un connettivo valido perchè obliquo

3\. Equivalenze logiche, regola di deduzione  
Tra le equivalenze logiche più importanti abbiamo:  
	1° legge di De Morgan	¬(p∧q) ≡ (¬p)∨(¬q)  
	2° legge di De Morgan	¬(p∨q) ≡ (¬p)∧(¬q)  
	doppia negazione		p ≡ ¬¬p  
	commutative			p∧q ≡ q∧p	p∨q ≡ q∨p  
Regola di deduzione: se p è vera e p⇒q è vera allora q è vera

4\. Tautologie, contraddizioni  
Una tautologia è una proposizione sempre vera (p∨¬p)  
Una contraddizione è una formula sempre falsa (p∧¬p)

5\. Tavole di verità  
Nelle tavole di verità si dà l’interpretazione semantica ai connettivi tramite 2 simboli (0 e 1\)

6\. Variabili e sostituzione, costanti  
Le variabili sono simboli logici il cui valore non è stabilito a priori e hanno un proprio dominio di esistenza.  
La sostituzione è l’assegnazione di un valore alla variabile  
Le costanti sono simboli logici sostituibili alle variabili

7\. Predicati: proprietà e relazioni  
Un predicato è un’espressione contenente una o più variabili  
P(x) è una proprietà  
P(x,y) è una relazione  
P(x,y,z,...) è un predicato n-ario

8\. Quantificatori e regola di negazione  
Abbiamo 2 quantificatori universali: ∀ (per ogni), ∃ (esiste)  
¬(∀x:P(x)) ⇔ ∃x:¬P(x)  
¬(∃x:P(x)) ⇔ ∀x:¬P(x)

9\. Uguaglianza e assegnamento  
L’uguaglianza è una relazione P(x,y) che esprime il fatto che x e y sono intercambiabili  
Con l’assegnamento x:=y imponiamo una definizione y per x

**INSIEMISTICA**  
10\. Definizione di insieme  
Un insieme è una qualsiasi collezione di oggetti non ripetuti, non necessariamente ordinati o omogenei

11\. Relazione di uguaglianza tra insiemi, inclusione, e inclusione propria tra insiemi  
A=B ⇔ (∀x: x∈A ⇔ x∈B)  
A⊆B ⇔ (∀x: x∈A ⇒ x∈B)  
A⊂B ⇔ (∀x: x∈A ⇒ x∈B) ∧ (∃x: x∉A ∧ x∈B)

12\. Operazioni tra insiemi: unione, intersezione, differenza, differenza simmetrica  
AUB \= {x: x∈A ∨ x∈B}  
A∩B \= {x: x∈A ∧ x∈B}  
A\\B \= {x: x∈A ∧ x∉B}  
AΔB \= (A\\B) U (B\\A) \= (AUB) \\ (A∩B)

13\. Definizione di insieme delle parti  
P(A) è l’insieme di tutti i sottoinsiemi di A

14\. Cardinalità di un insieme finito  
Sia A un insieme finito e ‘n’ il numero di elementi  
La cardinalità di A è uguale a n		|A| \= n

15.Proprietà delle operazioni tra insiemi  
Idempotenza  
Commutativa  
Associativa  
Distributiva  
Assorbimento

16\. Operazioni di complementazione, leggi di De Morgan per insiemi  
Sia A⊆T: ¬A \= T \\ A  
¬¬A \= A  
De Morgan 1°: ¬(A∩B) \= ¬A U ¬B  
De Morgan 2°: ¬(AUB) \= ¬A ∩ ¬B

17\. Insieme prodotto, coppie ordinate  
A×B := {(a,b): a∈A ∧ b∈B}  
Una coppia ordinata si definisce a partire da P(AUB) come (x,y):={{x},{x,y}}

18\. Definizione di applicazione o funzione (iniettiva, suriettiva e biiettiva)  
f relazione su A×B si dice funzione (o applicazione) se  
∀x∈A ∃\!y∈B: (x,y)∈f

E’ iniettiva se ∀x1,x2∈A (f(x1)=f(x2) ⇔ x1=x2)		|A|≤|B|  
E’ suriettiva se ∀y∈B ∃x∈A: f(x)=y				|A|≥|B|  
E’ biiettiva se è iniettiva e suriettiva			|A|=|B|  
(∀y∈B ∃\!x∈A: f(x)=y)

19\. Cardinalità anche su insiemi infiniti  
La cardinalità di un insieme con un numero infinito di elementi può essere numerabile o non numerabile

A e B si dicono equipotenti se ∃f A→B biiettiva e si indica A≈B (|A|=|B|)

A è detto numerabile se A≈ℕ e |A|=|ℕ|=ℵ**0**

20\. Teorema di Cantor, ipotesi del continuo, cardinalità del numerabile  
Teorema di Cantor |A|\<|P(A)|  
Dim.  
Suppongo per assurdo che |A|=|P(A)|  
Esiste quindi una funzione biiettiva f: A→P(A)  
In P(A) prendo l’insieme X così definito X:={x: x∉f(x)}  
L’insieme esiste in quanto X⊂A  
Deve quindi esistere un elemento d tc f(d)=X  
Se d∈f(d) allora d∉f(d)=X  
Se d∉f(d) allora d∈f(d)=X  
Questo è assurdo.

Siccome ogni singoletto {a}∈P(A) e in P(A) abbiamo anche l’insieme A stesso e ∅ giungiamo alla conclusione |A|\<|P(A)|

|ℕ|\<|P(ℕ)|	|P(ℕ)| si dice più che numerabile  
|P(ℕ)|=|ℝ|	si dice cardinalità del continuo  
|ℝ| è la più piccola cardinalità non numerabile (ipotesi del continuo)

**RELAZIONI DI EQUIVALENZA E DI ORDINE**  
Una relazione R(x,y) su A×A si dice

* Riflessiva se ∀x∈A: R(x,x)  
* Simmetrica se ∀x,y∈A: R(x,y) ⇒ R(y,x)  
* Transitiva se ∀x,y,z∈A: R(x,y)∧R(y,z) ⇒ R(x,z)  
* Anti-simmetrica se ∀x,y∈A: R(x,y)∧R(y,x) ⇒ x=y

21\. Definizione di relazione di equivalenza  
Una relazione è di equivalenza se è riflessiva, simmetrica e transitiva

22\. Relazione di uguaglianza come relazione di equivalenza  
R(x,y) ⇔ x=y

23\. Cardinalità come classe di equivalenza  
Per ogni classe di equivalenza si elegge un rappresentante  
La relazione di equivalenza R(A,B)⇔|A|=|B| divide tutti gli insiemi in classi contenenti solo insiemi equipotenti.  
Il rappresentante di ognuna di queste classi è la cardinalità

24\. Definizione di pre-ordine e di relazione d’ordine  
Una relazione si dice di pre-ordine se è riflessiva e transitiva  
Una relazione d’ordine è una relazione che è un pre-ordine ed è anti-simmetrica

25\. Ordinamento degli insiemi numerici con ≤ e ordinamento degli insiemi con ⊆  
≤, ⊆ sono ordinamenti, indichiamo quindi con (A,≤) o (A,⊆) un generico insieme ordinato

26\. Elementi minimali e massimali, minimi e massimi, maggioranti e minoranti, estremi superiori e inferiori  
Un elemento M di un insieme ordinato (A,≤) si dice  
•) Massimo se ∀x∈A: x≤M  
•) Massimale se ∀x∈A: (M≤x ⇒ x=M)  
Analogamente si definisce m minimo e minimale  
Sia X⊂A con A insieme ordinato (A,≤)  
Si dice M maggiorante di X se ∀x∈X: x≤M  
L’insieme dei maggioranti Mx:={a∈A: (∀x∈X: x≤a)}  
Il minimo di questo insieme Mx, se esiste, si dice estremo superiore di X  
Ragionamento analogo per minorante e estremo inferiore

27\. Relazione di divisibilità |  
R(x,y) ⇔ x|y ⇔ ∃m: y=mx

28\. Relazioni di ordine totale e parziale  
Una relazione di ordine su (A,≤) è totale se ∀x,y∈A: x≤y ∨ y≤x

**PRINCIPIO DI INDUZIONE**  
29\. Assiomi di Peano  
L’insieme ℕ è definito tramite gli assiomi di Peano

1) 0 è un numero  
2) Il successivo di un numero è un numero  
3) 0 non è il successivo di nessun numero  
4) Numeri diversi hanno successivi diversi  
5) Se A⊆ℕ, 0∈A, A contiene il successivo di ogni suo numero, allora A=ℕ

30\. Principio di induzione naturale come tecnica dimostrativa  
CB, PI: HP e TS

31\. Esercizi ed esempi di dimostrazioni per induzione (tra cui: somma dei primi n numeri naturali, somma dei primi n termini di una progressione geometrica)  
∑ni=0 i \= (n\*(n+1))/2		∑ni=0 qi \= (1-qn+1)/(1-q)

32\. Funzioni definite per ricorrenza  
Una funzione f:ℕ→A  si dice definita per ricorrenza quando non è nota la legge che da n↦f(n) ma è noto un caso base e una regola per ottenere f(n+1) a partire da f(n)

**COMBINATORIA**  
33\. Richiami alla definizione di cardinalità

34\. Principio della somma  
S e T disgiunti	|SUT| \= |S| \+ |T|	principio della somma  
S1,S2,...,Sn a due a due disgiunti  
|S1US2U…USn| \= ∑ni=1|Si|			principio generalizzato della somma

35\. Principio del prodotto  
|S×T|=|S|∙|T|					principio del prodotto  
S1,S2,...,Sn  
|S1×S2×…×Sn| \= **∏**ni=1|Si|			principio generalizzato del prodotto

36\. Permutazioni di k elementi in n  
Si dice permutazione di k elementi di S una funzione dagli indici ({1,…,k}) a S  
Il numero di permutazioni su k elementi di n è n\!/(n-k)\!

37\. Permutazioni di n elementi  
Una permutazione di k elementi di S, se k=n, si dice permutazione di S.  
Il numero di permutazioni di S è n\!

38\. Combinazioni di k elementi su n  
Il numero di combinazioni di k elementi su n è nk

39\. Coefficiente binomiale, Teorema della potenza n-esima del binomio  
|S|=n, il numero di k-sottoinsiemi di S è (nk)= n\!/(k\!(n-k)\!)  
Poiché ci sono k\! tuple per ogni k-sottoinsieme dal numero di permutazioni ricaviamo quello di k-sottoinsiemi

∀n∈ℕ (x+y)n \= ∑ni=0((nk)xn-kxk)

**LOGICA PROPOSIZIONALE**  
40\. Definizione di alfabeto  
Si dice alfabeto e si indica con 𝓐 (𝓐≠∅) un insieme finito di elementi detti simboli

41\. Definizione di stringa e lunghezza di una stringa  
Si dice stringa una successione finita di elementi di 𝓐  
L’insieme di tutte le stringhe di 𝓐 è 𝓐\*  
len(s): 𝓐\*→ℕ  
{ len(ε)=0  
{ len(cs) \= len(s) \+ 1 (c∈𝓐)

42\. Sintassi: Grammatica della logica proposizionale (formule ben formate)  
L’𝓐 del linguaggio della logica proposizionale è costituito da:

1) Simboli atomici di proposizione: p,q,r,...  
2) Simboli di connettivo: ¬, ∧, ∨, ⇒, ⊥  
3) Simboli ausiliari: (, )

 L’insieme delle FBF è il minimo insieme X tc:

1) ∀proposizione atomica si ha che a,b,c,...∈X  
2) ⊥∈X  
3) Se p∈X allora ¬p∈X  
4) Se p,q ∈X allora p∧q,p∨q,p⇒q∈X

43\. Definizione di sottoformula e altezza di una formula  
sub: X→ℕ  
{sub(a) \= 1	se a è atomica  
{sub(⊥) \= 1  
{sub(¬p) \= sub(p) \+ 1   
{sub(p∧q) \= sub(p) \+ sub(q) \+ 1  
{sub(p∨q) \= sub(p) \+ sub(q) \+ 1  
{sub(p⇒q) \= sub(p) \+ sub(q) \+ 1

alt: X→ℕ  
{alt(a) \= 0	se a è atomica  
{alt(⊥) \= 0  
{alt(¬p) \= alt(p) \+ 1   
{alt(p∧q) \= alt(p) \+ alt(q) \+ 1  
{alt(p∨q) \= alt(p) \+ alt(q) \+ 1  
{alt(p⇒q) \= alt(p) \+ alt(q) \+ 1

44\. Principio di induzione strutturale su FBF del linguaggio proposizionale  
Sia P una proprietà, ∀x∈X: P(x) vale se:

1) ∀a∈X a proposizione atomica: P(a) vale  
2) P(⊥) vale  
3) ∀x∈X P(x) ⇒ P(¬x)  
4) ∀x,y∈X: (P(x)∧P(y))⇒(P(x∧y)∧P(x∨y)∧P(x⇒y))

   
45\. Semantica: soddisfacibilità, contraddizioni e tautologie  
Si dice valutazione ogni funzione v:X→{0,1}  
Una funzione v:X→*B* si dice interpretazione per la logica classica se:  
v(⊥) \= 0  
v(¬p) \= 1 \- v(p)  
v(p∧q) \= min(v(p), v(q))  
v(p∨q) \= max(v(p), v(q))  
v(p⇒q) \= 1 ⇔ v(p)≤v(q)

Sia p∈X e v∈ℑ. Se v(p)=1 allora si dice che p è soddisfatta nell’interpretazione v oppure v è un modello per p		 			v⊨p   
Una p∈X è soddisfacibile se ∃v∈ℑ:v⊨p  
Una p∈X è contraddittoria quando non è soddisfacibile, cioè se ∀v∈ℑ:v(p)=0  
Una p∈X è una tautologia (o è valida) quando ∀v∈ℑ:v⊨p	⊨p

Una p∈X è una tautologia sse ¬p è una contraddizione

Sia Γ⊆X un insieme di FBF. Si dice che Γ è:  
\- soddisfacibile se ∃v∈ℑ:(∀pi∈Γ: v(pi)=1)  
\- insoddisfacibile se ∀v∈ℑ:(∃pi∈Γ: v(pi)=0)

46\. Conseguenza semantica  
Sia Γ⊆X. Si dice che q∈X è conseguenza semantica di Γ sse  
∀v∈ℑ:((∀pi∈Γ: v(pi)=1) ⇒ v(q)=1)					Γ⊨q

Γ⊨p sse ΓU{¬p} è insoddisfacibile

p⊨q sse ⊨p⇒q

47\. Teorema di deduzione semantica  
Γ⊨q sse p1,p2,...,pn⊨q sse p1,p2,...,pn-1⊨pn⇒q  
⊨p1⇒(p2⇒(...(pn⇒q)...)

48\. Equivalenza semantica e regola di sostituzione per FBF  
Siano p,q∈X, si dicono semanticamente equivalenti se  
∀v∈ℑ:(v(p)=v(q))							p≡q

Siano r,p∈X e sia a∈X atomica  
r\[p/a\] è l’FBF ottenuta sostituendo in r tutte le occorrenze di a con la proposizione p

1. r\[p/a\] \= r se r≠a  
2. r\[p/a\] \= p se r=a  
3. (¬r)\[p/a\] \= ¬(r\[p/a\])  
4. (r1∧r2)\[p/a\] \= (r1\[p/a\]) ∧ (r2\[p/a\])  
5. (r1∨r2)\[p/a\] \= (r1\[p/a\]) ∨ (r2\[p/a\])  
6. (r1⇒r2)\[p/a\] \= (r1\[p/a\]) ⇒ (r2\[p/a\])

\*. Regola per assurdo  
p⇒q ≡ p∧(p⇒¬q)⇒⊥ ≡ ¬(p∧(p⇒¬q))

49\. Forme normali congiuntive e disgiuntive  
Siano p1,...,pn∈X si dice disgiunzione (congiunzione) la FBF così costruita:  
p1∨p2∨…∨pn∈X (p1∧p2∧…∧pn∈X)

Un letterale è una proposizione atomica o la sua negazione.

Una FBF è detta in FNC sse è p∈X p \= p1∧p2∧…∧pn dove ogni pi è una disgiunzione di letterali.  
In modo analogo FND.

∀p∈X ∃ pc e pd tc p ≡ pc ≡ pd

50\. Sistemi di calcolo: regole deduttive di introduzione e di eliminazione  
Il problema della logica formale è sviluppare sistemi di calcolo che rendano possibili la completezza e la correttezza.

Sistemi di calcolo: Deduzione naturale, Sistemi assiomatici, Calcolo dei sequenti

Un sistema di calcolo è un insieme di regole nella forma

a1,a2,...,an ⊢ b

Congiunzione  
E∧		a∧b⊢a		a∧b⊢b  
I∧		a,b⊢a∧b

Disgiunzione  
I∨		a⊢a∨b		b⊢a∨b  
Econd∨	se a⊢c    e	b⊢c	allora	a∨b⊢c  
		(premesse sussidiarie)	(conclusione sussidiaria)

Implicazione  
E⇒		a,a⇒b⊢b	(Modus Ponens)  
I⇒		se a⊢b	allora	a⇒b  
Negazione  
⊢a è falsa quando ¬∃ una dimostrazione per a (¬ ⊢a)  
→ ⊢¬a sse ¬ ⊢a 	NO\! instabile\!  
Instabilità: ∀ dim dovrei dimostrare che non conclude a

Una formula a si dice assurda se l’HP di a rende inconsistente la teoria logica  
Inconsistente è una teoria che permette di concludere qualsiasi proposizione

E⊥		⊥⊢a  
E¬		a,¬a⊢⊥  
I¬		se a⊢⊥	allora	⊥⊢¬a  
RAA		se ¬a⊢⊥	allora ⊢a

Regola di taglio  
Se Γ⊢a e Γ,a⊢b	allora	Γ⊢b

51\. Deduzione naturale

\*. Analogie Calcolo-Semantica

Calcolo		|	Semantica  
———————————————————————  
Γ⊢a		|	Γ⊨a  
Derivabilità		|	Conseguenza semantica  
———————————————————————  
⊢a		|	⊨a  
Teorema		|	Tautologia  
———————————————————————  
Γ¬⊢⊥		|	Γ¬⊨⊥  
Consistenza		|	Soddisfacibilità  
———————————————————————  
Γ⊢⊥		|	Γ⊨⊥  
Inconsistenza	|	Insoddisfacibilità  
———————————————————————

52\. Teorema di correttezza della logica proposizionale con il sistema di calcolo di deduzione naturale, e corollario (senza dimostrazione)  
Se Γ⊢a allora Γ⊨a  
Tutto ciò che posso dimostrare è valido

Corollario  
Se ⊢a allora ⊨a	(Γ=∅)

53\. Teorema di completezza e completezza debole della logica proposizionale con il sistema di calcolo di deduzione naturale (senza dimostrazione)  
Se Γ⊨a allora Γ⊢a  
Tutto ciò che è valido lo posso dimostrare

Completezza debole  
Se ⊨a allora ⊢a	(Γ=∅)

Esistono sistemi di calcolo in cui la completezza non è garantita  
(es. sistema assiomatico dell’aritmetica)

**LOGICA DEL I ORDINE**  
54\. Definizione di alfabeto e linguaggio del I ordine  
Un linguaggio del I ordine è definito da un alfabeto composto da;  
•) Un insieme di simboli di costante {a,b,c,...}  
•) Un insieme infinito di variabili {x,y,z,...}  
•) Un insieme di simboli di funzione {f,g,h,...}  
•) Un insieme di simboli di predicato {P,Q,R,...}  
•) Connettivi: ¬, ∧, ∨, ⇒, ⊥  
•) Quantificatori: ∀, ∃  
•) Simboli ausiliari: (, ), :

55\. Sintassi: grammatica dei termini e delle formule ben formate  
TER, insieme dei termini, è il minimo insieme tc:  
1\) c∈TER, c costante  
2\) x∈TER, x variabile  
3\) Se t1,t2,...,tn ∈TER e f è un simbolo funzionale n-ario  
allora f(t1,t2,...,tn)∈TER

FBF è il minimo insieme tc:  
1\) ⊥∈FBF  
2\) Se t1,t2,...,tn ∈TER e P è un predicato n-ario   
allora P(t1,t2,...,tn)∈FBF  
3\) X∈FBF allora (¬X)∈FBF  
4\) X,Y∈FBF allora (X∧Y)∈FBF  
5\) X,Y∈FBF allora (X∨Y)∈FBF  
6\) X,Y∈FBF allora (X⇒Y)∈FBF  
7\) X∈FBF allora (∀x:X)∈FBF  
8\) X∈FBF allora (∃x:X)∈FBF

1 e 2 definiscono gli atomi della logica del I ordine

56\. Definizione di sottoformula e altezza di una formula  
sub:FBF→ ℕ  
{sub(⊥) \= 1  
{sub(A(t1,...tn)) \= 1  
{sub(¬P1) \= sub(P1) \+ 1  
{sub(P1∧P2) \= sub(P1) \+ sub(P2) \+1  
{sub(P1∨P2) \= sub(P1) \+ sub(P2) \+1  
{sub(P1⇒P2) \= sub(P1) \+ sub(P2) \+1  
{sub(∀x:P1) \= sub(P1) \+ 1  
{sub(∃x:P1) \= sub(P1) \+ 1

alt:FBF→ℕ  
{alt(⊥) \= 0  
{alt(A(t1,...tn)) \= 0  
{alt(¬P1) \= alt(P1) \+ 1  
{alt(P1∧P2) \= alt(P1) \+ alt(P2) \+1  
{alt(P1∨P2) \= alt(P1) \+ alt(P2) \+1  
{alt(P1⇒P2) \= alt(P1) \+ alt(P2) \+1  
{alt(∀x:P1) \= alt(P1) \+ 1  
{alt(∃x:P1) \= alt(P1) \+ 1

57\. Principio di induzione strutturale sui termini di un linguaggio del I ordine  
Sia 𝓐 una proprietà sui termini, 𝓐(t) è verificata ∀t∈TER se:  
CB  
∀ costante c : 𝓐(c)  
∀x∈VAR : 𝓐(x)  
PI  
∀t1,t2,...,tn∈TER: 𝓐(t1), 𝓐(t2), …, 𝓐(tn) ⇒ 𝓐(f(t1,t2,...,tn))  
Da verificare per ogni simbolo funzionale

58\. Principio di induzione strutturale su FBF di un linguaggio del I ordine  
Sia 𝓐 una proprietà sulle FBF, 𝓐(P) è verificata ∀P se:  
CB  
𝓐 è verificata su tutti gli atomi (⊥, A(t1,t2,...,tn))  
PI  
1\. ∀P1∈FBF: (𝓐(P1)⇒𝓐(¬P1))  
2\. ∀P1,P2∈FBF: (𝓐(P1),𝓐(P2) ⇒ 𝓐(P1∧P2),𝓐(P1∨P2),𝓐(P1⇒P2))  
3\. ∀P1∈FBF: (𝓐(P1)⇒𝓐(∀x:P1),𝓐(∃x:P1)) → da provare ∀x∈VAR

59\. Variabili libere e vincolate  
Sia t∈TER, l’insieme FV(t) è così definito:  
•) FV(x) \= {x} x∈VAR  
•) FV(c) \= ∅ c costante  
•) FV(f(t1,t2,...,tn)) \= FV(t1)UFV(t2)U…UFV(tn)

Sia P∈FBF, l’insieme FV(P) è così definito:  
•) FV(⊥) \= ∅  
•) FV(A(t1,t2,...,tn)) \= FV(t1)UFV(t2)U…UFV(tn)  
•) FV(¬P1) \= FV(P1)  
•) FV(P1∧P2) \= FV(P1)UFV(P2)  
•) FV(P1∨P2) \= FV(P1)UFV(P2)  
•) FV(P1⇒P2) \= FV(P1)UFV(P2)  
•) FV(∀x:P1) \= FV(P1) \\ {x}  
•) FV(∃x:P1) \= FV(P1) \\ {x}

Una P FBFsi dice chiusa se FV(P)=∅ altrimenti si dice aperta

60\. Regola di sostituzione per FBF del I ordine  
Siano s,t ∈TER allora s\[t/x\]∈TER si ottiene nel seguente modo:  
1\) s∈VAR, allora s\[t/x\] \=	s se s≠x;	t se s=x  
2\) s è una costante, s\[t/x\] \= s  
3\) s=f(t1,t2,...,tn), allora f(t1,t2,...,tn)\[t/x\] \= f(t1\[t/x\],t2\[t/x\],...,tn\[t/x\])

Siano P∈FBF e t∈TER, allora P\[t/x\] è definita nel seguente modo:  
1\) ⊥\[t/x\] \= ⊥  
2\) A(t1,t2,...,tn)\[t/x\] \=  A(t1\[t/x\],t2\[t/x\],...,tn\[t/x\])  
3\) (¬P)\[t/x\] \= ¬(P\[t/x\])  
4\) (P1∧P2)\[t/x\] \= (P1\[t/x\]) ∧ (P2\[t/x\])  
5\) (P1∨P2)\[t/x\] \= (P1\[t/x\]) ∨ (P2\[t/x\])  
6\) (P1⇒P2)\[t/x\] \= (P1\[t/x\]) ⇒ (P2\[t/x\])  
		    { ∀y:P1\[t/x\] se x≠y e y∉FV(t)  
7\) (∀y:P1)\[t/x\]= { ∀z:P1\[z/y\]\[t/x\] se x≠y e y∈FV(t)  
		    { ∀y:P1 se x=y  
8\) (∃y:P1)\[t/x\] analogo

61\. Semantica: interpretazione di un linguaggio del I ordine (definizione di ambiente e struttura)  
Una struttura 𝓐 è una coppia (D𝓐,I𝓐)  
D𝓐 è un insieme qualsiasi detto dominio  
I𝓐 è un assegnamento (o istanziazione) tc:

1. c è una costante, I𝓐(c)∈D𝓐  
2. f è un simbolo funzionale n-ario  
   I𝓐(f):D𝓐×D𝓐×…×D𝓐→D𝓐		funzione  
3. B è un predicato n-ario

I𝓐(B):D𝓐×D𝓐×…×D𝓐→{0,1}	relazione

Un ambiente per una struttura 𝓐 è una funzione da VAR a D𝓐  
Si indica con ENV𝓐 \=  {h| h: VAR→D𝓐}

Una interpretazione per un linguaggio ℒ del I ordine è una coppia (𝓐,h) dove 𝓐=(D𝓐,I𝓐) è una struttura e h∈ENV𝓐 è un ambiente

62\. Valore di verità di FBF e termini  
Sia P∈FBF e (𝓐,h) una interpretazione per ℒ.

Per ogni Termine che occorre in P, denotiamo il suo valore di verità in (𝓐,h) in questo modo ⟦•⟧: FBF→D𝓐

1) Se t=x∈VAR, ⟦x⟧ \= h(x)  
2) Se t è una funzione f(t1,t2,...,tn) n-aria allora  
   ⟦f⟧ \= I𝓐(f)(⟦t1⟧,⟦t2⟧,...,⟦tn⟧)

Per ogni FBF si definisce induttivamente il suo valore di verità in (𝓐,h) in questo modo ⟦•⟧: FBF→{0,1}

1) ⟦⊥⟧ \= 0  
2) ⟦A(t1,t2,...,tn)⟧ \= I𝓐(A)(⟦t1⟧,⟦t2⟧,...,⟦tn⟧)  
3) ⟦P1∧P2⟧ \= min(⟦P1⟧,⟦P2⟧)  
   ⟦P1∨P2⟧ \= max(⟦P1⟧,⟦P2⟧)  
   ⟦P1⇒P2⟧ \= max(1-⟦P1⟧,⟦P2⟧)  
   ⟦¬P1⟧ \= 1 \- ⟦P1⟧  
4) ⟦∀x:P1⟧ \= min(⟦P1⟧(h\[a/x\]): a∈D𝓐)	\= min { ⟦P1⟧ dove h\[a/x\] }  
   ⟦∃x:P1⟧ \= max(⟦P1⟧(h\[a/x\]): a∈D𝓐)	    a∈D𝓐

63\. Nozioni di soddisfacibilità, verità, validità, falsità, e contraddittorietà per FBF del I ordine  
Sia P∈FBF  
•) P è soddisfatta in 𝓐 rispetto ad h, se ⟦P⟧=1			(𝓐,h)⊨P  
•) P è soddisfacibile in 𝓐 se ∃h tc (𝓐,h)⊨P  
•) P è vera in 𝓐 se ∀h si ha (𝓐,h)⊨P				𝓐⊨P  
•) P è soddisfacibile se ∃𝓐 tc P è soddisfacibile in 𝓐  
•) P è valida se è vera ∀𝓐						⊨P  
•) P è falsa in 𝓐 sse non è soddisfacibile in 𝓐:  
	se ¬∃h tc (𝓐,h)⊨P						𝓐¬⊨P  
•) P è contraddittoria se è falsa ∀𝓐				¬⊨P  
