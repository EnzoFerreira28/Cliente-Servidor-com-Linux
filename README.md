
# Análise de Logs do Nginx

Projeto desenvolvido como parte dos projetos práticos do [roadmap.sh](https://roadmap.sh/projects/nginx-log-analyser).

## Objetivo

Script Shell que analisa um arquivo de log do Nginx e exibe:

- Top 5 IPs com mais requisições
- Top 5 caminhos mais acessados
- Top 5 códigos de status HTTP
- Top 5 user agents

## Tecnologias

- Shell Script (Bash)
- Comandos: `awk`, `sort`, `uniq`, `head`, `grep`

## Como executar
Para executar o código, abra um terminal (cmd, PowerShell por exemplo) e execute:
```bash
chmod +x ./analises.sh

e então:

./analises.sh
```

## Estrutura do projeto

```
├── logs/
│   └── nginx-access.log
└── ShellScript/
    └── analises.sh
```

