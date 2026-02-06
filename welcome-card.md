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
| `?avatar_border`| $\color{green}{\text{Query}}$ | A 24-bit HEX digit (with #) for the avatar border. |

> [!NOTE]
> All parameters **must** be URI encoded.



## Preview
![Preview Lmao](https://dash.bananabot.qzz.io/api/welcome-card?bg_type=image&bg_color=%23ffffff&avatar_url=https%3A%2F%2Fi.ibb.co%2FzTWF0St6%2Frickroll-roll.gif&text=hai&bg_url=https%3A%2F%2Fi.ibb.co%2FzTWF0St6%2Frickroll-roll.gif)
