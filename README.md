# Desafio Técnico de Estágio — Front-end

## 1. Objetivo

Desenvolver uma aplicação web para gerenciamento de clientes (CRUD), utilizando Next.js, TypeScript, Tailwind CSS, shadcn/ui e Lucide React.

O projeto será desenvolvido em etapas, contemplando funcionalidades comuns de sistemas administrativos.

O candidato poderá utilizar o ChatGPT como ferramenta de apoio durante o desenvolvimento. Entretanto, deverá compreender o código produzido e conseguir explicar suas decisões técnicas.

## 2. Prazo de entrega

**Data limite: 23 de outubro de 2026.**

O projeto deverá estar publicado em um repositório público no GitHub do próprio candidato. O link do repositório deverá ser compartilhado com a empresa responsável pelo processo seletivo até a data limite.

## 3. Tecnologias obrigatórias

- Next.js, utilizando a versão estável mais recente disponível no início do desenvolvimento.
- React.
- TypeScript.
- Tailwind CSS.
- shadcn/ui.
- Lucide React (`lucide-react`).

### Criação do projeto

Utilize o comando abaixo para criar a aplicação:

```bash
npx create-next-app@latest crud-clientes
```

Configure o projeto utilizando TypeScript, Tailwind CSS e App Router.

## 4. Restrições de bibliotecas

Somente as tecnologias e bibliotecas especificadas neste documento poderão ser utilizadas no desenvolvimento.

Não será permitido utilizar bibliotecas externas adicionais para formulários, validações, gerenciamento de estado, tabelas, ícones ou componentes de interface.

Serão permitidas as dependências necessárias ao funcionamento do Next.js, Tailwind CSS e shadcn/ui.

## 5. Descrição do projeto

Desenvolver uma aplicação para gerenciamento de clientes, contendo os seguintes dados:

- Nome completo.
- E-mail.
- Telefone.
- Cidade.
- Status: Ativo ou Inativo.

A aplicação deverá permitir cadastrar, listar, editar, pesquisar, filtrar e excluir clientes.

Não será necessário desenvolver backend ou integrar um banco de dados. Os dados poderão ser mantidos em memória durante a execução da aplicação.

## 6. Referência visual

A imagem abaixo apresenta um exemplo de interface administrativa utilizada em sistemas corporativos.

Utilize-a como inspiração para desenvolver o layout do projeto, considerando a organização dos filtros, tabelas, botões e informações.

O objetivo não é reproduzir a imagem exatamente, mas desenvolver uma interface própria, organizada e responsiva, utilizando as tecnologias especificadas neste desafio.

![Referência visual de um sistema administrativo](./Captura%20de%20tela%20de%202026-10-17%2016-07-56.png)

## 7. Desafios

### Desafio 01 — Estrutura inicial

Configure o projeto e desenvolva a estrutura principal da aplicação, incluindo o layout e a navegação.

### Desafio 02 — Listagem de clientes

Implemente a exibição dos clientes em uma tabela, utilizando dados fictícios e tipagem adequada com TypeScript.

### Desafio 03 — Cadastro de clientes

Desenvolva uma interface para cadastrar novos clientes.

### Desafio 04 — Salvamento de registros

Implemente a inclusão de novos clientes na listagem, sem recarregar a página.

### Desafio 05 — Validação de dados

Adicione validações aos campos do formulário e apresente mensagens de feedback ao usuário.

### Desafio 06 — Edição de clientes

Permita selecionar um cliente existente, editar suas informações e salvar as alterações.

### Desafio 07 — Exclusão de clientes

Implemente a exclusão de registros com confirmação da ação.

### Desafio 08 — Pesquisa de clientes

Adicione uma funcionalidade de pesquisa para localizar clientes cadastrados.

### Desafio 09 — Filtro por status

Implemente filtros para visualizar todos os clientes, somente os ativos ou somente os inativos. A filtragem deverá funcionar em conjunto com a pesquisa.

### Desafio 10 — Finalização do projeto

Revise a interface, a responsividade, a organização dos componentes e a qualidade geral do código. Documente as instruções necessárias para executar a aplicação.

## 8. Requisitos de entrega

- Os dez desafios deverão fazer parte da mesma aplicação.
- O código deverá utilizar TypeScript.
- A interface deverá ser desenvolvida com Tailwind CSS e shadcn/ui.
- Os ícones deverão utilizar Lucide React.
- A aplicação deverá funcionar localmente.
- O código deverá estar organizado e ser compreensível.
- O repositório deverá conter um README com instruções para instalação e execução.
- O repositório deverá ser público e estar publicado no GitHub do candidato.

## 9. Uso do ChatGPT

O uso do ChatGPT está permitido durante todo o desenvolvimento.

O candidato poderá utilizá-lo para pesquisar soluções, compreender conceitos, gerar sugestões de código e corrigir erros.

Durante a avaliação, poderá ser solicitado que o candidato explique partes da implementação ou realize pequenas alterações no projeto.

O candidato deverá compreender o código entregue e saber justificar as principais decisões tomadas durante o desenvolvimento.

## 10. Entrega final

Compartilhe o link do repositório público do GitHub com a empresa até **23 de outubro de 2026**.

Antes da entrega, verifique se o projeto está completo, executável e documentado.

**Boa sorte e bom desenvolvimento!**
