
# Conversion rad <-> deg:
## $deg = (rad*180)/π$ ​

## $rad = (deg*π)/180$ ​

# Trigo

$\cos(\theta)=\frac{\text{adjacent}}{\text{hypoténuse}}$

$\sin(\theta)=\frac{\text{opposé}}{\text{hypoténuse}}$

$x=L\cos(\theta)$

$y=L\sin(\theta)$

$(x,y)=(L\cos(\theta),L\sin(\theta))$

# Vecteurs

$\vec{a}=(a_x,a_y)$

$\vec{b}=(b_x,b_y)$

$\vec{a}+\vec{b}=(a_x+b_x,\ a_y+b_y)$

$\vec{a}-\vec{b}=(a_x-b_x,\ a_y-b_y)$

$\vec{a}+\vec{b}+\vec{c}=(a_x+b_x+c_x,\ a_y+b_y+c_y)$

$\vec{a}\cdot\vec{b}=a_xb_x+a_yb_y$ 

$\vec{a}\times\vec{b}=(0,\ 0,\ a_xb_y-a_yb_x)$

$|\vec{a}|=\sqrt{a_x^2+a_y^2}$

### Vecteurs / composantes

$\vec{a}=(a_x,a_y)$

$\vec{b}=(b_x,b_y)$

$\vec{a}+\vec{b}=(a_x+b_x,\ a_y+b_y)$

$\vec{a}-\vec{b}=(a_x-b_x,\ a_y-b_y)$

$k\vec{a}=(ka_x,\ ka_y)$

### Norme

$|\vec{a}|=\sqrt{a_x^2+a_y^2}$

$|\vec{b}|=\sqrt{b_x^2+b_y^2}$

$|\vec{a}|^2=a_x^2+a_y^2$

$|\vec{a}|^2=\vec{a}\cdot\vec{a}$

$|k\vec{a}|=|k||\vec{a}|$

### Produit scalaire

### $\vec{a}\cdot\vec{b}=a_xb_x+a_yb_y=|\vec{a}||\vec{b}|\cos(\theta)$

### $\cos(\theta)=\frac{\vec{a}\cdot\vec{b}}{|\vec{a}||\vec{b}|}$

$\vec{a}\cdot\vec{b}=\vec{b}\cdot\vec{a}$

$\vec{a}\perp\vec{b}\iff\vec{a}\cdot\vec{b}=0$ (orthogonaux)

### Signes avec produit scalaire

$(-\vec{a})\cdot\vec{b}=-(\vec{a}\cdot\vec{b})$

$\vec{a}\cdot(-\vec{b})=-(\vec{a}\cdot\vec{b})$

$(-\vec{a})\cdot(-\vec{b})=\vec{a}\cdot\vec{b}$

$-\vec{a}\cdot\vec{b}-\vec{b}\cdot\vec{a}=-2(\vec{a}\cdot\vec{b})$

car

$\vec{a}\cdot\vec{b}=\vec{b}\cdot\vec{a}$

### Formules très utiles avec les normes

$|\vec{a}+\vec{b}|^2=|\vec{a}|^2+2(\vec{a}\cdot\vec{b})+|\vec{b}|^2$

$|\vec{a}-\vec{b}|^2=|\vec{a}|^2+|\vec{b}|^2-2(\vec{a}\cdot\vec{b})$

Donc le fameux terme :

$-2(\vec{a}\cdot\vec{b})$

vient du développement de :

$|\vec{a}-\vec{b}|^2$

Et si $\vec{a}\perp\vec{b}$ :

$|\vec{a}+\vec{b}|^2=|\vec{a}|^2+|\vec{b}|^2$

C'est simplement Pythagore.

### Produit vectoriel en 2D

### $\vec{a}\times\vec{b}=a_xb_y-a_yb_x$

### ou en 3D :

### $\vec{a}\times\vec{b}=(0,0,a_xb_y-a_yb_x)$

### Passer angle + longueur → composantes

$a_x=|\vec{a}|\cos(\theta)$

$a_y=|\vec{a}|\sin(\theta)$

$\vec{a}=(|\vec{a}|\cos(\theta),\ |\vec{a}|\sin(\theta))$

### Vecteur unitaire

$\hat{a}=\frac{\vec{a}}{|\vec{a}|}$

$|\hat{a}|=1$

### Deux astuces à retenir

Si tu vois $|\vec{a}-\vec{b}|^2$, pense directement :

$|\vec{a}|^2-2\vec{a}\cdot\vec{b}+|\vec{b}|^2$

Si tu cherches l'angle entre deux vecteurs, pense directement :

$\theta=\arccos\left(\frac{\vec{a}\cdot\vec{b}}{|\vec{a}||\vec{b}|}\right)$