# Il teorema di Morse-Sard

Un punto critico di una funzione $f:U \rightarrow \mathbb{R}^n$ di classe $C^k$,  $k\ge 1$,    con $U$ aperto di $\mathbb{R}^m$,  è un punto in cui   la matrice Jacobiana di $f$ non ha rango massimo. 
Il Teorema di Morse-Sard afferma che l'immagine dei punti critici è un insieme di misura di Lebesgue $n$-dimensionale nulla se sussiste la seguente relazione tra $k$, $m$ e $n$: 
```math
 k\ge \max\{m-n+1,1\}.
```
Tale risultato è ottimale, come attestato da un controesempio di H. Whitney.

Il  Teorema di Morse-Sard è così chiamato, in quanto A.P. Morse nel  1939 pubblica la versione per funzioni a valori reali, successivamente  generalizzata da A. Sard   nel 1942, a funzioni a valori vettoriali; a tale risultato ci si riferisce spesso con la dicitura di Lemma di Sard.

Vi sono due casi di particolare rilevanza: il caso  $m=n$, e il caso $n=1$. Nel primo caso, il Teorema di Morse-Sard può essere così enunciato:

$$Sia \ U \ un \  aperto \  di \ \mathbb{R}^n \  e \  sia \ f:U \rightarrow \mathbb{R}^n \  una \  funzione \  di \  classe \ C^1(U). \ Allora \  \mathcal{L}^n(f(crit(f)) = 0 \  dove$$
$$crit(f) = \\{ x \in U \  : \  \det Df(x)=0 \\}.$$

Il secondo caso, riguardante funzioni a valori reali, è il Teorema di Morse, che possiamo  enunciare nel  modo seguente:

$$Sia  \  U \   un \  aperto \  di \  \mathbb{R}^m \  e \  sia \  f:U \rightarrow \mathbb{R} \  una \  funzione \  di \  classe \  C^m(U). Allora  \  \mathcal{L}^1(f(crit(f)) = 0 \  dove$$
$$crit(f) = \\{ x \in U \  : \  \nabla f(x)=0\\}.$$

In particolare, da questo risultato si deduce che quasi ogni insieme  di livello di $f$ è una varietà di classe $C^m$. 

Il capitolo centrale di questa tesi è il Capitolo 2, in cui diamo una dimostrazione del Teorema di Morse-Sard. Il caso $m<n$ non è difficile da trattare, ma decisamente più complicata è la trattazione del caso  $m\ge n$. Di questo caso, forniremo  la dimostrazione  di Moreira e Ruas pubblicata nel 2009, la quale fa uso del  cosiddetto Curve Selection Lemma.

Nel caso $m=n$, l'ipotesi $f\in C^1$ richiesta dal Teorema di Morse-Sard non è ottimale. Infatti, D.E.  Varberg nel 1966 ndimostra che è possibile indebolire la regolarità di $f$ richiedendo la sola  differenziabilità. 
Di tale teorema forniamo la dimostrazione originale di Varberg, la quale  poggia anche su risultati di Flett. Essa costituisce il terzo capitolo della tesi. 

A concludere l'elaborato è una significativa  applicazione del Teorema di Morse-Sard: la formula di coarea per  funzioni sommabili a valori reali. Mettiamo qui in evidenza il rilevante caso particolare:  se   $f \in L^1(\mathbb{R}^n)$, allora 

$$\int_{\mathbb{R}^n} f(x)\, dx =\int_{0}^{\infty}\left(\int_{\partial B(0,t)}f(x)\, d\sigma(x) \right)dt$$

dove $B(0,t)$ sta a indicare la palla di $\mathbb{R}^n$ centrata nell'origine e di raggio $t$. 
