# Doublons de booster

Petite app web installable (PWA) pour les boosters Pokémon japonais de la série MEGA :

- chance que le prochain paquet ne contienne que des doublons, selon les cartes déjà possédées par rareté ;
- nombre de paquets à ouvrir d'un coup pour que le paquet suivant ait 50 % de chances d'être 100 % doublons.

Le calcul est exact (inclusion-exclusion), les données des sets sont intégrées dans `index.html` et modifiables depuis l'app (section « Mettre à jour les données »).

## Installer sur Android

Ouvrir la page dans Chrome, puis menu ⋮ → « Installer l'application ». L'app fonctionne ensuite hors ligne.

## Mettre à jour

Modifier `index.html`, puis changer `VERSION` dans `sw.js` pour forcer le rafraîchissement du cache.
