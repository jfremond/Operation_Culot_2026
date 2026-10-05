# Le diable se cache dans les détails

## Objectif
Trouver l'auteur du site Internet d'Horizon Souverain 2035

## Résolution
On commence par aller sur le site d'[Horizon Souverain](https://horizon-souverain-2035.eu/).

En regardant les pages du site nous n'avons pas d'information, mais on peut
déposer une candidature.

En regardant le code source de la page de candidature, nous trouvons ceci:

```javascript
doc.setProperties({
          title: "Profil d'investisseur - " + ref,
          subject: 'Horizon Souverain 2035 - Profil d\'investisseur',
          author: 'THEREALBBKM',
          creator: 'THEREALBBKM',
          keywords: 'Horizon Souverain 2035, profil, THEREALBBKM'
        });
```

Nous voyons donc que l'auteur de ce site est THEREALBBKM.

Le flag pour ce challenge est: THEREALBBKM
