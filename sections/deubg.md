
    \begin{align*}
        F_k\to F ,\quad H_k\to H,\quad Q_k\to Q ,\quad R_k\to R 
    \end{align*}
    then Kalman filter and variance estimation have asymptotic form by solving
    \begin{align*}
        P_{\infty}=&F \left(P_\infty-P_\infty H'\left(H P_\infty H
        +R \right)^{-1}H P_\infty\right)F '+Q \\
        K_\infty = &P_\infty H '\left(H P_\infty H '\right)^{-1}
    \end{align*}