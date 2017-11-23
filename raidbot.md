# Tuto Raidbots

## Simulation Craft c'est quoi?

Simulation Craft permet de simuler n'importe quel personnage dans n'importe quelle situation.

Il est extrêmement utile pour optimiser son personnage mais comprend aussi quelques inconvénients. Difficile à prendre en main et consomme énormément de ressources CPU notamment.


## Et Raidbots?

Gomme tout les inconvénients de Simulation Craft?
C'est un service hébergé en "cloud"! Avec une interface user-friendly et des calculs fait à distance.


## Les liens importants

Le site [raidbots.com](https://www.raidbots.com).

L'[addon Simulationcraft](https://www.curseforge.com/wow/addons/simulationcraft), indispensable pour faire un copier/coller de son perso dans raidbots. Il suffit de taper /simc en jeu pour faire apparaitre les paramètres à copier dans raidbots.


## Quick sim

[Par ici!](https://www.raidbots.com/simbot/quick)

Pas besoin de se prendre la tête, une fois le personnage importé on clique sur Run quick sim et pouf! :boom: On a le DPS *théorique* de notre personnage.

### Les paramètres intéressants

Durée du combat
<br />
On peut faire varier la durée du combat avec **Fight Length**, essayer avec 1 minute par exemple pour tester le burst.

Nombre de cible
<br />
On peut faire varier le nombre de boss de 1 à 5 avec **Number of Bosses**. Très utile pour le multi-dot ou le cleave.

Style du combat
<br />
Sur **Fight Style** on a le choix entre :
- Patchwerk (mono-cible bête et méchant)
- Hectic Add Cleave (pour rajouter des phases d'AOE)
- Light ou Heavy Movement (pour rajouter des déplacements)
- Helter Skelter (pour rajouter des pauses).


## Stat weights

[Par ici!](https://www.raidbots.com/simbot/stats)

Affiche le nombre de DPS gagné par point de stat. (Pour calculer les stats il faut remonter le nombre d'**Itérations** à 50 000 sinon le calcul ne sera pas assez précis.)

Par exemple sur mon druide feral :tiger: :

| stat | dps |
|-------|--------|
| Agi | 26.95 |
| Vers | 25.92 |
| Crit | 23.78 |
| Mastery | 21.73 |
| Haste | 16.13 |

Mon perso va gagner 27 dps par point d'agilité, puis 26 par point de polyvalence... Je devrais donc privilégier ces stats.


## Top Gear

[Par ici!](https://www.raidbots.com/simbot/topgear)

Permet de trouver quel ensemble d'objet rapport le plus de DPS.

On selectionne les objets qu'on veut mettre dans la comparaison, puis dans la partie **Gems/Enchants** on rentre les gemmes et enchantements qu'on utilise habituellement.

Bouton **Find top gear** puis on le laisse mouliner.

`
Exemple de résultat :
`
![screenshot]({{ "/raidbots__compare_gear.PNG" | absolute_url }})

