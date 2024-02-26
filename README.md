# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

# Setup your repository
> Vite requires Node version 14.18+ or 16+ to operate stably.

1. Clone source code

```shell
git clone https://github.com/huunghiaish/weather-forecast.git
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
docker build -t weather-forecast .
docker run -p 80:80 weather-forecast
```
# Building and publish image to private Docker Registry
```shell
docker build . -t registry.huunghianguyen.com/weather-forecast:1.0.0
docker push registry.huunghianguyen.com/weather-forecast:1.0.0
```
