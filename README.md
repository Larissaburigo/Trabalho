**4.3.4 Estimativa de máxima verossimilhança**

Para estimar os parâmetros do modelo, adaptamos um algoritmo proposto por Anderson (1973). A log-verossimilhança para o modelo espacial linear T-Student é dado por

$L(\theta) = log(k_{n}(\eta)) K n ( eta)) - \frac{1}{2}log(\Sigma) - \frac {1}{2}(\eta)  (1 + n\eta) log(1 + c(\eta) \delta) $ 

**(4.4)**

com $log(k_{n}(\eta)) = \frac {\eta}{2} log (\frac {c(n)}{\pi}) + log \Gamma (\frac {1 + n\eta}{2\eta}) log \Gamma (\frac{1}{2\eta}) , \delta = (Y-X\beta)^{T} \Sigma - ^{-1} (Y - X\beta)$ e $c(\eta) = \eta/(1 -2\eta), 0 < \eta < \frac{1}{2}.$

Conforme o observado por Zellner (1976), a função log-verossimilhança (4.4) é uma função decrescente de \eta, e então não pode ser estimado por máximo verossimilhança. Veja também De Bastiani et al.(2015).

As funções escores para o modelo espacial linear T-Student são fornecidas por $U_{\theta}(\theta) = (U^T_\beta, U^T_\phi)^T$, em que 

$U = \partial L (\theta) /\partial\beta = w(\delta) X^T \Sigma^-1\epsilon$ and $U_\phi=\partial L (\theta)/\partial\phi$,

com o j-ésimo elemento de $U_(\phi)$, dado por $U_(\phi)_(j) = U = \partial L (\theta)/\phi_j = -\frac{1}{2}$ tr
$(\Sigma^-1 (\partial \Sigma / \partial \phi_j)) + \frac{1}{2} w (\delta) \epsilon^T \Sigma^-{1} (\partial \Sigma/\partial\phi_J) \Sigma{^-1}_epsilon$, para j = 1, 2, w $(\delta) = (\frac{1+ \eta\eta}{\eta}) (\frac{c(\eta)}{1+c(\eta)\delta})$ e $\psi$ (x) é a função Digama.Nesse artigo, $\Sigma = \phi_1 I\eta + \phi_2 R$, então $\partial \Sigma/\partial \phi_1 = I\eta$ e $\partial \Sigma/ \partial \phi_2 = R $. Dado $\Sigma$, a função log-verossimilhança (4.4) é maximizada em 

$\hat{\beta} = (X^T \Sigma^{-1} X) ^{-1} X ^T \Sigma^{-1}Y$, 

e de $U_\phi =0$ tem-se que, 

$i)\phi 1 tr (\Sigma^{-1} \Sigma^{-1}) + \phi_2 tr (\Sigma^{-1} R \Sigma^{-1}) = w (\delta) \epsilon^T \Sigma^{-1} \Sigma^{-1} \epsilon$

$ii)\phi 1 tr (\Sigma^{-1} R (\Sigma^{-1}) + \phi_2 tr (\Sigma^{-1} R(\Sigma^{-1} R) = w (\delta) \epsilon ^T(\Sigma^{-1} R \Sigma^{-1} \epsilon)$



