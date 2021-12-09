# tw-site
Website developed with TailwindCss

### Commands

Create a package.json file using npm `docker run -v "$PWD":/app -w /app node:lts npm init -y`

Install Tailwind `docker run -v "$PWD":/app -w /app node:lts npm i tailwindcss`

Create configuration file as per [documentation](https://tailwindcss.com/docs/installation#create-your-configuration-file) `docker run -v "$PWD":/app -w /app node:lts npx tailwindcss init --full`

Build css `docker run -v "$PWD":/app -w /app node:lts npm run build-css`