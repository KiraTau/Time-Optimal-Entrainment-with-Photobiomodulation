Here are the tables of the parameters of the hybrid dynamical system model.
The first table shows all the parameters in Equations 3 to 9 in the paper.
| Parameter | Value | Parameter | Value |
| :--- | :--- | :--- | :--- |
| $\mu$ | $0.13 h^{-1}$ | $k_c$ | $0.4h$ |
| $q$ | $1/3$ | $\tau_x$ | $24.2h$ |
| $k$ | $0.55h^{-1}$ | $G$ | $33.75$ |
| $\alpha_0$ | $0.05 h^{-1}$ | $p$ | $0.5$ |
| $I_0$ | $9500 \textrm{ lux}$ | $\gamma$ | $0.0075h^{-1}$ |
| $\tau_m$ | $1/360 h$ | $v_{mv}$ | $1.8 mVs$ |
| $A_m$ | $1.3 mV$ | $\tau_v$ | $1/360 h$ |
| $v_{vm}$ | $2.1 mVs$ | $v_{vc}$ | $3.37 mVs$ |
| $v_{vh}$ | $1.01 mVnM^{-1}$ | $A_v$ | $-10.2 mV$ |
| $Q_{max}$ | $100 s^{-1}$ | $\theta$ | $10 mV$ |
| $V_{m,{\rm th}}$ | $-3.785 mV$ | $\sigma$ | $3 mV$ |
| $c_{x}$ | $0.8$ | $c_{x_c}$ | $-0.16$ |
| $\mu_H$ | $4.2 nMs$ | $\chi$ | $45 h$ |

$V_1$ and $V_2$ are polynomials. 

$$ V_1(D_v) = 3.5702 \frac{\exp(-40 (D_v -1.45))-\exp(40 (D_v-1.45))}{\exp(-40 (D_v -1.45))+\exp(40 (D_v-1.45))} + \sum_{i = 0}^5 a_i D_v^i$$

$$ V_2(D_v) = \begin{cases}
  \sum_{i = 0}^{5} b_i D_v^i , &D_v \leq 2.46,\\
  \sum_{i = 0}^{11} c_{i} D_v^i, &2.46 < D_v \leq 2.66,\\
  1.04, & D_v > 2.66.
\end{cases}$$

The parameters of $V_1$ and $V_2$ are in the following table:
| Parameter | Value | Parameter | Value |
| :--- | :--- | :--- | :--- |
| $a_0$ | $-3.2369$ | $a_1$ | $-3.9232$ |
| $a_2$ | $9.2384$ | $a_3$ | $-7.3438$ |
| $a_4$ | $2.0482$ | $a_5$ | $-0.1964$ |
| $b_0$ | $1.1236$ | $b_1$ | $-0.3960$ |
| $b_2$ | $0.8783$ | $b_3$ | $-1.0640$ |
| $b_4$ | $0.5328$ | $b_5$ | $-0.0982$ |
| $c_0$ | $1.2155 \cdot 10^7$ | $c_1$ | $-2.5973 \cdot 10^7$ |
| $c_2$ | $2.2560 \cdot 10^7$ | $c_3$ | $-1.0007 \cdot 10^7$ |
| $c_4$ | $2.2781 \cdot 10^6$ | $c_5$ | $-2.0589 \cdot 10^5$ |
| $c_6$ | $-1.0268 \cdot 10^4$ | $c_7$ | $6.7223 \cdot 10^3$ |
| $c_8$ | $-3.4379 \cdot 10^3$ | $c_9$ | $1.2007 \cdot 10^3$ |
| $c_{10}$ | $-217.0005$ | $c_{11}$ | $16.6128$ |