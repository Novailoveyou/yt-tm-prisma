# Prisma Crash Course

## About

This is me following Brad Traversy's [youtube video](https://youtu.be/CYH04BJzamo)

Year 2024

## Commands run in order

Init package.json

```zsh
pnpm init
```

Install dev dependencies

```zsh
pnpm add typescript ts-node @types/node -D
```

Init tsconfig.json

```zsh
pnpm exec tsc --init
```

Install dependencies

```zsh
pnpm add prisma
```

Init prisma

```zsh
pnpm exec prisma init --datasource-provider sqlite
```

Run prisma migration

```zsh
pnpm exec prisma migrate dev --name init
```

Run server

```zsh
pnpm exec ts-node index
```

Run prisma studio

```zsh
pnpm exec prisma studio
```
