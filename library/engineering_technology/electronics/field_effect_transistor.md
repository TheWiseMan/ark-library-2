
Le field effect transistor (FET) est un transistor unipolaire (un seul type de porteurs de charges mobiles).
- MOS à appauvrissement (canal implanté ou diffusé)
- MOS à enrichissement (pas de canal initialement -> normally off)

Caractérisation technologique
Semiconducteur :
- Dopage substrat
- Mobilité
- Permittivité
- Affinité électronique

Isolant :
- Epaisseur
- Permittivité

# MOS à enrichissement

Transistor bloqué lorsque $V_(GSub)<V_T$
Transistor passant lorsque $V_(GSub)>=V_T$

## Caractéristique de sortie

$I_(DS)=f(V_(DS))$


Théorie simplifiée : $I_(DS) = mu_0 (W/L)C_I[(V_(GS)-V_(T))V_(DS)-1/2V^2_(DS)]$

On retrouve à partir de cette formule la conduction en régime ohmique ($V_(DS)<V_(GS)-V_T$), en négligeant le terme en $V_(DS)^2$.
On retrouve la conduction en régime saturé car alors $I_(DS)$ est constant à sa valeur pour $V_(DS)=V_P=V_(GS)-V_(T)$ (tension de pincement)

## Régime de pincement

En réalité, pour $V_(DS)>V_P$, le transistor est soumis à l'effet de modulation de la longueur de canal.
En effet, augmenter la tension drain-source déplace le point de pincement vers la source (dans le cas d'un NMOS), ce qui réduit la longueur effective du canal à $L^'=L-Delta L$.

On note alors $lambda=(DeltaL)/(LV_(DS))$, et sous l'hypothèse $Delta LL)$,

$I_(DS)=1/2mu_0C_I(V_(GS)-V_T)^2(1+lambda V_(DS)$ en saturation

# Sources

https://www.allaboutcircuits.com/technical-articles/mosfet-channel-length-modulation/
