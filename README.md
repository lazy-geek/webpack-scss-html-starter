# Webpack + SCSS + Html Starter
Webpack configured for compiling and bundling SCSS with Html (without Javascript Code)

## Project Structure

```
- src/
    - assets
    - scss/
        - style.scss
    index.html
```


- Place all html files directly inside `src` folder
- Place all assets (fonts, images etc.)  inside `src/assets` folder. The directory structure of inside doesn't matter e.g : `assets/images` for images, `assets/icons` for icons etc.
- Place all scss files  inside `src/scss` folder, make sure to import every scss file you write in `style.scss` file.

## Development

```bash
npm run dev
```

## Build

```bash
npm run build
```