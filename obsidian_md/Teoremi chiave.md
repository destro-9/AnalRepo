# Cauchy
1) $\exists \lambda \in \mathbb{R} : lim_{x\to x_{0}}f(x)=\lambda$
2) $\forall\epsilon>0 \exists W\in\mathbb{U}_{x_{0}}: \forall x,y\in A -\{x_{0}\}(x,y \in W \implies |f(x)-f(y)|<\epsilon)$
Le due sono equivalenti

# Rolle
Sia $a,b \in \mathbb{R}$ , $a<b$ , ed$f \in C([a,b])$
Inoltre $f$ derivabile in $]a,b[$
Se $f(a)=f(b) \implies \exists c \in ]a,b[ : f^I(c)=0$
Quindi se la funzione fra $a$ e $b$ non cresce o decresce allora  $\exists c \in ]a,b[$ tale che $f^I(c)=0$

# LaGrange (valor medio)
Questo è un caso particolare del teorema di Cauchy
Roll dice $\exists c$, invece LaGrange spiega come trovare $c\in]a,b[$
Sia $a,b \in \mathbb{R}$ , $a<b$ 
$f \in C([a,b])$
Sia $f:[a,b]\to\mathbb{R}$
Inoltre $f$ derivabile in $]a,b[$
$\exists c \in ]a,b[$ tale che $\frac{f(b)-f(a)}{b-a}=f^I(c)$

# Convessità
$f$ convessa$\iff$$f^I(x)$ monotona crescente
$f$ convessa$\iff$$f^{II}(x)>0$
$f$ convessa$\iff$$f(x)\geq f(x_0)+f^I(x_0)(x-x_0)$    $\forall x_{0}\in I$    ($I$ intervallo non banale)

