# Fichiers de traduction pour chillbot

Ce référentiel héberge les fichiers de traduction pour le bot Discord**Refroidissement**. Ces fichiers permettent à Chillbot d'offrir ses fonctionnalités en plusieurs langues et de permettre à la communauté de contribuer à améliorer les traductions.

## Structure de fichiers

Les fichiers de traduction sont dans**Json**format et organisé par code linguistique (par exemple,`en-US.json`,`fr-FR.json`).
Chaque fichier reflète la hiérarchie des modules, commandes et messages du bot.

**Exemple de structure:**

```json
{
  "pro": {
    "ftnl": {
      "chillbot": {
        "core": {
          "utility": {
            "commands": {
              "list": {
                "slash": {
                  "publics": {
                    "music": {
                      "PlayCmd": {
                        "action": {
                          "success": "🎵 %s, Successfully joined %s.",
                          "noPrime": "You can get 24/7 playback by voting for the bot here."
                        }
                      }
                    }
                  }
                }
              }
            }
          }
        }
      }
    }
  }
}
```

-   **Clés**Reflétez la structure des caractéristiques du bot.
-   **Valeurs**sont les chaînes à traduire, contenant parfois des variables (`%s`,`%d`, etc.).

## Comment contribuer

1.  **Choisissez ou créez le fichier de langue:**Si le fichier pour votre langue n'existe pas, copiez un fichier existant (par exemple,`en-US.json`) et le renommer avec le code linguistique approprié (par exemple,`fr-FR.json`).
2.  **Traduire les chaînes:**Remplacez chaque valeur par la traduction correcte. Assurez-vous de conserver les variables (`%s`,`%d`, etc.) dans leurs positions d'origine.
3.  **Maintenir la structure:**Ne modifiez pas la structure clé. Les clés manquantes ou renommées peuvent entraîner des erreurs pendant l'intégration.
4.  **Valider la syntaxe:**Utilisez un validateur JSON pour éviter les erreurs de mise en forme.

## Meilleures pratiques

-   **Variables dynamiques:**Assurer les variables (`%s`,`%d`, etc.) Restez au bon endroit dans la phrase.
-   **Emojis et liens:**Gardez les émojis, les liens ou les mentions de discorde présents dans les messages.
-   **Clarité et concision:**Utilisez des traductions claires et naturelles pour votre langue.

## Soumettre une traduction

1.  **Fourchette**ce référentiel.
2.  **Créer une branche** for your contribution.
3.  **Modifier ou ajouter**le fichier de traduction pertinent.
4.  **Ouvrir une demande de traction**avec une description claire de vos modifications.

## Exemple de messages à traduire

-   Succès ou messages d'erreur:`"success": "🎵 %s, Successfully joined %s."`
-   Descriptions de commande:`"description": "Starts playing music in voice channel"`
-   Étiquettes des boutones:`"supportButtonLabel": "Support"`

## Contact \\ & Support

Pour toute question ou suggestion, veuillez rejoindre le serveur Discord de support du bot ou ouvrir un problème dans ce référentiel.

* * *

Merci d'avoir aidé à rendre le chillbot accessible à tous!
