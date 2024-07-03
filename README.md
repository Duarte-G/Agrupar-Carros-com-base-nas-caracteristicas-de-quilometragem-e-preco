# Atividade Proposta Card 11
Algoritmo K-Means para agrupar carros contidos na tabela com base nas características de quilometragem e preço.

 Como atividade, utilizei o algoritmo K-Means para agrupar os carros contidos na tabela com base nas características de quilometragem e preço. A forma mais otimizada que encontrei foi utilizando 4 clusters, obtendo um bom resultado para analisar cada grupo.
 Os resultados obtidos foram os seguintes: 
 - **Grupo Roxo**: Carros com baixa quilometragem e preço baixo (Média de quilometragem: 10053 Km, Média de preço: U$ 18032,25);
 - **Grupo Azul**: Carros com alta quilometragem e preço baixo(Média de quilometragem: 24150 Km, Média de preço: U$ 15733,00);
 - **Grupo Amarelo**: Carros com baixa quilometragem e preço alto(Média de quilometragem: 10219 Km, Média de preço: U$ 41769,36);
 - **Grupo Verde**: Carros com alta quilometragem e preço alto(Média de quilometragem: 23966 Km, Média de preço: U$ 32068,11).

 Esses grupos oferecem uma visão detalhada do mercado de carros usados, destacando diferentes perfis de consumidores e oportunidades de negócios. Podendo ser muito úti usando em um banco de dados de carros reais para extrair algumas informações. No entanto, é importante considerar que o método K-Means, embora útil, pode ter limitações par perceber alguns casos específicos do mercado, sendo recomendável utilizá-lo em conjunto com outras técnicas e dados adicionais.

## Ferramentas Utilizadas
 - Python: Linguagem de programação principal.
 - Bibliotecas Python: pandas, scikit-learn, pydotplus, entre outras.
 - Jupyter Notebook: Ambiente interativo usado para desenvolvimento e experimentação.

## Como Usar
 - Clone o repositório para sua máquina local.
 - Instale as dependências necessárias listadas no arquivo requirements.txt.
 - Execute o .ipynb para explorar o código e resultados.
 - Sinta-se à vontade para modificar e experimentar com diferentes parâmetros de modelo ou novos conjuntos de dados.