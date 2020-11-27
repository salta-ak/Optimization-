# Optimization
Problem Formulation

---



ai = supply i ; 

bj = demand  at station j ; 

dij = distance between plant i and station j (Haversin distance km)

>  haversine distance (calculated from given  x and y coordinates only for AI95) , BUT this coordinates doesn't take into account the physical road barriers such as  traffic, rivers, lakes, buildings etc. In optimization problems it is better to use the road lenth.


cij = F⋅dij  shipping cost  between plant i  and station j

xij  = amount of petroleum to ship from plant i  to station j 

where xij ≥0 , for all i,j

Observe supply limit at plant i : ∑j xij≤ai for all i

Satisfy demand at station j:∑i xij≥bj for all j  
> **Mimize ∑i ∑j cij*xij**








