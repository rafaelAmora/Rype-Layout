# Rype — Plataforma Gamer (Frontend)

Interface web da Rype, uma plataforma gamer com foco em comunidade, gestão de times e eventos. Desenvolvida em React com roteamento client-side e estética espacial/gamer.

## Stack

- **React** com **Vite**
- **React Router DOM** para navegação
- CSS puro por componente

## Pré-requisitos

- Node.js 18+

## Instalação

```bash
git clone https://github.com/rafaelAmora/rype-frontend.git
cd rype-frontend
npm install
npm run dev
```

## Páginas

| Rota | Página | Status |
|------|--------|--------|
| `/` | Home | ✅ |
| `/LoginPage` | Login | ✅ |
| `/RegisterPage` | Cadastro | ✅ |
| `/About` | Sobre | 🚧 Em manutenção |
| `/Events` | Eventos | 🚧 Em manutenção |
| `/Trenings` | Treinos | 🚧 Em manutenção |
| `/Contact` | Contato | 🚧 Em manutenção |

## Estrutura

```
src/
├── pages/
│   ├── Home/
│   ├── LoginPage/
│   ├── RegisterPage/
│   ├── About/
│   ├── Events/
│   ├── Trenings/
│   └── Contact/
├── Components/
│   ├── Header/
│   ├── Forms-Login/
│   └── Forms-Register/
├── Utilities/
│   └── MaintenancePage/
├── router.jsx
└── main.jsx
```

## Funcionalidades

- Página inicial com apresentação da plataforma
- Tela de login e cadastro com background espacial animado
- Animação de chuva em canvas (`RainfallAnimation`)
- Header de navegação com links para todas as seções
- Página de manutenção reutilizável para rotas em desenvolvimento
