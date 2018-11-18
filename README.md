# Projeto – Análise de Risco de Crédito

Repositório para implementação do projeto da disciplina de IF702-Redes Neuras 2018.2.

## Classificação de padrões
- Base real de instituição que vende a crédito;
- Base em larga escala: +- 400 mil registros para treinamento e +-130 mil registros para teste;
- Problema: com base no perfil de clientes, decidir a quem conceder crédito (risco de inadimplência).

## Setup

### Creating an environment from an environment.yml file

Use the Terminal or an Anaconda Prompt for the following steps.

1. Create the environment from the environment.yml file:

```conda env create -f environment.yml```

The first line of the yml file sets the new environment’s name (**IF702-redes-neurais**).

2. Activate the new environment:
  * Windows: ```activate IF702-redes-neurais```
  * macOS and Linux: ```source activate IF702-redes-neurais```

3. The last command installs a kernel spec file for the current python installation. Kernel spec files are JSON files, which can be viewed and changed with a normal text editor:

```python -m ipykernel install --user --name IF702-redes-neurais --display-name "Python (IF702-redes-neurais)"```