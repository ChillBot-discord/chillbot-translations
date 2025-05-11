# Archivos de traducción para Chillbot

Este repositorio aloja los archivos de traducción para Discord Bot**Botín**. Estos archivos permiten que Chillbot ofrezca sus características en múltiples idiomas y permitan que la comunidad contribuya a mejorar las traducciones.

## Estructura de archivo

Los archivos de traducción están en**Json**formato y organizado por código de idioma (por ejemplo,`en-US.json`,`fr-FR.json`).
Cada archivo refleja la jerarquía de los módulos, comandos y mensajes del bot.

**Estructura de ejemplo:**

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

-   **Llaves**reflejar la estructura de las características del bot.
-   **Valores**son las cadenas a traducir, a veces que contienen variables (`%s`,`%d`, etc.).

## Cómo contribuir

1.  **Elija o cree el archivo de idioma:**Si el archivo para su idioma no existe, copie un archivo existente (por ejemplo,`en-US.json`) y cambie el nombre con el código de idioma apropiado (por ejemplo,`fr-FR.json`).
2.  **Traducir las cuerdas:**Reemplace cada valor con la traducción correcta. Asegúrese de mantener variables (`%s`,`%d`, etc.) en sus posiciones originales.
3.  **Mantener la estructura:**No altere la estructura clave. Las teclas faltantes o renombradas pueden causar errores durante la integración.
4.  **Validar la sintaxis:**Use un validador JSON para evitar el formateo de errores.

## Mejores prácticas

-   **Variables dinámicas:**Asegurar variables (`%s`,`%d`, etc.) permanecer en el lugar correcto dentro de la oración.
-   **Emojis y enlaces:**Mantenga cualquier emojis, enlaces o menciones de discordia presentes en los mensajes.
-   **Claridad y concisión:**Use traducciones claras y naturales para su idioma.

## Presentación de una traducción

1.  **Tenedor**este repositorio.
2.  **Crear una rama**para su contribución.
3.  **Editar o agregar**el archivo de traducción relevante.
4.  **Abra una solicitud de extracción**con una descripción clara de sus cambios.

## Mensajes de ejemplo para traducir

-   Mensajes de éxito o error:`"success": "🎵 %s, Successfully joined %s."`
-   Descripciones de comando:`"description": "Starts playing music in voice channel"`
-   Etiquetas de botones:`"supportButtonLabel": "Support"`

## Contacto \\ & Support

Para cualquier pregunta o sugerencia, únase al servidor Discord Support del Bot o abra un problema en este repositorio.

* * *

¡Gracias por ayudar a que Chillbot sea accesible para todos!
