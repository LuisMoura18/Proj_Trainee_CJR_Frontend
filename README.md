# 🖥️ Fullstack Profile System - Frontend

Este é o módulo Frontend de um sistema de gestão de perfis de usuários, responsável pela interface e interação com lojas, produtos e avaliações. A aplicação foi construída utilizando práticas modernas de componentização, controle de estados e consumo de APIs assíncronas.

## 🚀 Tecnologias Utilizadas

* **Next.js** (Framework React com suporte a renderização híbrida e rotas dinâmicas)
* **React** (Biblioteca para construção de interfaces baseadas em componentes)
* **TypeScript** (Tipagem estática para maior segurança e previsibilidade do código)
* **Tailwind CSS** (Estilização baseada em classes utilitárias de alta performance)
* **Axios** (Cliente HTTP para comunicação com a API do backend)

## 📦 Funcionalidades Principais

* **Perfil Dinâmico:** Renderização de informações do usuário através de rotas dinâmicas baseadas no ID (`/profile/[id]`).
* **Gerenciamento de Conta:** Modais interativos para edição de dados cadastrais (Nome, Username, Email) e alteração de senha.
* **Vitrine de Produtos:** Listagem horizontal de produtos cadastrados pelo usuário, com suporte a tratamento de imagens principais.
* **Módulo de Lojas:** Exibição de lojas associadas ao perfil com suas respectivas categorias e logotipos.
* **Feed de Avaliações:** Renderização de comentários de produtos vinculados diretamente ao perfil do usuário.

## 🔧 Estrutura de Arquivos Chave

* `src/app/profile/[id]/page.tsx`: Tela principal do perfil do usuário contendo a lógica de hooks (`useState`, `useEffect`) e os modais de gerenciamento.
* `src/api/api.js`: Centralização e configuração das chamadas HTTP utilizando uma instância do Axios conectada ao servidor do backend.
