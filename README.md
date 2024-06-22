# Vencord CSS
Discord CSS snippets made for use with Vencord.

## Available snippets
### Markdown Header Killer
This disables markdown headers which can get spammy and annoying

Before:

![image](https://github.com/nin0-dev/vencord-css/assets/75569739/ea3e78b4-f977-4ab1-80f9-f2b1f90e875a)

After:

![image](https://github.com/nin0-dev/vencord-css/assets/75569739/455cdbfc-7d67-41a8-a2b0-a296a2e275ba)

```css
@import url(https://nin0-dev.github.io/vencord-css/md-header-killer.css)
:root {
    /* This'll be the prefix before a markdown header, leave empty to remove */
    --header-override-prefix: "🔼 "
}
```
