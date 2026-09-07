# 🌐 Géo-Géométrie & Symétrie Systémique : Le Modèle ABC - EF

> *« La géopolitique est emprisonnée dans le triangle ABC rectangle en B, mais la symétrie EF offre la clé de l'équilibre. »*

Bienvenue sur le dépôt officiel du projet **Géo-Géométrie**. Ce projet explore une modélisation conceptuelle, topographique et philosophique originale qui relie la géométrie des surfaces (rectangles, triangles rectangles, diagonales et hypoténuses) à la résolution des tensions géopolitiques contemporaines et aux systèmes de repérage spatiaux (GPS).

---

## 📐 1. Fondements Théoriques

Les structures de pouvoir traditionnelles se comportent souvent comme un système figé, enfermé dans l'implacabilité d'un triangle rectangle où l'angle droit en $B$ incarne le point de friction permanent, et la diagonale $AC$ l'hypoténuse de la confrontation.

### L'Équation Paramétrique
Le modèle introduit la relation interactive suivante :
$$\text{FOA} - \text{FE} = \text{AC}$$

* **$AC$** : La diagonale principale, représentant la tension ou la distance critique du système.
* **$FE$** : L'axe de coupe vertical intérieur, qui segmente l'espace.
* **$FOA$** : Le chemin orthogonal de liaison géométrique.

L'introduction de la **symétrie $EF$** permet de court-circuiter ce face-à-face binaire pour redéfinir un axe d'équilibre global.

---

## 📊 2. Visualisation et Simulation Python

Le script ci-dessous génère la représentation géométrique sous-jacente du modèle, illustrant le passage de la diagonale de tension ($AC$) à l'axe d'équilibre ($EF$).

```python
import matplotlib.pyplot as plt
import numpy as np

# Initialisation de la figure
fig, ax = plt.subplots(figsize=(8, 6))

# Tracé du rectangle géopolitique de base
rect = plt.Rectangle((0, 0), 4, 3, linewidth=2, edgecolor='#2b2d42', facecolor='#f8f9fa', label='Cadre Géopolitique (Rectangle)')
ax.add_patch(rect)

# Tracé de la diagonale AC (Tension/Conflit / Hypoténuse)
ax.plot([0, 4], [3, 0], color='#e63946', linewidth=2.5, label='Diagonale AC (Hypoténuse)')

# Tracé de l'axe de symétrie EF
ax.plot([2.5, 2.5], [0, 3], color='#2a9d8f', linewidth=2.5, linestyle='--', label='Axe EF (Symétrie/Équilibre)')

# Annotations des sommets et points clés
ax.text(-0.2, 3.1, 'A', fontsize=12, fontweight='bold', color='#1d3557')
ax.text(-0.2, -0.3, 'B (Pivot)', fontsize=12, fontweight='bold', color='#1d3557')
ax.text(4.1, -0.3, 'C', fontsize=12, fontweight='bold', color='#1d3557')
ax.text(2.5, -0.3, 'E', fontsize=12, fontweight='bold', color='#2a9d8f')
ax.text(2.5, 3.1, 'O/F', fontsize=12, fontweight='bold', color='#2a9d8f')

ax.set_xlim(-1, 5)
ax.set_ylim(-1, 4)
ax.set_aspect('equal')
ax.axis('off')
ax.legend(loc='upper right', frameon=True)
plt.title('Modélisation Géométrique : Le Système ABC et l\'Axe EF', fontsize=12, fontweight='bold', pad=20)

plt.savefig('geopolitics_geometry.png', dpi=300, bbox_inches='tight')
plt.show()
# 1. Cloner le dépôt
git clone [https://github.com/votre-nom/geo-symetrie-ef.git](https://github.com/votre-nom/geo-symetrie-ef.git)
cd geo-symetrie-ef

# 2. Installer les dépendances requises
pip install matplotlib numpy

# 3. Exécuter le script de visualisation
python script_visualisation.py
