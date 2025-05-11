# Translation Files for ChillBot

This repository hosts the translation files for the Discord bot **ChillBot**. These files enable ChillBot to offer its features in multiple languages and allow the community to contribute to improving translations.

## File Structure

Translation files are in **JSON** format and organized by language code (e.g., `en-US.json`, `fr-FR.json`).
Each file reflects the hierarchy of the bot's modules, commands, and messages.

**Example structure:**

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

- **Keys** reflect the structure of the bot’s features.
- **Values** are the strings to be translated, sometimes containing variables (`%s`, `%d`, etc.).


## How to Contribute

1. **Choose or create the language file:**
If the file for your language does not exist, copy an existing file (e.g., `en-US.json`) and rename it with the appropriate language code (e.g., `fr-FR.json`).
2. **Translate the strings:**
Replace each value with the correct translation. Be sure to keep variables (`%s`, `%d`, etc.) in their original positions.
3. **Maintain the structure:**
Do not alter the key structure. Missing or renamed keys may cause errors during integration.
4. **Validate the syntax:**
Use a JSON validator to avoid formatting errors.

## Best Practices

- **Dynamic variables:** Ensure variables (`%s`, `%d`, etc.) remain in the correct place within the sentence.
- **Emojis and links:** Keep any emojis, links, or Discord mentions present in the messages.
- **Clarity and conciseness:** Use clear and natural translations for your language.


## Submitting a Translation

1. **Fork** this repository.
2. **Create a branch** for your contribution.
3. **Edit or add** the relevant translation file.
4. **Open a Pull Request** with a clear description of your changes.

## Example Messages to Translate

- Success or error messages:
`"success": "🎵 %s, Successfully joined %s."`
- Command descriptions:
`"description": "Starts playing music in voice channel"`
- Button labels:
`"supportButtonLabel": "Support"`


## Contact \& Support

For any questions or suggestions, please join the bot’s support Discord server or open an issue in this repository.

---

Thank you for helping make ChillBot accessible to everyone!
