# Budget Tracker

**🔗 Accéder à l'app : <a href="https://antoningd19.github.io/budget-tracker/" target="_blank" rel="noopener">antoningd19.github.io/budget-tracker</a>**

PWA de suivi de budget mensuel personnel, pensée pour voir chaque jour ce que je dépense par catégorie et ce que je mets de côté. Page HTML autonome, sans dépendance ni build.

## Fonctionnalités

- **Mis de côté ce mois** : la carte principale affiche l'épargne du mois (lignes Épargne + reste positif en fin de mois) et le taux d'épargne, avec revenus, dépenses et investissement (suivi à part, jamais compté comme épargne)
- **Catégories** : Logement, Abonnement, Charges fixes, Alimentation, Déplacement, Épargne, Plaisir, Imprévus, Investissement
- **Enveloppes** Alimentation, Déplacement et Plaisir : dépensé / reste, barre de progression et reste par jour jusqu'à la fin du mois, visibles même enveloppe fermée ; un dépassement réduit l'épargne du mois
- **Sous-catégories Plaisir** (restaurants, bars, fast-food, sport, achats plaisir, cadeaux) avec le dépensé de chacune ; seul le budget global de l'enveloppe est fixé
- **Ajout rapide** : bouton « + » pour saisir une dépense d'enveloppe en deux gestes, avec annulation
- **Plan épargne octobre → avril** : total mis de côté, objectif global et détail par mois, objectifs modifiables dans l'app (octobre et novembre en bonus)
- **Évolution** des derniers mois avec l'écart par catégorie par rapport au mois précédent
- Lignes récurrentes recopiées par « Créer le mois suivant »
- Réorganisation par glisser-déposer, édition des libellés et montants directement dans la liste
- L'app s'ouvre sur le mois en cours
- Installation en PWA (icône, écran d'accueil iOS/Android)

## Utilisation

Ouvrir le lien ci-dessus dans Safari, puis Partager → « Sur l'écran d'accueil ».

Pour lancer en local : ouvrir `index.html` directement dans un navigateur.

Les données sont sauvegardées dans le `localStorage` du navigateur, propres à chaque appareil et à chaque icône d'écran d'accueil ; rien n'est envoyé à un serveur. Supprimer l'icône de l'écran d'accueil efface ses données.
