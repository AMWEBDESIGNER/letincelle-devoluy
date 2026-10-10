# L’Étincelle — maquette indépendante

Site vitrine statique pour **L’Étincelle**, restaurant de village à Agnières-en-Dévoluy.

## Vérification et sources

- Activité : Tripadvisor contient des retours datés de mars et juillet 2026 ; Petit Futé et la liste officielle des restaurants/bars du Dévoluy, crawlée le mois dernier, citent l’établissement.
- Sources : [Tripadvisor](https://www.tripadvisor.fr/Restaurant_Review-g10717361-d1153512-Reviews-L_etincelle-Le_Devoluy_Hautes_Alpes_Provence_Alpes_Cote_d_Azur.html), [liste Le Dévoluy](https://www.ledevoluy.com/ete/je-suis-sur-place-2/se-regaler-2/les-restaurants-et-bars-2/), [Petit Futé](https://www.petitfute.com/v33214-agnieres-en-devoluy-05250/c1165-restaurants/).
- Logo : aucun fichier logo exploitable avec droit de réutilisation explicite n’a été trouvé ; signature provisoire à remplacer par l’actif autorisé.
- Visuels : images Unsplash sous licence, liées dans le HTML et non représentatives de l’établissement.

## Liens

- GitHub : https://github.com/AMWEBDESIGNER/letincelle-devoluy
- Pages : https://letincelle-devoluy.pages.dev

## Parcours livré

L’accueil est complété par `experience.html` et `infos.html`, avec une présentation de la table, l’ambiance, l’itinéraire et les points à confirmer. Confirmer carte, contacts, horaires, identité graphique et médias avec le restaurant avant utilisation commerciale. Maquette indépendante.

## Motion design et provenance du code

Animations réalisées en CSS vanilla, avec respect de `prefers-reduced-motion`, et une révélation progressive inspirée du pattern public [Scroll animation: IntersectionObserver and CSS](https://codepen.io/oscar-jite/pen/qBzwOVq). La logique reste locale, légère et adaptée à l’identité de chaque établissement ; aucune dépendance payante ni contenu généré n’est requis.

## Informations pratiques livrées

`site-enhance.js` ajoute sur l’accueil un bloc dédié à l’adresse, aux horaires, aux services, au téléphone et à l’itinéraire, ainsi qu’un footer local complet. Les informations signalées « à confirmer » doivent être validées par l’établissement avant mise en production commerciale.
