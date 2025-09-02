# Detalhes Técnicos do Projeto

Esta página descreve a arquitetura e as ferramentas utilizadas na criação e manutenção do Manual de Especialidades em versão digital. O projeto é construído sobre uma pilha de ferramentas de código aberto, projetadas para garantir facilidade de uso, manutenção e colaboração.

## Ferramentas Principais

- **[Markdown](https://pt.wikipedia.org/wiki/Markdown):** Todas as especialidades são transcritas para arquivos Markdown (`.md`). Esta linguagem de marcação simples e leve permite que o conteúdo seja facilmente lido, editado e versionado, sem a complexidade de formatos proprietários.
- **[Git](https://git-scm.com/) & [GitHub](https://github.com/):** O controle de versão é gerenciado com **Git**, e o código-fonte (os arquivos Markdown) é hospedado em um repositório no **GitHub**. Isso não só garante a segurança e o histórico de todas as alterações, como também facilita a contribuição da comunidade através de _pull requests_ e _issues_.
- **[MkDocs](https://www.mkdocs.org/) & [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/):**
    - **MkDocs** é um gerador de site estático que converte os arquivos Markdown em um website totalmente navegável. Ele cuida da estrutura de navegação e da geração das páginas HTML.
    - **Material for MkDocs** é um tema para o MkDocs que oferece um _design_ moderno, responsivo e com ótimos recursos, como a barra de pesquisa, navegação lateral e suporte a ícones. Ele é fundamental para a experiência de usuário.
- **[Read the Docs](https://about.readthedocs.com/):** Esta plataforma hospeda a documentação do projeto. O **Read the Docs** se integra perfeitamente com o GitHub, detectando automaticamente as atualizações no repositório. Ele então executa o MkDocs para gerar o site e publicá-lo, garantindo que a versão online esteja sempre sincronizada com o conteúdo mais recente.
