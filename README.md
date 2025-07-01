# MutPy Tutorial

Este projeto contém um exemplo simples de teste de mutação usando o MutPy.

## Estrutura
- `calculator.py`: Código com funções básicas.
- `test_calculator.py`: Testes unitários com unittest.
- `report/index.html`: Relatório de mutação com 100% de score.

## Como gerar o relatório novamente

```bash
pip install git+https://github.com/mutpy/mutpy.git
python -m mutpy --target calculator --unit-test test_calculator --report html --report-html report
```
