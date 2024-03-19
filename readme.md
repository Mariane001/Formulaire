## Formulaire de contact <!-- en-tête -->

> **comment créer un formulaire**

> _Exemple de structure HTML_

```html
<fieldset >
            <legend>Remplir le formulaire</legend>
            <form action="https://www.google.com/search" method="get" target="_blank">
                <label for="query">Recherche</label>

                <div class="wrapper" role="group" aria-describedby="search submit >
                    <div id="search" class="search-input">
                        <input type="text" name="q" id="query" placeholder="search" aria-required="true" required>
                        <input type="submit" value="Envoyer">
                    </div>
                        <div id="submit"><button type="submit">Recherche</button></div>
                </div>
            </form>
        </fieldset>

```

> **Langages utilisés**

1. html
2. css


*   ![cover](./asset/undraw_education_f8ru.svg)
   [![forthebadge](https://forthebadge.com/images/featured/featured-uses-html.svg)](https://forthebadge.com)
