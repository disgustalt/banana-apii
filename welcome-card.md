## Description
An API that generates a custom welcome card.

## Params
**Key:**
- $\color{blue}{\text{Required}}$
- $\color{green}{\text{Optional}}$

| Param | Type | Description |
| :--- | :--- | :--- |
| `?bg_type` | $\color{blue}{\text{Query}}$ | The type of background. Accepts `image` or `color`. |
| `?bg_color` | $\color{green}{\text{Query}}$ | A 24-bit HEX digit (with #). Required if `bg_type` is `color`. |
| `?bg_url` | $\color{green}{\text{Query}}$ | An image URL. Required if `bg_type` is `image`. |
| `?text` | $\color{blue}{\text{Query}}$ | The text content of the card. |
| `?text_color` | $\color{green}{\text{Query}}$ | A 24-bit HEX digit (with #) for the text. |
| `?avatar_url` | $\color{blue}{\text{Query}}$ | The URL for the avatar image. |
| `?avatar_border`| $\color{green}{\text{Query}}$ | A 24-bit HEX digit (with #) for the border. |

> [!NOTE]
> All parameters **must** be URI encoded.
