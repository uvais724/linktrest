# Blinks

Blinks is a Nuxt-based application for managing and sharing collections of links. This project includes user authentication, link submission, and sharing features.

## Features

- User registration and authentication
- Link submission and sharing
- Organized collections of links
- Responsive design

## Setup

Create a .env file in the root directory and add JWT_SECRET in the file.

Make sure to download and install MongoDB

```bash
# mongod
mongod.exe --dbpath /data/db

```

Make sure to install dependencies:

```bash
# npm
npm install

# pnpm
pnpm install

# yarn
yarn install

# bun
bun install
```

## Development Server

Start the development server on `http://localhost:3000`:

```bash
# npm
npm run dev

# pnpm
pnpm dev

# yarn
yarn dev

# bun
bun run dev
```

## Production

Build the application for production:

```bash
# npm
npm run build

# pnpm
pnpm build

# yarn
yarn build

# bun
bun run build
```

Locally preview production build:

```bash
# npm
npm run preview

# pnpm
pnpm preview

# yarn
yarn preview

# bun
bun run preview
```

## Deployment

Check out the [Nuxt deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.

## License

This project is licensed under the MIT License.