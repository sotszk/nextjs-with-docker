# Next.js with Docker

## Getting Started

1. Install Docker
2. Build your container image `docker build -t nextjs-docker .`
3. Run your container `docker run -p 3000:3000 -d --rm nextjs-docker`

ブラウザで <http:localhost:3000> にアクセスします。

## 参考URL

- [With Docker | Next.js examples](https://github.com/vercel/next.js/tree/canary/examples/with-docker)
- [Dockerfile reference](https://docs.docker.com/engine/reference/builder/)
