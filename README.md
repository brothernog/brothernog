## Olá, eu sou o Fernando 👋

Técnico em automação industrial que virou desenvolvedor de software com agentes de IA. Passei oito anos com elétrica predial e industrial e programação de CLPs, e hoje coordeno Claude Code, Codex e outros agentes para construir e manter projetos completos, de um jogo com página na Steam ao aplicativo que uso para orquestrar esses mesmos agentes.

Da automação eu trouxe um hábito: documentar, testar e entender um sistema antes de mexer nele. É isso que deixa um projeto seguro para vários agentes trabalharem ao mesmo tempo.

### Projetos

| Projeto | O que é | Stack |
|---|---|---|
| [**Case Opened**](https://github.com/brothernog/case-opened) | Jogo de abertura de caixas com mecânica própria de avaliação de coleção. [Página na Steam](https://store.steampowered.com/app/5329660/Case_Opened/) | Godot 4, GDScript, Python, Steamworks |
| [**Orbit**](https://github.com/brothernog/orbit) | App desktop para orquestrar agentes de vários provedores e contas, com delegação entre eles e acompanhamento ao vivo das alterações | Electron, TypeScript, React, SQLite |
| [**Transfer Window**](https://github.com/brothernog/transfer-window) | Plataforma que reúne recrutamento, rankings, builds, guias e chat para jogadores de EA FC Pro Clubs (pausado) | Ruby on Rails 8, Hotwire, SQLite |

### Como eu trabalho com agentes

Num projeto de jogo que estou desenvolvendo agora (privado), a estrutura foi pensada desde o primeiro dia para trabalho com vários agentes:

- **Escopo por agente.** Cada um dos 15 agentes tem uma página de escopo, as pastas que pode alterar e o modelo que deve usar.
- **Contratos em vez de leitura cruzada.** Os módulos conversam por 12 contratos de interface versionados. Um agente lê o contrato, não o código do outro.
- **Decisões registradas.** Mais de 120 decisões numeradas, além de quadros de perguntas, pedidos e bloqueios. Nada fica só na memória de uma conversa.
- **Regras que a máquina confere.** Um verificador barra arquivos acima de 300 linhas, funções acima de 50, valores fixos no código e pendências não registradas. A média é de 81 linhas por arquivo.
- **Testes como rede de segurança.** São 475 testes, incluindo um que confirma que a simulação produz sempre o mesmo resultado para a mesma semente.

### Ferramentas

- **Agentes:** Claude Code, Codex, Gemini CLI, OpenCode, MCP, skills e subagentes
- **Tecnologias:** TypeScript, React, Electron, Ruby on Rails, Godot, Python, SQLite
- **Antes disso:** Ladder, Structured Text, Sysmac Studio, ISPSoft, elétrica predial e industrial

### Contato

📧 nogaredo.fernando@gmail.com

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/brothernog/brothernog/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/brothernog/brothernog/output/github-snake.svg" />
  <img alt="Cobrinha comendo o gráfico de contribuições" src="https://raw.githubusercontent.com/brothernog/brothernog/output/github-snake.svg" />
</picture>
