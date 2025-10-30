# Gerador de Dieta IA

Este é um projeto de frontend para um aplicativo web que gera planos de dieta personalizados usando inteligência artificial. Os usuários podem inserir suas informações pessoais, nível de atividade e objetivos, e o aplicativo gera um plano de dieta customizado.

## ✨ Funcionalidades

- **Formulário Intuitivo:** Um formulário fácil de usar para coletar dados do usuário, como nome, idade, altura, peso, sexo, nível de atividade e objetivo.
- **Validação de Dados:** Validação de formulário em tempo real para garantir que os dados inseridos sejam válidos.
- **Geração de Dieta:** Comunica-se com uma API externa para gerar um plano de dieta com base nas informações do usuário.
- **Exibição em Streaming:** A resposta da API é recebida e exibida em tempo real (streaming), proporcionando uma experiência de usuário fluida e responsiva.

## 🚀 Tecnologias Utilizadas

- **Framework:** [Next.js](https://nextjs.org/)
- **Linguagem:** [TypeScript](https://www.typescriptlang.org/)
- **Estilização:** [Tailwind CSS](https://tailwindcss.com/)
- **Componentes de UI:** [shadcn/ui](https://ui.shadcn.com/)
- **Gerenciamento de Formulários:** [React Hook Form](https://react-hook-form.com/)
- **Validação de Schema:** [Zod](https://zod.dev/)
- **Renderização de Markdown:** [React Markdown](https://github.com/remarkjs/react-markdown)

## 🏁 Começando

Siga as instruções abaixo para configurar e executar o projeto em seu ambiente local.

### Pré-requisitos

- [Node.js](https://nodejs.org/en/) (versão 20 ou superior)
- [npm](https://www.npmjs.com/), [yarn](https://yarnpkg.com/), ou [pnpm](https://pnpm.io/)

### Instalação

1.  Clone o repositório:
    ```bash
    git clone https://github.com/FabianoLaureano/gerador-de-dietas
    ```
2.  Navegue até o diretório do projeto:
    ```bash
    cd gerador-de-dietas/frontend/web
    ```
3.  Instale as dependências:
    ```bash
    npm install
    ```

### Executando o Servidor de Desenvolvimento

Para iniciar o servidor de desenvolvimento, execute o seguinte comando:

```bash
npm run dev
```

Abra [http://localhost:3000](http://localhost:3000) em seu navegador para ver o resultado.

## ⚙️ Scripts Disponíveis

- `npm run dev`: Inicia o servidor de desenvolvimento.
- `npm run build`: Compila o aplicativo para produção.
- `npm run start`: Inicia um servidor de produção.
