# CW3D Dapp Boilerplate For Netlify<br>
[![Netlify Status](https://api.netlify.com/api/v1/badges/575173a2-e88d-401c-856f-c90c66e05899/deploy-status)](https://app.netlify.com/sites/quiet-horse-453a83/deploys)
This boilerplate is set up to be deployed on Netlify and you can directly deploy this project by clicking the button below:





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



To get started with this boilerplate, you'll need to have the following software installed on your local machine:

- [Node.js](https://nodejs.org/)
- [Yarn](https://yarnpkg.com/)
- [Git](https://git-scm.com/)

### Installation

1. Clone the repository to your local machine:
   ```
   git clone https://github.com/alchemyplatform/netlify-alchemy-dapp-boilerplates.git
   ```
2. Navigate to the project directory:
   ```
   cd netlify-alchemy-dapp-boilerplates
   ```
3. Install the required dependencies:
   ```
   yarn install
   ```

### Running the Project

1. Start the local development server:
   ```
   yarn run dev
   ```
2. Open your browser and navigate to [`http://localhost:3000/`](http://localhost:3000/) to view the dApp in action.

### Deploying to Netlify

This boilerplate is set up to be deployed on Netlify and you can directly deploy this project by clicking the button below:

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/alchemyplatform/netlify-alchemy-dapp-boilerplates)

 If you prefer to deploy it manually, you can follow these steps:

1. Sign up for a Netlify account at [netlify.com](https://www.netlify.com/) if you don't already have one.
2. Install the Netlify CLI:
   ```
   npm install -g netlify-cli
   ```
3. Run the following command to deploy your dApp to Netlify:
   ```
   netlify deploy
   ```
4. Follow the prompts and provide the required information. Your dApp will be deployed and accessible via a unique URL.

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
