## Description
An API for that generates a custom welcome card.

## Params
**Key:**
- $\color{blue}{\text{Blue}}$ - Required.
- $\color{green}{\text{Green}}$ - Optional.

| Param | Type | Description |
| ----- | ----- | ----- |
| $\color{blue}{\text{?bg_type}}$ | Query | The type of background to use. Accepts 'image' and 'color'. |
| $\color{green}{\text{?bg_color}}$ | Query | A 24-bit HEX digit (with the #) that defined the background color of the card. Ignored if `bg_type` is 'image'. Required if `bg_type` is 'color' |
| $\color{green}{\text{?bg_url}}$ | Query | An image URL that defines the background image of the card. Ignored if `bg_type` is 'color'. Required if `bg_type` is 'image'. |
| $\color{blue}{\text{?text}}$ | Query | The text content of the card. |
| $\color{green}{\text{?text_color}}$ | Query | A 24-bit HEX digit (with the hash) that defines the color of the text. |
| $\color{blue}{\text{?avatar_url}}$ | Query | An image URL that defines the avatar image in the welcome image. |
| $\color{green}{\text{?avatar_color}}$ | Query | A 24-bit HEX digit (with the #) that defines the color of the avatar border. |

[!NOTE]
All params **must** be URI encoded.
