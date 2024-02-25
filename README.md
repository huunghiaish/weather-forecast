# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

# Setup your repository
> Vite requires Node version 14.18+ or 16+ to operate stably.

1. Clone boilerplate

```shell
git clone https://github.com/huunghiaish/react-vite-boilerplate.git
```

2. Install package

```shell
npm install
```
3. Start code

```shell
npm run dev
```
# Building and running in Docker
```shell
docker build -t react-vite-boilerplate .
docker run -p 80:80 react-vite-boilerplate
```
# Building and publish image to private Docker Registry
```shell
docker build . -t registry.huunghianguyen.com/react-vite-boilerplate:1.0.0
docker push registry.huunghianguyen.com/react-vite-boilerplate:1.0.0
```