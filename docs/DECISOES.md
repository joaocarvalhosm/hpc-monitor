## D-00X: Desenvolvimento com agente isolado (ai-jail)
Contexto: o Claude Code escreve e executa comandos na minha máquina e o repositório é público.
Decisão: rodar o agente no ai-jail: só a pasta do projeto é gravável, home vazio, ambiente
limpo, sem SSH, rede apenas para hosts permitidos (API da Anthropic, registries, GitHub).

## D-01X: --- 