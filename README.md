# pond_rnn_forecast

Projeto simples de previsão do consumo de energia elétrica residencial usando RNN. Todo o trabalho está em um único notebook Jupyter e utiliza o dataset incluído no repositório.

## Conteúdo
- `Previsa_de_consumo_de_energia_com_rnn.ipynb`: notebook principal com preparação de dados, modelo e resultados.
- `household_power_consumption.txt`: conjunto de dados usado no notebook.

## Como executar
1. Crie um ambiente virtual (opcional, recomendado):
   - Linux/macOS: `python -m venv .venv && source .venv/bin/activate`
   - Windows (PowerShell): `python -m venv .venv; .venv\Scripts\Activate.ps1`
2. Instale os pacotes básicos: `pip install jupyter numpy pandas matplotlib scikit-learn tensorflow`
3. Inicie o Jupyter: `jupyter notebook`
4. Abra `Previsa_de_consumo_de_energia_com_rnn.ipynb` e execute as células.

## Observações
- O arquivo de dados é grande; a abertura e o primeiro processamento podem demorar.
- Dependências podem variar por ambiente; se o TensorFlow for pesado para sua máquina, use `tensorflow-cpu`.
- O código foi testado no Google Colab, o caminho inicial de carregamento dos dados precisará de mudança se for testado localmente.
