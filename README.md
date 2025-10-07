# Papyrus

A Self-hosted OPAC (Online Public Access Catalog) and Personal Favorite Book Management System.

## Teck stack

### Frontend

- Framework: [TanStack Router](https://tanstack.com/router/v1/)
- CSS Framework: [Panda CSS](https://panda-css.com/)


### Backend

- Framework: [Elysia](https://elysiajs.com/)

### Common

- Runtime: [Cloudflare Workers](https://workers.cloudflare.com/)
- Linter and Formatter: [Biome](https://biomejs.dev/)
- Package Manager: [pnpm](https://pnpm.io/)
- API Schema: [OpenAPI](https://www.openapis.org/)

## Development

1. Install [Node.js](https://nodejs.org/) (version >= 20) and [pnpm](https://pnpm.io/installation).
2. Clone this repository and navigate to the project directory.
3. Run `pnpm install` to install dependencies.

### Frontend and Backend

1. to Run `pnpm run dev` to start the development servers.
2. Open your browser and go to `http://localhost:8787` for the backend and `http://localhost:5173` for the frontend.

### Typespec

1. Navigate to `typespec` directory and run `pnpm run dev` to start the development servers.
2. Open your browser and go to `http://localhost:8080/oapi.html` for the [scalar](https://scalar.com/).

### GitHub Actions

1. Write workflow files in `.github/workflows` directory.
2. Install [pinact](https://github.com/suzuki-shunsuke/pinact) and run `pinact` to update the workflow files.
```bash
go install github.com/suzuki-shunsuke/pinact/cmd/pinact@latest
pinact
```
