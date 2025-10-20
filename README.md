# Intermediate Python Projects

Este repositório contém todos os projetos relacionados ao curso Intermediate Python da Udacity.

## Estrutura do Projeto

### Neo Project
Projeto principal de análise de dados de Near-Earth Objects (NEOs).

**Arquivos principais:**
- `main.py` - Script principal de execução
- `database.py` - Operações de banco de dados
- `extract.py` - Extração de dados
- `filters.py` - Filtros de dados
- `models.py` - Modelos de dados
- `write.py` - Escrita de resultados
- `helpers.py` - Funções auxiliares

**Dados:**
- `data/neos.csv` - Dataset principal de NEOs

**Testes:**
- `tests/` - Conjunto completo de testes unitários

## Configuração

- Python 3.13
- Ambiente virtual configurado com `uv`
- Linting com `ruff`

## Como usar

1. Clone o repositório
2. Ative o ambiente virtual: `source .venv/bin/activate`
3. Execute os testes: `python -m pytest tests/`
4. Execute o projeto principal: `python main.py`

## Licença

MIT License - veja o arquivo [LICENSE](LICENSE) para detalhes.