# Mundo Vinyl — Landing Page

Landing page em React para a Mundo Vinyl (loja de discos, Jardim São Luiz, Ribeirão Preto-SP). Rebrand construído em cima da mesma base da landing da Hifive Discos, com paleta preto/branco + azul cobalto extraída da logo, e dados reais confirmados pelo cliente (endereço, WhatsApp, e-mail).

## Stack

- React 18 + Vite
- Tailwind CSS
- Ícones: [lucide-react](https://lucide.dev/)

## Rodando localmente

```bash
npm install
npm run dev       # ambiente de desenvolvimento
npm run build     # build de produção (gera pasta dist/)
npm run preview   # serve o build de produção localmente
```

## Antes de publicar

O próprio código-fonte (`src/App.jsx`) aponta o que falta conferir: o horário de funcionamento (`HOURS`) está com um valor genérico e precisa ser confirmado com o cliente.
