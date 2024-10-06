# ChnoAI의 프론트엔드 파일입니다.
## 프로젝트 설정 및 실행

### 의존성 설치

프로젝트의 의존성을 설치하려면 다음 명령어를 사용하세요:

```bash
npm install --legacy-peer-deps
```

### 환경 변수 설정

프로젝트 루트 디렉토리에 `.env` 파일을 추가하고 아래 코드를 복사 붙여넣기 해주세요.

```env
VITE_BASE_URL = http://localhost:8080/
VITE_APP_FORM_SPARK = "https://submit-form.com/zTXgFX6MY"
```

### 프로젝트 실행

프로젝트를 실행하려면 다음 명령어를 사용하세요:

```bash
npm run dev
```

이 명령어는 개발 서버를 시작하고 애플리케이션을 브라우저에서 확인할 수 있게 합니다.


아래 무시

# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: "latest",
    sourceType: "module",
    project: ["./tsconfig.json", "./tsconfig.node.json"],
    tsconfigRootDir: __dirname,
  },
};
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
