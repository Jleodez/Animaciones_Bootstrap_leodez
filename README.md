# Leodez Studio Static Website

This repository contains the source code for **Leodez Studio**, a showcase website for 3D modeling, 3D printing, and NFT mini worlds. The site is entirely static, built with plain HTML and a small custom CSS file alongside [Bootstrap](https://getbootstrap.com/) and [Animate.css](https://animate.style/).

## Project Structure

```
/                - Project root with `index.html`
/css/            - Custom stylesheet (`estilo.css`)
/img/            - Images and icons
/pages/          - Additional HTML pages
/wireframe/      - PDF wireframes for design reference
```

The repository also contains some `desktop.ini` files from Windows; these are unnecessary for the website and can be removed.

## Key Files

- **index.html** – Landing page with a navigation bar, carousel, and links to the service pages. It loads Bootstrap and Animate.css from CDNs and references `./css/estilo.css` for custom styles.
- **pages/Impresión3d.html** – Page describing 3D printing services.
- **pages/Modelado_3d_Realidad_Aumentada.html** – Details 3D modeling and augmented reality work.
- **pages/Mini_Mundos_NFT.html** – Overview of the Mini Worlds NFT project.
- **css/estilo.css** – Custom color palette, gradients, and layout helper classes used by all pages.
- **wireframe/** – Mobile and desktop design mockups in PDF format.

## Running the Site

Because the site is static, you only need a web browser to view it. You can open `index.html` directly, or serve the project with a simple HTTP server:

```bash
# From the repository root
python3 -m http.server
```

Then visit `http://localhost:8000` in your browser.

## Suggestions for Contributors

- **Clean Up:** Delete the `desktop.ini` files to keep the repository tidy.
- **Reuse Components:** The header and footer are repeated across pages. Consider extracting them into templates if you plan to add more pages.
- **Learn Bootstrap:** Understanding Bootstrap's grid and components will make customizing layouts much easier.
- **Accessibility:** Review alt text on images and ensure semantic HTML for better accessibility.

Feel free to open issues or submit pull requests with improvements.
