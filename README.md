# weather diary client

## Vite React 시작하기

1. Vite React 앱 설치

```bash
npm create vite@latest weather-diary-client --template react
```

2. npm 패키지 설치

```bash
cd weather-diary-client
npm i
```

3. 리액트 앱 실행

```
npm run dev
```

## eslint, prettier 설정

1. 플러그인 설치

```bash
npm install --save-dev eslint eslint-plugin-import eslint-plugin-html eslint-config-prettier prettier
```

> reference: [eslint + prettier 설치하기](https://velog.io/@dikum98/vite%EB%A1%9C-react-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EC%8B%9C%EC%9E%91%ED%95%98%EA%B8%B0)

2. .prettierrc, eslint.config.js 및 package.json script 설정

- `.prettierrc`

  ```bash
  {
    "printWidth": 80,
    "tabWidth": 2,
    "useTabs": false,
    "semi": true,
    "singleQuote": false,
    "jsxSingleQuote": false,
    "trailingComma": "es5",
    "bracketSpacing": true,
    "arrowParens": "always",
    "endOfLine": "lf",
    "proseWrap": "preserve"
  }
  ```

> reference: [socketing-client repository](https://github.com/everyone-falls-asleep/socketing-client/blob/master/eslint.config.js)
