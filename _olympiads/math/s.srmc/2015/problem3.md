Пусть $B_n$ — множество всех последовательностей длины $n$, состоящих из нулей и единиц. Для каждых двух последовательностей $a,b \in B_n$ (не обязательно различных) определим строки $\varepsilon_0\varepsilon_1\varepsilon_2 \dots \varepsilon_n$ и $\delta_0\delta_1\delta_2 \dots \delta_n$ соотношениями $\varepsilon_0=\delta_0=0$ и 
$$
 \varepsilon_{i+1}=(\delta_i-a_{i+1})(\delta_i-b_{i+1}), \quad \delta_{i+1}=\delta_i+(-1)^{\delta_i}\varepsilon_{i+1} \quad (0 \leq i \leq n-1). 
$$
Пусть $w(a,b)=\varepsilon_0+\varepsilon_1+\varepsilon_2+\dots +\varepsilon_n$. Найдите $f(n)=\sum\limits_{a,b \in {B_n}} {w(a,b)} $.