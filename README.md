# tw-site
Website developed with TailwindCss.

Links from courses:
- Build a Modern Landing Page With Tailwind CSS [https://www.youtube.com/watch?v=00gyCtIQp8E](https://www.youtube.com/watch?v=00gyCtIQp8E)
- Tailwind playlist from The Net Ninja [https://www.youtube.com/playlist?list=PL4cUxeGkcC9ht1OMQPhBVKAb2dVLhg-MJ](https://www.youtube.com/playlist?list=PL4cUxeGkcC9ht1OMQPhBVKAb2dVLhg-MJ)

### Commands

Create a package.json file using npm `docker run -v "$PWD":/app -w /app node:lts npm init -y`

Install Tailwind `docker run -v "$PWD":/app -w /app node:lts npm i tailwindcss`

Create configuration file as per [documentation](https://tailwindcss.com/docs/installation#create-your-configuration-file) `docker run -v "$PWD":/app -w /app node:lts npx tailwindcss init --full`

Build css `docker run -v "$PWD":/app -w /app node:lts npm run build-css`