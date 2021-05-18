<h1 align="center">
    <img alt="Ignite" title="Ignite" src=".github/imagem.png" />
</h1>

<h2 align="center">Refactoring de classes e typescript</h2>

</br>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Sobre o desafio</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Preparando ambiente Typescript</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Funcionalidades</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Como executar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Resultado Final</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Rodando a aplicação</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Licença</a>&nbsp;&nbsp;&nbsp;
</p>

## 📦 Tecnologias

- [React](https://reactjs.org/)
- [Typescript](https://www.typescriptlang.org/)
- [Axios](https://github.com/axios/axios)
- [react-icons](https://react-icons.github.io/react-icons/)
- [react-modal](https://github.com/reactjs/react-modal)
- [react-router-dom](https://reactrouter.com/web/guides/quick-start)
- [styled-components](https://styled-components.com/)
- [polished](https://polished.js.org/)
- [unform](https://unform.dev/)
- [yup](https://github.com/jquense/yup)

## 📦 Sobre o desafio

Essa será uma aplicação já funcional onde o seu principal objetivo é realizar dois processos de migração: de Javascript para Typescript e de Class Components para Function Components.

## Preparando ambiente Typescript

Como esse é um projeto CRA sem TypeScript, você primeiro precisar instalar as dependências/tipagens e configurar o TS. Nossa sugestão é criar um novo projeto CRA com Typescript e comparar a estrutura atual com a que você precisa ter. Realizando essa comparação, facilmente você consegue ver que:

- É preciso instalar o `typescript`
- É preciso criar um arquivo de configuração `tsconfig.json`. Inclusive, você pode utilizar a configuração gerada automaticamente no CRA template Typescript para criar o seu arquivo.
- É preciso criar um arquivo `react-app-env.d.ts` com o conteúdo:

```tsx
/// <reference types="react-scripts" />
```

- É preciso instalar as tipagens das bibliotecas.

Configurando esse setup, você deve ser capaz de trabalhar normalmente com o Typescript no seu projeto.

## 📦 Funcionalidades

- [x] Adicionar prato
- [x] Alterar detalhe do prato
- [x] Marcar/Desmarcar como disponível
- [x] Deletar prato


## 📦 Como executar

- Clone o repositório
- Instale as dependências com yarn install
- Inicie o servidor de dados com yarn server
- Em um novo terminal, inicie o servidor com yarn dev
- Agora você pode acessar localhost:8080 do seu navegador.

## 📦 Resultado Final

<p align="center" style="display: flex; align-items: flex-start; justify-content: center;">
  <img alt="Imagem de um App funcionando" title="App rocketshoes, desafio do Ignite" src="https://raw.githubusercontent.com/elianbecali/refactoring-classes-ts/master/.github/preview.gif" />
</p>

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.