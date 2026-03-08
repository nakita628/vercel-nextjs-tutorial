# Vercel Next.js Tutorial

## 環境構築

```sh
npm i -g vercel
```

```sh
npm i next@latest react@latest react-dom@latest
```

```sh
npm i -D @types/node @types/react
```

## ディレクトリ構成

```sh
.
├── package.json
├── src
│   └── app
│       ├── layout.tsx
│       └── page.tsx
└── tsconfig.json
```

```sh
vercel link
```

```json
{"projectId":"***","orgId":"***"}
```

`projectId`を`VERCEL_PROJECT_ID`

`orgId`を`VERCEL_ORG_ID`