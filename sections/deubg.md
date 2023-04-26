
$$
\begin{aligned}
        p(y|\theta )=&\prod_{i=1}^N\dfrac{ \theta ^{y_i} }{ y_i! }e^{-\theta }\\
        p(\theta )\sim &\Gamma (\alpha,\beta )\\ 
        p(\tilde{y}|y)\propto&\int \dfrac{ \theta ^{\tilde{y}} }{ \tilde{y}! }e^{-\theta } \theta ^{\alpha -1}e^{-\beta \theta }\theta ^{N\bar{y}}e^{-N\theta }  \,\mathrm{d}\theta \\
        = & \dfrac{ 1 }{ \tilde{y}! }\int\theta ^{\alpha +N\bar{y}+\tilde{y} -1}e^{-(\beta+N +1)\theta }  \,\mathrm{d}\theta\\
        =&\dfrac{ 1 }{ \tilde{y}! }\dfrac{ \Gamma (\alpha +N\bar{y}+\tilde{y}) }{ (\beta+N +1)^{\alpha +N\bar{y}+\tilde{y}} } \\
        \sim &\binom{\alpha +N\bar{y}+\tilde{y}-1 }{\tilde{y}}\left( \dfrac{ \beta+N  }{ \beta+N +1 }  \right)^{\alpha +N\bar{y}}\left( \dfrac{ 1 }{ \beta+N +1 } \right)^{\tilde{y}}\\
        \sim & \mathrm{Neg}\text{-}\mathrm{Binom}(\alpha +N\bar{y}, \beta+N )
\end{aligned}
$$ 


