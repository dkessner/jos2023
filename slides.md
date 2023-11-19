
class: title

.content[
# Contact juggling and rotations in 3D

<hr/>

## Joy of ~~Science~~ Math 2023
## Darren Kessner

<br/> <br/> <br/> <br/>
<br/> <br/> <br/> <br/>
<br/>

<img src="ei_icon.png" width="20%"/>  

### <br/> 
### &nbsp; &nbsp; Ellison Institute   
### &nbsp; &nbsp; of Technology



]

---

layout:true

class: normal

.footer[
Ellison Institute  of Technology
]

---

class: normal

# 3D space
<hr/>


.row[

.column[

<br/>
<br/>
<br/>
![](pix/axis.png)

]

.column[

<br/><br/>
<br/><br/>
<br/><br/>

$$
\begin{align}
R_z \circ R_y \circ R_x &= I \\\\
\\\\
R_y \circ R_x &= R_z
\end{align}
$$

]

]

---

class: normal

# Composing rotations

<hr/>

.row[
.column[
### 2D

$ R_a \circ R_b = R_c $

<br/>
<br/>
<img src="pix/rotation_2d.png" width="80%"/>
]

.column[

### 3D

$ R_a \circ R_b = \text{rotation?} $

<br/>
<br/>
<br/>
<img src="pix/rotation_3d.png" width="80%"/>


]

]

---

class: normal

# Linear algebra

<hr/>

.row[
.column[

$$
R_x = \begin{bmatrix}
1 & 0 & 0 \\\\
0 & -1 & 0 \\\\
0 & 0 & -1
\end{bmatrix}
$$

<br/>

$$
R_y = \begin{bmatrix}
-1 & 0 & 0 \\\\
0 & 1 & 0 \\\\
0 & 0 & -1
\end{bmatrix}
$$

<br/>

$$
R_z = \begin{bmatrix}
-1 & 0 & 0 \\\\
0 & -1 & 0 \\\\
0 & 0 & 1
\end{bmatrix}
$$



]

.column[

$$
R_x \begin{pmatrix} a \\\\ b \\\\ c \end{pmatrix}
 = \begin{pmatrix} a \\\\ -b \\\\ -c \end{pmatrix}
$$

<br/> <br/>
<br/> <br/>

$R_x$ flips $y$ and $z$ coordinates.  

$R_y$ flips $x$ and $z$ coordinates.  

<hr/>

$R_z$ flips $x$ and $y$ coordinates.  

]

]

---

class: normal

# Geometric algebra

<hr/>

.row[
.column[

<img src="pix/e1e2e3.png" width="80%"/>

]

.column[

Rotation about $z$-axis is represented by the
_bivector_ $e_1 e_2$.

<br/>

$$
e_1 e_1 = e_2 e_2 = e_3 e_3 = 1
$$

<br/>

$$
(e_1 e_2)(e_2 e_3) = e_1 e_3
$$

<br/>

Quaternions:   

$$
i j = k
$$

]

]

