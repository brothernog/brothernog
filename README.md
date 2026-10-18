## Olá, eu sou o Fernando 👋

Sou técnico em automação industrial e trabalhei oito anos com elétrica predial e industrial e programação de CLPs. Hoje me dedico ao desenvolvimento de software e à orquestração de agentes de IA, como Claude Code e Codex.

A automação me ensinou a documentar, testar e entender um sistema antes de mexer nele. Levo isso para os meus projetos de software, principalmente quando vários agentes trabalham no mesmo código.

### Projetos

| Projeto | O que é | Stack |
|---|---|---|
| [**Case Opened**](https://github.com/brothernog/case-opened) | Jogo de abertura de caixas com uma mecânica própria de avaliação da coleção. [Página na Steam](https://store.steampowered.com/app/5329660/Case_Opened/) | Godot 4, GDScript, Python, Steamworks |
| [**Orbit**](https://github.com/brothernog/orbit) | App desktop para orquestrar agentes de vários provedores e contas, com delegação entre eles e acompanhamento das alterações em tempo real | Electron, TypeScript, React, SQLite |
| [**Transfer Window**](https://github.com/brothernog/transfer-window) | Site que reúne recrutamento, rankings, builds, guias e chat para jogadores de EA FC Pro Clubs (pausado) | Ruby on Rails 8, Hotwire, SQLite |

### Como organizo projetos com agentes

Estou desenvolvendo outro jogo, ainda privado, que foi estruturado desde o início para o trabalho com vários agentes. Alguns pontos dessa estrutura:

- Cada um dos 15 agentes tem um escopo definido, as pastas que pode alterar e o modelo que deve usar.
- Os módulos se comunicam por 12 contratos de interface versionados. Um agente consulta o contrato e não precisa ler o código de outro módulo.
- Todas as decisões do projeto ficam registradas (hoje são mais de 120). Perguntas, pedidos e bloqueios também têm um quadro próprio.
- Um verificador automático barra arquivos com mais de 300 linhas, funções com mais de 50, valores fixos no código e pendências que não foram registradas. A média do projeto é de 81 linhas por arquivo.
- São 475 testes automatizados, entre eles um que garante que a simulação dá sempre o mesmo resultado para a mesma semente.

### Ferramentas

- **Agentes:** Claude Code, Codex, Gemini CLI, OpenCode, MCP, skills e subagentes
- **Tecnologias:** TypeScript, React, Electron, Ruby on Rails, Godot, Python, SQLite
- **Automação industrial:** Ladder, Structured Text, Sysmac Studio, ISPSoft

### Contato

📧 nogaredo.fernando@gmail.com

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/brothernog/brothernog/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/brothernog/brothernog/output/github-snake.svg" />
  <img alt="Cobrinha comendo o gráfico de contribuições" src="https://raw.githubusercontent.com/brothernog/brothernog/output/github-snake.svg" />
</picture>
