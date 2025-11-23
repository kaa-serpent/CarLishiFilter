# 🚗 Filtre Lishi pour Clés de Véhicule

Ceci est un outil web simple pour filtrer et trouver rapidement des informations sur les clés de véhicule, en particulier les codes d'outils Lishi, en se basant sur la marque et le modèle du véhicule.

Les données proviennent de EntrepriseAnonyme et sont basées sur leur document PDF accessible au public.

---

## ✨ Fonctionnalités

*   **Filtrage par Marque et Modèle**: Recherchez facilement un véhicule par sa marque et son modèle.
*   **Suggestions Autocomplétées**: Les champs de recherche fournissent des suggestions pour vous aider à trouver rapidement ce que vous cherchez.
*   **Informations Détaillées**: L'outil affiche divers codes d'ébauches de clés et d'autres données pertinentes pour le véhicule sélectionné.
*   **Lien Direct**: Un lien direct vers la page du produit sur EntrepriseAnonyme est fourni pour l'outil Lishi correspondant.

---

## 🚀 Utilisation

1.  Ouvrez le fichier `index.html` dans votre navigateur web.
2.  Commencez à taper une marque de véhicule dans le champ de saisie **"Marque (brand)"**.
3.  Sélectionnez une marque parmi les suggestions ou tapez-la entièrement.
4.  Tapez un modèle dans le champ de saisie **"Modèle (model)"**. Les suggestions seront affinées en fonction de la marque sélectionnée.
5.  Les informations sur la clé du premier véhicule correspondant seront affichées sous forme de carte.

---

## 📊 Données

Les données sont stockées dans le fichier `data.csv`.

| Colonne             | Description                       |
| ------------------- | --------------------------------- |
| `marque_vehicule`   | Marque du véhicule                |
| `modele_vehicule`   | Modèle du véhicule                |
| `lishi`             | Code de l'outil Lishi             |
| `t3`                | Code T3                           |
| `ic_card`           | Code de la carte IC               |
| `silca_card`        | Code de la carte Silca            |
| `silca_key_blank`   | Ébauche de clé Silca              |
| `ilca_key_blank`    | Ébauche de clé Ilca               |
| `ilco_key_blank`    | Ébauche de clé Ilco               |
| `keyline_key_blank` | Ébauche de clé Keyline            |
| `jma_key_blank`     | Ébauche de clé JMA                |

---

### ⚠️ Important ⚠️ :

Ce projet fournit uniquement l’interface web pour filtrer les données.

Les données EntrepriseAnonyme (Lishi, clés, etc.) ne sont pas incluses.

Toute utilisation publique ou commerciale des données EntrepriseAnonyme requiert une autorisation écrite de leur part.

Ce dépôt est destiné à un usage local et privé uniquement.

un jeux de donnée fictif est disponible `data-test.csv` pour la structure du projet

Pour une utilisation optimal merci de changer la valeur de l'url ```const baseURL = 'https://lien-fictif.com/';``` dans `index.html` par l'url du site.

## 📦 Dépendances

Cet outil utilise [PapaParse](https://www.papaparse.com/) pour l'analyse des fichiers CSV, qui est inclus via un lien CDN. Aucune installation locale n'est requise.

---

## 📄 Licence

Ce projet est sous licence selon les termes de la [Licence MIT](LICENSE).