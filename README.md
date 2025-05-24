📊 Análise de Evasão de Clientes (Churn) – Telecom X

🧭 Visão Geral

Esse projeto nasceu como parte de um desafio de Data Science com um objetivo bem claro: entender por que os clientes da Telecom X estão deixando a empresa. Analisar o churn não é só uma questão de números — é sobre entender comportamentos, melhorar o serviço e fortalecer a relação com o cliente.

Aqui, mergulhei nos dados para identificar os principais fatores que influenciam a evasão de clientes. A ideia é que essas informações sirvam como base para criar estratégias de retenção mais eficazes e inteligentes, reduzindo perdas e otimizando investimentos em aquisição.

🗂 Estrutura do Projeto

O projeto está todo concentrado em um único Jupyter Notebook:
	•	TelecomX_Churn_Analysis_Report.ipynb: nele você encontra desde o carregamento e tratamento dos dados até a análise completa e um relatório final com insights e recomendações práticas.

🛠 Tecnologias Utilizadas

Para essa análise, utilizei as seguintes bibliotecas Python:
	•	pandas – manipulação e análise de dados.
	•	numpy – suporte a operações numéricas e vetoriais.
	•	requests – carregamento de dados via HTTP.
	•	seaborn e matplotlib.pyplot – visualizações para tornar os insights mais claros e acessíveis.

▶️ Como Executar

Se quiser rodar a análise no seu ambiente local, é só seguir os passos abaixo:
	1.	Clone o repositório:

git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
cd SEU_REPOSITORIO

(Lembre-se de trocar SEU_USUARIO e SEU_REPOSITORIO pelo seu usuário e repositório do GitHub.)

	2.	(Opcional) Crie um ambiente virtual:

python -m venv venv
# No Windows:
.\venv\Scripts\activate
# No macOS/Linux:
source venv/bin/activate


	3.	Instale as dependências:

pip install pandas numpy requests seaborn matplotlib


	4.	Abra o notebook no Jupyter:

jupyter notebook TelecomX_Churn_Analysis_Report.ipynb

Isso abrirá o notebook no navegador. A partir daí, é só executar as células e acompanhar todo o raciocínio da análise.

📌 Principais Conclusões

Alguns pontos se destacaram durante o estudo:
	•	Clientes com pouco tempo de contrato (tenure curto) tendem a evadir com mais frequência.
	•	Planos com cobrança mensal estão diretamente ligados a altas taxas de churn.
	•	O método de pagamento “Electronic check” tem forte correlação com evasão.
	•	A adesão a serviços adicionais (como backup e suporte técnico) parece ajudar na retenção.
	•	Curiosamente, clientes com Fibra Óptica apresentaram maior taxa de churn — o que pode indicar uma falha na entrega ou expectativas não atendidas.

💡 Recomendações

Com base nas análises, algumas sugestões surgem de forma natural:
	•	Criar programas de boas-vindas focados nos clientes novos (especialmente no início do ciclo).
	•	Incentivar contratos de longo prazo.
	•	Investigar o motivo da insatisfação com o método de pagamento “Electronic check”.
	•	Promover serviços adicionais como parte de pacotes mais completos.
	•	Reavaliar a qualidade do serviço de fibra óptica, que pode estar impactando negativamente a experiência do cliente.

Para mais detalhes e visualizações, você pode conferir tudo dentro do notebook.

⸻

Autor: Dragos Calin
Data: 24 de Maio de 2025
