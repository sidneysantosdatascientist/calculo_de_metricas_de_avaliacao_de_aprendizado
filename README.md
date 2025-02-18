Ajuste de Limiar e Avaliação de Modelos de Classificação

Este projeto tem como objetivo demonstrar como ajustar o limiar de decisão de modelos de classificação para melhorar o desempenho em cenários de classes desbalanceadas, além de calcular e visualizar as principais métricas de avaliação de modelos.

Principais Funcionalidades

Cálculo de métricas fundamentais:

Acurácia

Sensibilidade (Recall)

Especificidade

Precisão

F1-Score e F2-Score

Ajuste do limiar de decisão:

Personalização do limiar com base no equilíbrio entre recall e especificidade.

Maximização de métricas específicas, como o F2-Score.

Gráficos interativos:

Curvas ROC e Precision-Recall para visualização do desempenho do modelo.

Balanceamento de dados:

Uso de técnicas como SMOTE para lidar com datasets desbalanceados.

Tecnologias Utilizadas

Linguagem: Python

Bibliotecas:

scikit-learn: Modelagem, métricas e balanceamento de dados.

numpy e matplotlib: Cálculos e visualizações.

imblearn: Oversampling com SMOTE.

Estrutura do Projeto

main.py: Arquivo principal com todo o fluxo de treinamento, ajuste de limiar e avaliação.

utils.py: Funções auxiliares para cálculo de métricas e balanceamento de dados.

README.md: Documentação do projeto.

Como Executar

Clone este repositório:

git clone https://github.com/seu-usuario/nome-do-repositorio.git

Instale as dependências necessárias:

pip install -r requirements.txt

Execute o arquivo principal:

python main.py

Opcionalmente, você pode usar o Jupyter Notebook para executar partes do código de forma interativa.

Exemplo de Resultados

Saída do Ajuste de Limiar

Melhor limiar para equilibrar Recall e Especificidade: 0.47
Acurácia: 0.92
Recall (Sensibilidade): 0.97
Especificidade: 0.59
Precisão: 0.94
F1-Score: 0.96
F2-Score: 0.72

Gráficos

Curva Precision-Recall: Visualização da relação entre precisão e recall em diferentes limiares.

Curva ROC: Avaliação do trade-off entre taxa de verdadeiros positivos (TPR) e taxa de falsos positivos (FPR).

Aplicações Práticas

Este projeto é ideal para cenários como:

Detecção de fraudes financeiras

Diagnóstico médico

Classificação com classes desbalanceadas

Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests com melhorias.

Licença

Este projeto está licenciado sob a Licença MIT. Consulte o arquivo LICENSE para mais informações.

