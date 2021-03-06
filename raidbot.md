# Tutoriel Raidbots

## Simulation Craft c'est quoi?

Simulation Craft permet de simuler n'importe quel personnage dans n'importe quelle situation.

Il est extrêmement utile pour optimiser son personnage mais comprend aussi quelques inconvénients. Difficile à prendre en main et consomme énormément de ressources CPU notamment.


## Et Raidbots?

Gomme tout les inconvénients de Simulation Craft.<br />
C'est un service hébergé en "cloud"! Avec une interface user-friendly et des calculs fait à distance.


## Les liens importants

Le site <a href="https://www.raidbots.com" target="_blank">raidbots.com</a>.

L'<a href="https://www.curseforge.com/wow/addons/simulationcraft" target="_blank">addon Simulationcraft</a>, indispensable pour faire un copier/coller de son perso dans raidbots. Il suffit de taper /simc en jeu pour faire apparaitre les paramètres à copier dans raidbots.

---

---

## Quick sim

<a id="quick_sim" href="https://www.raidbots.com/simbot/quick" target="_blank">Par ici!</a>

Pas besoin de se prendre la tête, une fois le personnage importé on clique sur **Run quick sim** et pouf! :boom: On a le DPS *théorique* de notre personnage.

### Les paramètres intéressants

**Durée du combat**<br />
On peut faire varier la durée du combat avec **Fight Length**, essayer avec 1 minute par exemple pour tester le burst.

**Nombre de cible**<br />
On peut faire varier le nombre de boss de 1 à 5 avec **Number of Bosses**. Très utile pour le multi-dot ou le cleave.

**Style du combat**<br />
Sur **Fight Style** on a le choix entre :
- Patchwerk (mono-cible bête et méchant)
- Hectic Add Cleave (rajoute des phases d'AOE)
- Light ou Heavy Movement (rajoute des déplacements)
- Helter Skelter (rajoute des pauses).

---

---

## Stat weights

<a id="stat_weights" href="https://www.raidbots.com/simbot/stats" target="_blank">Par ici!</a>

Affiche le nombre de DPS gagné par point de stat.

Par exemple sur mon druide feral  :smirk_cat: :

| stat | dps |
|-------|--------|
| Agi | 26.95 |
| Vers | 25.92 |
| Crit | 23.78 |
| Mastery | 21.73 |
| Haste | 16.13 |

Mon personnage va gagner 26 DPS par point de polyvalence, puis 24 par point de critique...<br />
Je vais donc devoir privilégier ces stats.

> Pour calculer les stats il faut remonter le nombre d'**Itérations** à 50 000 sinon le calcul ne sera pas assez précis.

---

---

## Top Gear

<a id="top_gear" href="https://www.raidbots.com/simbot/topgear" target="_blank">Par ici!</a>

Permet de trouver quel ensemble d'objet rapport le plus de DPS.

On selectionne les objets qu'on veut mettre dans la comparaison, puis dans la partie **Gems/Enchants** on rentre les gemmes et enchantements qu'on utilise habituellement.

Bouton **Find top gear** puis on le laisse mouliner.

`Exemple de résultat :`
![screenshot]({{ "/raidbots__compare_gear.PNG" | absolute_url }})

---

---

## Gear Compare

<a id="gear_compare" href="https://www.raidbots.com/simbot/gear" target="_blank">Par là!</a>

La fonction **Gear Compare** permet de comparer rapidement n'importe quel loot (même ceux qu'on a pas dans son sac contrairement à Top Gear cité plus haut).

Pareil que les fonctions précédentes, on rentre d'abord les informations de son perso.
Puis on peut ensuite rentrer un ou plusieurs **Gearset** contenant eux même un ou plusieurs **Item**. Pour cela on clique sur **Add gearset** et **Add item**.

`Interface :`
![screenshot]({{ "/img/raidbots/trinket_compare.PNG" | absolute_url }})

On peut par exemple simuler rapidement un objet en raid, ici on rentre le nom de l'objet en Anglais, *Golga...* Puis on clique sur **Compare Items**

`Résultats :`
![screenshot]({{ "/img/raidbots/trinket_compare_result.PNG" | absolute_url }})


---

---

> version 0.2 - patch 7.3
