import pandas as pd
import matplotlib.pyplot as plt

# Suponhamos que você tenha um arquivo CSV chamado 'taxas_homicidio_2022.csv' com seus dados.
# Carregue o arquivo CSV em um DataFrame pandas.
dados = pd.read_csv('taxas_homicidio_2022.csv')

# Visualize as primeiras linhas dos dados para verificar a estrutura.
print(dados.head())

# Agora, você pode realizar análises e visualizações básicas. Por exemplo, calcular a média da taxa de homicídios:
media_taxa_homicidio = dados['Taxa_Homicidio'].mean()
print(f'Média da Taxa de Homicídio em 2022: {media_taxa_homicidio}')

# Criar um gráfico de barras simples para comparar as taxas de homicídio por estado:
plt.figure(figsize=(12, 6))
plt.bar(dados['Estado'], dados['Taxa_Homicidio'])
plt.xlabel('Estado')
plt.ylabel('Taxa de Homicídio')
plt.title('Taxa de Homicídio por Estado em 2022')
plt.xticks(rotation=45)
plt.tight_layout()
plt.show()



- 👋 Hi, I’m @Fabyangr
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Fabyangr/Fabyangr is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
