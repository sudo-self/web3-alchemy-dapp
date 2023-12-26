# <a href="https://quiet-horse-453a83.netlify.app/">CW3D Dapp Boilerplate For Netlify</a><br>
[![Netlify Status](https://api.netlify.com/api/v1/badges/575173a2-e88d-401c-856f-c90c66e05899/deploy-status)](https://app.netlify.com/sites/quiet-horse-453a83/deploys)
<img width="1440" alt="Screenshot 2023-12-26 at 2 52 15 AM" src="https://github.com/sudo-self/netlify-alchemy-dapp/assets/119916323/5f7682c0-cb85-4868-91b5-c8836fde7a1d">






This boilerplate has everything you need to start building a dapp:

- Next.js
- Wagmi Hooks
- Ethers.js
- Rainbowkit
- Alchemy SDK


The project supports all the major EVM chains:

 - Ethereum
 - Polygon
 - Polygon zkEVM
 - Arbitrum
 - Optimism




1. Start the local development server:
   ```
   yarn run dev
   ```

## Project Structure

The boilerplate project is a Next.js application with the following structure:

```
📦root
 ┣ 📂components
 ┃ ┣ 📂navigation
 ┃ ┃ ┗ 📜navbar.jsx
 ┃ ┗ 📜InstructionsComponent.jsx
 ┣ 📂layout
 ┃ ┗ 📜mainLayout.jsx
 ┣ 📂pages
 ┃ ┣ 📜_app.js
 ┃ ┗ 📜index.jsx
 ┣ 📂public
 ┃ ┗ 📜cw3d-logo.png
 ┣ 📂styles
 ┃ ┣ 📜Home.module.css
 ┃ ┣ 📜InstructionsComponent.module.css
 ┃ ┣ 📜Navbar.module.css
 ┃ ┗ 📜globals.css
 ┣ 📜.gitignore
 ┣ 📜README.md
 ┣ 📜next.config.js
 ┣ 📜package-lock.json
 ┗ 📜package.json
```

Start editing the `pages/index.jsx` file to customize the project according to your own needs!
