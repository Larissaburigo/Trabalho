**4.3.4 Estimativa de máxima verossimilhança**

Para estimar os parâmetros do modelo, adaptamos um algoritmo proposto por Anderson (1973). A log-verossimilhança para o modelo espacial linear T-Student é dado por

$L(\theta) = log(k_{n}(\eta)) K n ( eta)) - \frac{1}{2}log(\Sigma) - \frac {1}{2}(\eta)  (1 + n\eta) log(1 + c(\eta) \delta) $ 

**(4.4)**

com $log(k_{n}(\eta)) = \frac {\eta}{2} log (\frac {c(n)}{\pi}) + log \Gamma (\frac {1 + n\eta}{2\eta}) log \Gamma (\frac{1}{2\eta}) , \delta = (Y-X\beta)^{T} \Sigma - ^{-1} (Y - X\beta)$ e $c(\eta) = \eta/(1 -2\eta), 0 < \eta < \frac{1}{2}.$

Conforme o observado por Zellner (1976), a função log-verossimilhança (4.4) é uma função decrescente de \eta, e então não pode ser estimado por máximo verossimilhança. Veja também De Bastiani et al.(2015).

As funções escores para o modelo espacial linear T-Student são fornecidas por $U_{\theta}(\theta)$
