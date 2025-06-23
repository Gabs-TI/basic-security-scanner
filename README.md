
#### README.md:
```markdown
# Scanner de Segurança Básico 🔐

Este projeto simula um scanner simples de vulnerabilidades, como verificação de headers de segurança e links suspeitos.

## Objetivo

Aplicar conceitos básicos de segurança ofensiva para fins educativos, utilizando Python e análise estática de sites.

## Funcionalidades

- Verifica se o site usa HTTPS
- Analisa cabeçalhos HTTP (ex: `X-Content-Type-Options`, `Strict-Transport-Security`)
- Coleta links e verifica padrões suspeitos

## Tecnologias

- Python
- Requests
- BeautifulSoup

## Como executar

```bash
pip install -r requirements.txt
python scanner/main.py

