# Il teorema di Morse-Sard

Un punto critico di una funzione $f:U \rightarrow \mathbb{R}^n$ di classe $C^k$,  $k\ge 1$,    con $U$ aperto di $\mathbb{R}^m$,  è un punto in cui   la matrice Jacobiana di $f$ non ha rango massimo. 
Il Teorema di Morse-Sard afferma che l'immagine dei punti critici è un insieme di misura di Lebesgue $n$-dimensionale nulla se sussiste la seguente relazione tra $k$, $m$ e $n$: 
```math
 k\ge \max\{m-n+1,1\}.
```

Tale risultato è ottimale, come attestato da un controesempio di H. Whitney.

Il  Teorema di Morse-Sard è così chiamato, in quanto A.P. Morse nel  1939 pubblica la versione per funzioni a valori reali, successivamente  generalizzata da A. Sard   nel 1942, a funzioni a valori vettoriali; a tale risultato ci si riferisce spesso con la dicitura di $Lemma \  di \  Sard$.

Vi sono due casi di particolare rilevanza: il caso  $m=n$, e il caso $n=1$. Nel primo caso, il Teorema di Morse-Sard può essere così enunciato:

```math
 Sia \ U \ un \  aperto \  di \ \mathbb{R}^n \  e \  sia \ f:U \rightarrow \mathbb{R}^n \  una \  funzione \  di \  classe \ C^1(U). \ Allora \  \mathcal{L}^n(f(crit(f)) = 0 \  dove 
```

```math
crit(f) = \\{ x \in U \  : \  \det Df(x)=0 \\}.
```






%Il primo è il Teorema di Morse-Sard per funzinoi $f \in C^1(\mathbb{R}^n, \mathbb{R}^n)$, che dice che se $f:U \rightarrow \mathbb{R}^n$ è una funzione di classe $C^1(U)$, dove $U$ è un aperto di $\mathbb{R}^n$, allora $\operatorname{vol}(f(crit(f)) = 0$ dove $crit(f) = \{ x \in U \, : \, Df(x) \text{ non ha rango massimo}\}$,  vedi Teorema \ref{t:MSnnC1}.

Il secondo caso, riguardante funzioni a valori reali, è il Teorema di Morse, che possiamo  enunciare nel  modo seguente:

\medbreak

{\em Sia $U$  un aperto di $\mathbb{R}^m$ e sia  $f:U \rightarrow \mathbb{R}$ una funzione di classe $C^m(U)$.}

{\em Allora ${\mathcal{L}^1}(f(crit(f)) = 0$ dove 
\[crit(f) = \{ x \in U \, : \, \nabla f(x)=0\}.\]}
 In particolare, da questo risultato si deduce che quasi ogni insieme  di livello di $f$ è una varietà di classe $C^m$. 

\medbreak


Il capitolo centrale di questa tesi è il Capitolo \ref{cap:2}, in cui diamo una dimostrazione del Teorema di Morse-Sard. Il caso $m<n$ non è difficile da trattare, ma decisamente più complicata è la trattazione del caso  $m\ge n$. Di questo caso, forniremo  la dimostrazione  di 
Moreira e Ruas pubblicata nel 2009 in  \cite{Moreira}, la quale fa uso del  cosiddetto {\em Curve selection lemma}, si veda \cite{Milnor}. 




%Il secondo è il Teorema di Morse-Sard per funzioni $f \in C^m(\mathbb{R}^m, \mathbb{R})$, e dice che se $f:U \rightarrow \mathbb{R}$ è una funzione di classe $C^m(U)$, dove $U$ è un aperto di $\mathbb{R}^m$, allora $\operatorname{vol}(f(C(f)) = 0$ dove $C(f) = \{ x \in U \, : \, Df(x) = 0\}$. Questo risultato prende il nome di Teorema di Morse, vedi Teorema \ref{t:morseRn}.




%Questi Teoremi sono in realtà due casi particolari del più generale Teorema di Morse-Sard, si veda Teorema \ref{t:misf(c(f))=0}. Esso afferma che per $f \in C^{m-n+1}(U, \mathbb{R}^n)$, con $m \ge n$ e $U$ aperto di $\mathbb{R}^m$, allora $\operatorname{vol}(f(crit(f)))=0$ dove $crit(f) = \{ x \in U \, : \, Df(x) \text{ non ha rango massimo}\}$.



%Alla fine del secondo capitolo tratteremo anche il Teorema di Morse-Sard nel caso di $f \in C^1(\mathbb{R}^m, \mathbb{R}^n)$ con $m < n$, si veda Teorema \ref{t:MSm<n2}.

\medbreak

Nel caso $m=n$, l'ipotesi $f\in C^1$ richiesta dal Teorema di Morse-Sard non è ottimale. Infatti, D.E.  Varberg nel 1966 in \cite{Varberg} dimostra che è possibile indebolire la regolarità di $f$ richiedendo la sola  differenziabilità. 
  Di tale teorema forniamo la dimostrazione originale di Varberg, la quale  poggia anche su risultati di Flett \cite{flett}. Essa costituisce il terzo capitolo della tesi. 


%Tale Teorema afferma che se $f:U \rightarrow \mathbb{R}^n$, con $U$ aperto di $\mathbb{R}^n$, è una funzione differenziabile su $U$, allora $\operatorname{vol}(f(crit(f)) = 0$, dove $crit(f) = \{ x \in U \, : \, Df(x) \text{ non ha rango massimo}\}$. Di questo risultato, forniamo la dimostrazione originale, la quale poggia anche su risultati di Flett \cite{flett}.

\medbreak
A concludere l'elaborato è una significativa  applicazione del Teorema di Morse-Sard: la formula di coarea per  funzioni sommabili a valori reali.   Mettiamo qui in evidenza il rilevante caso particolare:  se   $f\in L^1(\mathbb{R}^n)$, allora 
\[
\int_{\mathbb{R}^n} f(x)\, dx =\int_{0}^{\infty}\left(\int_{\partial B(0,t)}f(x)\, d\sigma(x)
\right)dt
\]
dove $B(0,t)$ sta a indicare la palla di $\mathbb{R}^n$ centrata nell'origine e di raggio $t$. 

