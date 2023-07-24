# IA Cluster : trame du document scientifique en latex/pandoc


Permet de générer un pdf dans le format attendu par l'ANR pour l'appel à manifestation d'intérêt [IA Cluster 2023](https://anr.fr/fr/france-2030/france2030/call/ia-cluster-poles-de-recherche-et-de-formation-de-rang-mondial-en-intelligence-artificielle-app/)
en utilisant comme source du texte au format markdown (et du latex)
et en utilisant pandoc pour obtenir un pdf.

Il est nécessaire d'installer la [police de caractères Marianne](https://www.systeme-de-design.gouv.fr/elements-d-interface/fondamentaux-de-l-identite-de-l-etat/typographie/).

Pour compiler le document

`pandoc --pdf-engine=xelatex --template clusteria.latex.format example.md -o example.pdf`

