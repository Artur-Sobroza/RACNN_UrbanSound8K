# RACNN_UrbanSound8K
Classificação de Sons Urbanos com Transferência de Aprendizado (RACNN). Este projeto explora o modelo RACNN pré-treinado em ESC-50 e finetunado para o dataset UrbanSound8K, usando Mel-espectrogramas e 10-Fold CV. Analisamos detalhadamente Precision, Recall e F1-Score para entender o desempenho em classes variadas e desafios de desbalanceamento.

O que este projeto faz?
Este repositório implementa um modelo de Rede Neural Convolucional Adaptativa a Recursos (RACNN) para a classificação automática de eventos sonoros em ambientes urbanos. O foco principal é explorar a eficácia da Transferência de Aprendizado, pré-treinando o modelo no dataset ESC-50 e realizando finetuning no desafiador UrbanSound8K. Avalia-se o desempenho detalhadamente usando Precision, Recall e F1-Score para cada classe, considerando desafios como desbalanceamento e variabilidade sonora intrínseca.

Por que este projeto é útil?
Este trabalho oferece insights valiosos sobre a aplicação de Transferência de Aprendizado em tarefas de Classificação de Eventos Sonoros (ESC). Ele contribui para o avanço de soluções em áreas como cidades inteligentes e monitoramento ambiental, ao analisar a capacidade de generalização de modelos e identificar desafios específicos na classificação de sons urbanos. Os resultados e a análise detalhada podem guiar futuros aprimoramentos de modelos para cenários do mundo real.

Como começar a usar o projeto?
Para começar a explorar este projeto, que foi desenvolvido para ser executado no Google Colab:

Clone o repositório: git clone [URL_DO_SEU_REPOSITORIO]

Abra os notebooks no Google Colab: Os notebooks Jupyter (.ipynb) estão configurados para instalar todas as dependências necessárias diretamente em suas células de código.

Prepare os datasets:

Baixe o dataset ESC-50 em: https://github.com/karolpiczak/ESC-50
Baixe o dataset UrbanSound8K em: https://urbansounddataset.weebly.com/urbansound8k.html
Após o download, faça upload de ambos os datasets para uma pasta de sua escolha no Google Drive (por exemplo, Meu Drive/datasets/).
Nos notebooks, haverá instruções para montar o seu Google Drive e apontar o caminho para a pasta onde você salvou os datasets.
Sequência de Execução dos Notebooks:
Para uma experiência completa e para reproduzir os resultados, siga a ordem de execução dos notebooks e o propósito de cada um:

ESC-50_R11_GH.ipynb: Este notebook realiza o pré-treinamento do modelo RACNN utilizando o dataset ESC-50. Ele estabelece a base para a transferência de aprendizado.
Analise_UrbanSound8K_GH.ipynb: Dedicado à análise exploratória e preparação do dataset UrbanSound8K, incluindo a compreensão da distribuição das classes e características dos áudios.
UrbanSound8K_R6_GH.ipynb: Este é o notebook central onde ocorre o finetuning do modelo RACNN (pré-treinado no ESC-50) para a tarefa de classificação no UrbanSound8K, incluindo a metodologia de validação cruzada de 10 folds e a geração das métricas de desempenho.
Analises_Graficas_GH.ipynb: Utilizado para gerar visualizações e gráficos a partir dos resultados obtidos no notebook anterior, facilitando a interpretação das métricas de Precision, Recall, F1-Score e outros padrões de desempenho do modelo.
Onde obter ajuda com o projeto?
Se você tiver dúvidas, encontrar problemas ou precisar de ajuda com o projeto, por favor, abra uma "Issue" diretamente neste repositório do GitHub.

Quem mantém e contribui para o projeto?
O principal mantenedor e contribuidor deste projeto é: Artur.
