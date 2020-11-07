# ETL em python: trabalhando com dados abertos no mundo real([Python Brasil 2020](https://2020.pythonbrasil.org.br))

Nesse tutorial vamos aprender o básico sobre as etapas de uma rotina de ETL(extract, transform and load). A ideia aqui é utilizar um dataset público da [CVM](dados.cvm.gov.br/) para demonstrar como implementar as diferentes etapas dessa rotina. Vamos explorar alguns conceitos básicos da Engenharia de dados, como implementar rotinas para extração de arquivos e como manipular dados tabulares com o Pandas. Lembrando que toda a implementação aqui é focada em *small data*.

O arquivo `ETL_open_data.ipynb` é o arquivo base para a implementação do tutorial, o resultado final, para quem quiser spoilers, está no arquivo `Result-ETL_open_data.ipynb`.

# Configurar ambiente

Requisitos:
- Python 3.6 ou superior
- [Python virtual env](https://docs.python.org/3/tutorial/venv.html)

1. Inicialize um ambiente virtual na raiz do projeto:
```bash
python3 -m venv etl-env
```
2. Ative o ambiente virtual:
```bash
source etl-env/bin/activate
```

3. Instale as dependências executando na raiz do projeto:
```bash
pip install -r requirements.txt
```

4. Inicie o jupyter notebook executando:
```
python -m jupyter notebook
```