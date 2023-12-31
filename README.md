# OAuh2 Demo

## Getting Started

### Install Dependencies

```sh
npm install
```

### Start Development Server
```sh
npm run dev
```

### Production Build

```sh
npm run build
```

### Start Production Server
```sh
npm run start
```

## Containerization

### Build Image

Note: If you use Docker, then replace 'podman' with 'docker' for all commands below.

```sh
podman build -t auth-demo ./
```

### Start Container

```sh
podman run -d -p 3000:3000 --name=auth-demo auth-demo
```

## Tech Stack

### Primary

- [Next.js](https://nextjs.org) - **13.5.4** (React **18.2.0**)
- [NextAuth.js](https://next-auth.js.org/) - **4.24.5**
- [Tailwind CSS](https://tailwindcss.com) - **3.0.11**
