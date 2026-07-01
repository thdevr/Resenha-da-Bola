# Resenha da Bola

Projeto colaborativo desenvolvido como Atividade Avaliativa Final para a disciplina de Controle de Versão com Git & GitHub no curso Técnico em Informática para Internet. O objetivo principal do projeto é aplicar o fluxo de trabalho profissional utilizando Git (Git Flow), documentando o histórico de ramificações, resolução de conflitos e a aplicação de comandos avançados de versionamento.

## Instituição e Curso
* **Instituição:** Instituto Federal do Piauí (IFPI) - Campus Paulistana
* **Curso:** Técnico em Informática para Internet
* **Professor:** Prof. Me. Julian Rodrigues Valério
* **Data de Entrega:** 01/07/2026

---

## Equipe e Divisão de Trabalho
O projeto foi estruturado de forma que cada integrante ficasse responsável pelo desenvolvimento de uma página específica, garantindo a interligação do site por meio de um menu de navegação e o isolamento do código em branches exclusivas.

1. **Thiago Coutinho (Responsável Técnico / Desenvolvedor)**
   * **Branch:** `feature/home`
   * **Contribuição:** Desenvolvimento e estruturação da Página Inicial (`index.html`), criação da folha de estilos compartilhada (`style.css`) e implementação dos scripts dinâmicos de comportamento da interface (`script.js`), uso do comando git log --oneline --graph.

2. **Renan**
   * **Branch:** `feature/[Estatisticas]`
   * **Contribuição:** Desenvolvimento da página de Estatísticas e integrações.

3. **Gustavo Araújo**
   * **Branch:** `feature/lendas`
   * **Contribuição:** Desenvolvimento da página de lendas e integrações.

4. **Maicon**
   * **Branch:** `feature/campeonatos`
   * **Contribuição:** Desenvolvimento da página de Campeonatos (`campeonatos.html`)

---

## Tecnologias Utilizadas
* **HTML5:** Estruturação das páginas interligadas do site institucional.
* **CSS3:** Estilização visual unificada através de um arquivo de estilos compartilhado.
* **JavaScript:** Implementação de comportamentos dinâmicos na interface do usuário.
* **Git & GitHub:** Versionamento de código, gerenciamento de ramificações, Pull Requests e revisão por pares.

---

## Fluxo de Trabalho e Diretrizes (Git Flow)

### 1. Isolamento em Branches de Funcionalidade
Para assegurar a estabilidade do código na ramificação principal (`main`), nenhuma alteração foi submetida diretamente a ela. O processo seguiu o padrão de boas práticas:
* Criação de ramificações locais baseadas na funcionalidade (`git checkout -b feature/descricao`).
* Registro do progresso por meio de commits atômicos (mínimo de 3 por integrante), utilizando mensagens descritivas e objetivas.

### 2. Pull Requests e Revisão de Código (Code Review)
A integração do código de cada página foi realizada por meio de Pull Requests na interface do GitHub. Cada solicitação de integração foi revisada e comentada por pelo menos um outro integrante do grupo antes da aprovação final e do merge na `main`.

---

## Demonstração de Comandos Avançados

Conforme os requisitos técnicos previstos, foram aplicados e documentados comandos avançados do ecossistema Git para auditoria e controle do repositório:

### Comando 1: Inspeção de Histórico Gráfico e Ramificado
* **Comando:** `git log --oneline --graph`
* **Aplicação (Thiago Coutinho):** Executado ativamente no terminal para mapear a árvore de commits do repositório antes de realizar novas alterações ou integrações. O comando permitiu visualizar a relação cronológica entre as branches paralelas, mitigando riscos de conflitos cegos durante o desenvolvimento da `feature/home`.

---

## Arquivo de Configuração (.gitignore)
O repositório inclui um arquivo `.gitignore` estruturado para evitar a inclusão e o rastreamento de arquivos desnecessários ou redundantes ao escopo do projeto, tais como:
* Diretórios de configuração de editores e IDEs (`.vscode/`, `.idea/`).
* Arquivos temporários gerados pelo sistema operacional (`.DS_Store`, `Thumbs.db`).

---

### Links do Repositório
* **URL do Projeto:** [https://github.com/thdevr/Resenha-da-Bola](https://github.com/thdevr/Resenha-da-Bola)
* **URL do Site:** [https://thdevr.github.io/Resenha-da-Bola/]
