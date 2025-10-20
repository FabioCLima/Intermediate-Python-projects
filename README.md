# Intermediate Python Projects

Este repositório contém todos os projetos relacionados ao curso Intermediate Python da Udacity.

## Estrutura do Projeto

### Neo Project (Submódulo)
Projeto principal de análise de dados de Near-Earth Objects (NEOs) organizado como um submódulo Git.

**Localização:** `neo-project/`

**Para trabalhar com o neo-project:**
```bash
cd neo-project
source .venv/bin/activate
python -m pytest tests/
python main.py
```

## Configuração

- Python 3.13
- Ambiente virtual configurado com `uv`
- Linting com `ruff`

## Como usar

1. Clone o repositório principal
2. Para trabalhar com o neo-project:
   - `cd neo-project`
   - `source .venv/bin/activate`
   - Execute os testes: `python -m pytest tests/`
   - Execute o projeto: `python main.py`

## Licença

MIT License - veja o arquivo [LICENSE](LICENSE) para detalhes.