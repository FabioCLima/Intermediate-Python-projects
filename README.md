# Intermediate Python Projects

Este repositório contém todos os projetos relacionados ao curso Intermediate Python da Udacity.

## Estrutura do Projeto

### Neo Project (Submódulo)
Projeto principal de análise de dados de Near-Earth Objects (NEOs) organizado como um submódulo Git.

**Localização:** `neo-project/`

**Para trabalhar com o neo-project:**
```bash
# Clonar o repositório com submódulos
git clone --recursive https://github.com/FabioCLima/Intermediate-Python-projects.git

# Ou se já clonou, inicializar submódulos
git submodule update --init --recursive

# Entrar no diretório do neo-project
cd neo-project

# Ativar ambiente virtual
source .venv/bin/activate

# Executar testes
python -m pytest tests/

# Executar o projeto
python main.py
```

## Configuração

- Python 3.13
- Ambiente virtual configurado com `uv`
- Linting com `ruff`

## Como usar

1. Clone o repositório com submódulos: `git clone --recursive <url>`
2. Para trabalhar com o neo-project:
   - `cd neo-project`
   - `source .venv/bin/activate`
   - Execute os testes: `python -m pytest tests/`
   - Execute o projeto: `python main.py`

## Licença

MIT License - veja o arquivo [LICENSE](LICENSE) para detalhes.