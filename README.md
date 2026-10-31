# Corte & Código — React V18

Migração inicial do site estático para React + Vite. Preserva o HTML e CSS aprovados e incorpora a página CORTES V17, com GSAP ScrollTrigger e tilt 3D leve.

## Executar
```bash
npm install
npm run dev
```

## Publicar na Vercel
Importe o repositório, selecione **Vite** (se necessário), Build Command `npm run build`, Output Directory `dist`.

## Atenção
A estrutura de HTML original está encapsulada nos componentes `src/pages/Home.jsx` e `src/pages/Cortes.jsx` para preservar o design. É uma **migração inicial funcional**, não uma reescrita completa em componentes reutilizáveis. Não inclui modelos WebGL ou MP4 originais; estes podem ser adicionados na próxima etapa.
