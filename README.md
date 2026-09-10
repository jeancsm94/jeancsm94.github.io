# Jean Carlos — Portfolio

> Portfólio pessoal de Jean Carlos, Desenvolvedor de Software Full Stack .NET.

[Site](https://jeancsm94.github.io) · [GitHub](https://github.com/jeancsm94) · [LinkedIn](https://www.linkedin.com/in/jeancsm94)

---

## Funcionalidades
- Hero interativo com fundo WebGL `<LetterGlitch />` ([ReactBits.dev](https://www.reactbits.dev/))
- Lista de skills, parede de logos e vitrine de projetos

## Stack
![Astro](https://img.shields.io/badge/Astro-FF5D01?logo=astro&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)

## Estrutura do projeto
```text
public/
└── svg/
src/
├── Components/
|    ├── footer.astro
|    ├── home.astro
|    ├── logoWall.astro
|    ├── nav.astro
|    └── projects.astro
├── layouts/
|    └── Layout.astro
├── React/
|    ├── LetterGlitch.tsx
|    └── SkillsList.tsx
└── pages/
     └── index.astro
```

## Configuração local

### Pré-requisitos
- Node.js v20 ou superior
- pnpm v9 ou superior (exigido pelo `preinstall`)

```bash
git clone https://github.com/jeancsm94/jeancsm94.github.io.git
pnpm install
pnpm dev
```

## Deploy
Hospedado no [GitHub Pages](https://pages.github.com/).

---

Baseado no template [Dark Minimal](https://github.com/Gothsec/dark-minimal), de Gothsec, licenciado sob [MIT](https://opensource.org/licenses/mit).
