# 🌌 Emissários Wiki - Sistema de RPG

Este repositório contém a wiki oficial do sistema de RPG **Emissários**, desenvolvida com foco em performance, automação e organização de lore/regras. O projeto utiliza o framework **Quartz** para transformar notas em Markdown numa plataforma web interactiva.

## 🚀 Tecnologias Utilizadas

- **Quartz 4.0**: Framework baseado em TypeScript para geração de sites estáticos a partir de notas.
- **TypeScript**: Configuração e lógica do sistema de temas e plugins.
- **GitHub Actions (CI/CD)**: Pipeline automatizada para build e deploy contínuo no GitHub Pages.
- **Markdown**: Linguagem de marcação para todo o conteúdo de regras e ambientação.

## 🛠️ Funcionalidades Técnicas

- **Deploy Automatizado**: Cada `push` para a branch principal dispara uma ação no GitHub que reconstrói o site automaticamente.
- **Gráfico de Conexões**: Visualização dinâmica das interligações entre as notas de lore.
- **Pesquisa em Tempo Real**: Indexação de conteúdo para busca rápida de regras.
- **Tema Customizado**: Interface personalizada com a estética "Khaenri'ah" (Azul Abissal e Dourado).

## 📦 Como Executar Localmente

Se desejar testar o projeto no seu ambiente local:

1. Instale as dependências:
   ```bash
   npm install
Execute o servidor de desenvolvimento:

Bash
npx quartz build --serve
O site estará disponível em http://localhost:8080.

📈 Desenvolvimento de Software (CS Context)

Este projeto foi desenvolvido como parte de um estudo prático de DevOps e Sincronização de Versionamento, focando em:

Resolução de conflitos de ambiente entre local e servidor (Node.js 22).

Gestão de hierarquia de ficheiros e sintaxe TypeScript.

Implementação de fluxos de trabalho (workflows) automatizados.

Desenvolvido por Pedro Rafael Freitas de Souza
