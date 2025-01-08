# Estructura de Proyecto

<details>
<summary>📁 .git</summary>

- 📄 `COMMIT_EDITMSG`
- 📁 config
  - 📄 `description`
- 📄 `FETCH_HEAD`
- 📄 `HEAD`
- 📁 hooks
  - 📄 `applypatch-msg.sample`
  - 📄 `commit-msg.sample`
  - 📄 `fsmonitor-watchman.sample`
  - 📄 `post-update.sample`

</details>

- 📄 `.htaccess`

<details>
<summary>📁 CERTIFICADOS</summary>

- 📄 `SOA.pdf`

</details>

<details>
<summary>📁 cv</summary>

- 📄 `20231224_224610 (2).png`
- 📄 `cv.html`

</details>

<details>
<summary>📁 img</summary>

- 📄 `1.jpg`
- 📄 `AplicacionDePrestamos.png`
- 📄 `KadeScreen.png`
- 📄 `PortalCapacitacion.png`

</details>

- 📄 `index.html`
- 📄 `root.py`
- 📄 `style.css`

## Styles

```css
/* General styles */
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f9;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

/* Container for the file structure */
.container {
    width: 80%;
    max-width: 900px;
    margin: 20px auto;
    padding: 20px;
    background-color: #ffffff;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
}

/* Title */
h1 {
    text-align: center;
    color: #333;
}

/* List styles */
.file-structure {
    list-style-type: none;
    padding-left: 20px;
}

.folder {
    color: #2c6b2f;
    font-weight: bold;
}

.file {
    color: #555;
}

.folder > ul {
    margin-left: 20px;
}

/* Hover effect for files and folders */
.folder:hover, .file:hover {
    color: #1e5c2c;
    cursor: pointer;
}

/* Optional: add icons for folder and file types */
.folder:before {
    content: "📁 ";
    font-size: 1.2em;
}

.file:before {
    content: "📄 ";
    font-size: 1.2em;
}
