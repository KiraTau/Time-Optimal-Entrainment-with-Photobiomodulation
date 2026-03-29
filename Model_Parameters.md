Here are the tables of the parameters of the hybrid dynamical system model.
The first table shows all the parameters in Equations 3 to 9 in the paper.
Parameter,Value,Parameter,Value
μ,0.13h−1,kc​,0.4h
q,1/3,τx​,24.2h
k,0.55h−1,G,33.75
α0​,0.05h−1,p,0.5
I0​,9500 lux,γ,0.0075h−1
τm​,1/360h,vmv​,1.8mVs
Am​,1.3mV,τv​,1/360h
vvm​,2.1mVs,vvc​,3.37mVs
vvh​,1.01mVnM−1,Av​,−10.2mV
Qmax​,100s−1,θ,10mV
"Vm,th​",−3.785mV,σ,3mV
cx​,0.8,cxc​​,−0.16
μH​,4.2nMs,χ,45h

$V_1$ and $V_2$ are polynomials. 
$$ V_1(D_v) = 3.5702 \frac{\exp(-40 (D_v -1.45))-\exp(40 (D_v-1.45))}{\exp(-40 (D_v -1.45))+\exp(40 (D_v-1.45))} + \sum_{i = 0}^5 a_i D_v^i$$

$$ V_2(D_v) = \begin{cases}
  \sum_{i = 0}^{5} b_i D_v^i , &D_v \leq 2.46,\\
  \sum_{i = 0}^{11} c_{i} D_v^i, &2.46 < D_v \leq 2.66,\\
  1.04, & D_v > 2.66.
\end{cases}$$

The parameters of $V_1$ and $V_2$ are in the following table:
Parameter,Value,Parameter,Value
a0​,−3.2369,a1​,−3.9232
a2​,9.2384,a3​,−7.3438
a4​,2.0482,a5​,−0.1964
b0​,1.1236,b1​,−0.3960
b2​,0.8783,b3​,−1.0640
b4​,0.5328,b5​,−0.0982
c0​,1.2155⋅107,c1​,−2.5973⋅107
c2​,2.2560⋅107,c3​,−1.0007⋅107
c4​,2.2781⋅106,c5​,−2.0589⋅105
c6​,−1.0268⋅104,c7​,6.7223⋅103
c8​,−3.4379⋅103,c9​,1.2007⋅103
c10​,−217.0005,c11​,16.6128