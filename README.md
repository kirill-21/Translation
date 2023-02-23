### Translation rules

- The original translation were made for **English, Ukrainian and Russian** languages, all other languages are translated with the help of volunteers. If you want to check the correctness of some phrase, refer to that languages translations first.
- User should be addressed informally (like **Du** in Deutch, like **Ти** in Ukrainian,  like **Ты** in Russian, ...).
- Its better to adjust the translation length to approximately match the translation line on other languages.
- Keep plurals and nouns as they are, and do not incldude articles like **the, ein, eine, etc.**, unless they are included to the english translation! Example: 
```
 'OneMinute': {
    languageEn: 'minute', -> one minute left until download process is ended 
    languageRu: 'минута', -> до конца загрузки осталась одна минута
    languageUa: 'хвилина' -> до кінця завантаження залишилася одна хвилина,
    languagePl: 'minuta',
    languageDe: "Minute"
  },
  'OneMinuteNoun': {
    languageEn: 'minute', -> he played the game for one minute,
    languageRu: 'минуту', -> он наиграл в игру одну минуту,
    languageUa: 'хвилину', -> він награв у гру одну хвилину
    languagePl: 'minutę',
    languageDe: "Minute"
  },
  'Reviews': {
    languageEn: 'review', -> 1 review
    languageRu: 'отзыв',  -> 1 отзыв
    languageUa: 'відгук', -> 1 відгук
    languagePl: 'recenzja',
    languageDe: "Rezension"
  },
  'ReviewsSecond': {
    languageEn: 'reviews', -> 2-4 reviews
    languageRu: 'отзыва', -> 2-4 отзыва
    languageUa: 'відгука', -> 2-4 відгука
    languagePl: 'recenzje',
    languageDe: "Rezensionen"
  },
  'ReviewsThird': {
    languageEn: 'reviews', -> 5-10 reviews
    languageRu: 'отзывов', -> 5-10 отзывов
    languageUa: 'відгуків', -> 5-10 відгуків
    languagePl: 'recenzji',
    languageDe: "Rezensionen"
  },
```
- Do not translate inserted objects like this one {game}. You can change its order but do not touch the object itself. Example:
```
  'ShowAnswers': {
    languageEn: 'Show {number} {answers}',
    languageRu: 'Показать {number} {answers}',
    languageUa: 'Показати {number} {answers}',
    languagePl: 'Pokaż {number} {answers}',
    languageDe: "{number} {answers} anzeigen"
  },
```
- If you see blocks similrar to this one `<style=lighten>` then the following word must go without spaces between the style markup identifier and the word. Example: `<style=lighten>game`
- If you are not sure what the phrase meen then try looking onto the phrases above/beneath it to follow it's context. You can also try looking for the phrase inside the app/installer to check where it's used.
- If you see many `\n` symbols inside the translation phrase than its probably used inside the tooltip and you should arrange these symbols so that each line corresponds to the previous one in its in length. Example of usage:
```
'OpticalDescription': {
    languageEn:
        "Optical modifications are designed to help\nyou to enjoy the game's beauty by changing\nit's visual component(models of items, players,\nthe surrounding world, etc.).",
    languageRu:
        'Визуальные модификации предназначены для того,\nчтобы помочь тебе насладиться всей красотой игры,\nизменяя её визуальные компоненты(модельки\nпредметов, персонажей, окружающего мира и т.д.).',
    languageUa:
        'Візуальні модифікації призначені для того, щоб\nдопомогти тобі насолодитися всією красою гри,\nзмінюючи її візуальні компоненти(модельки\nпредметів, персонажів, навколишнього світу і т.д.).',
    languagePl:
        'Modyfikacje wizualne mają pomóc ci cieszyć się\ncałym pięknem gry, zmieniając jej aspekty\nwizualne (modele obiektów, postaci, otaczającego\nświata itp.).',
    languageDe:
        "Visuelle Modifikationen sollen Ihnen helfen, die ganze\nSchönheit des Spiels zu genießen, indem seine visuellen\nKomponenten geändert werden (Modelle von Objekten,\nCharakteren, der umgebenden Welt usw.)."
  },
```
[![Example](https://raw.githubusercontent.com/kirill-21/Translation/main/images/newLineExample.png "Example")](https://raw.githubusercontent.com/kirill-21/Translation/main/images/newLineExample.png "Example")

- If you see words wrapped with «» then wrap the translated analogues with exectly the same quotation marks.
- Do not remove 🙁, ❎, 🖱, ... symbols from you translation analogues.
- Please, do not try to use any translators(google, yandex, prompt, bing, etc.) to translate the app. It will look funny for native speakers who will see such translation in the app.
- You can use the issues tab for reporting about mistakes in current translation or create a pull request with fixes and descriptions if you want!

[![issues](https://img.shields.io/github/issues/pandao/editor.md.svg "issues")](https://github.com/kirill-21/Translation/issues "issues")
