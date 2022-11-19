## Cauchy
1) $\exists \lambda \in \mathbb{R} : lim_{x\to x_{0}}f(x)=\lambda$
2) $\forall\epsilon>0 \exists W\in\mathbb{U}_{x_{0}}: \forall x,y\in A -\{x_{0}\}(x,y \in W \implies |f(x)-f(y)|<\epsilon)$
Le due sono equivalenti

## Rolle
Sia $a,b \in \mathbb{R}$ , $a<b$ , ed$f \in C([a,b])$
Inoltre $f$ derivabile in $]a,b[$
Se $f(a)=f(b) \implies \exists c \in ]a,b[ : f^I(c)=0$
Quindi se la funzione fra $a$ e $b$ non cresce o decresce allora  $\exists c \in ]a,b[$ tale che $f^I(c)=0$

## LaGrange (valor medio)
Questo è un caso particolare del teorema di Cauchy
Roll dice $\exists c$, invece LaGrange spiega come trovare $c\in]a,b[$
Sia $a,b \in \mathbb{R}$ , $a<b$ 
$f \in C([a,b])$
Sia $f:[a,b]\to\mathbb{R}$
Inoltre $f$ derivabile in $]a,b[$
$\exists c \in ]a,b[$ tale che $\frac{f(b)-f(a)}{b-a}=f^I(c)$

## Compattezza
A compatto $\iff$ A chiuso e limitato
E se per ogni successione puoi estrarre una sottosuccessione di A
N.B. A chiuso $\iff$ A = chiusura di A

## A aperto
$\implies \mathbb{R}$ \ $A$ chiuso 

## Continuita'
1) Se $x_{0} \not\in D(A) \implies f$ continua in $x_0$
2) Se $x_{0} \in D(A) \implies f$ continua in $x_{0}\iff \lim_{x\to x_0}f(x)=f(x_0)$

## Bolzano-Weierstrass (successioni)
Ogni successione reale limitata ammette una sottosucessione convergente. Formalizzato:
$\forall \{a_n\}_{n\in\mathbb{N}}\subseteq \mathbb{R}, \exists M>0:|a_{n}|\leq M, \forall n \in \mathbb{N}$

## Bolzano
Siano $a,b\in \mathbb{R}, a<b$. 
$a,b$ di segni opposti ( $f(a)\cdot f(b) \leq 0$ )
$\implies \exists x_{0}\in [a,b]:f(x_0)=0$

## Weierstrass
Sia $(X,d)$ uno spazio metrico compatto (limitato e chiuso). Ogni funzione $f\in C(X)$ ($f$ continua) ammette MAX e MIN assoluti

## Derivazius
$A\subseteq\mathbb{R}, f:A\to\mathbb{R}, x_{0} \in A\cap D(A)$
$Rg(x_0)(x)=\frac{f(x)-f(x_0)}{x-x_0}$
$f$ si dice derivabile in $x_0$ se $\exists \lambda \in \mathbb{R}$ tale che
$$\lambda=\lim_{x\to x_0}Rg(x_0)(x)=\frac{f(x)-f(x_0)}{x-x_0}
$$
Il limite puo' essere riscritto come $h=x-x_0$
$$\lim_{x\to x_0}\frac{f(h+x_0)-f(x_0
)}{h}$$
## Convessità
$f$ convessa$\iff$$f^I(x)$ monotona crescente
$f$ convessa$\iff$$f^{II}(x)>0$
$f$ convessa$\iff$$f(x)\geq f(x_0)+f^I(x_0)(x-x_0)$    $\forall x_{0}\in I$    ($I$ intervallo non banale)

