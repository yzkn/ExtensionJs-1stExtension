# ExtensionJs-1stExtension

Extension.jsで拡張機能を作る

---

# 手順

## Nodeの最新化

```sh
volta install node@latest
volta install npm@latest
```

## Extension.jsのインストール

```sh
npx extension@latest create 1stext
```

## 実行

- package.json

```plaintext
  "scripts": {
    "dev": "extension dev --browser=edge",
    "start": "extension start",
```

```sh
cd ./1stext
npm run dev
```

---

Copyright (c) 2024 YA-androidapp(https://github.com/yzkn) All rights reserved.
