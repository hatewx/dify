# AB Frontend

## Getting Started

### Run by source code

First, install the dependencies:

```bash
cd web/

pnpm i
```

Finally, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Deploy

### Deploy on server

First, build the app for production:

```bash
pnpm build
```

Then, start the server:

```bash
pnpm start
```

If you want to customize the host and port:

```bash
pnpm start --port=3001 --host=0.0.0.0
```
