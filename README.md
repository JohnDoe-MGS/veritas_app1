# Estrutura do Projeto VERITAS

Este diretório contém uma estrutura inicial para o aplicativo VERITAS conforme especificado. Inclui código React (TypeScript) para páginas, componentes, configuração do Firebase, funções Cloud e um workflow de GitHub para implantação no Firebase Hosting.

Para utilizar este pacote:

1. Ajuste a configuração do Firebase em `src/firebase/firebase.ts` substituindo pelos seus valores reais.
2. Instale dependências com `npm install`.
3. Configure a CLI do Firebase e inicialize Hosting/Functions.
4. Compile com `npm run build` e implante com `firebase deploy`.
