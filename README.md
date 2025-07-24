# INF1771 – Trabalho 3: Aprendizado de Máquina

## Descrição  
Este repositório contém o desenvolvimento de modelos preditivos para dois problemas de classificação, usando exclusivamente a ferramenta Orange:  
- **Análise de Crédito**: prever aprovação (+) ou não (–) de crédito a partir de atributos anonimizados A1–A12;  
- **Avaliação de Carros**: classificar carros em _unacc_, _acc_, _good_ ou _v‑good_ com base em suas características :contentReference[oaicite:0]{index=0}.

## Datasets  
- **Credit Approval**: atributos numéricos e categóricos A1–A12, classe binária (+/–).  
- **Car Evaluation**: atributos nominais como _buying_, _maint_ e _safety_, classe com quatro níveis de qualidade :contentReference[oaicite:1]{index=1}.

## Tarefas  

1. **Análise Exploratória de Dados**  
   - Estatísticas descritivas (média, desvio padrão, correlações);  
   - Visualizações: Distribution, Scatter Plot, Heat Map, Linear Projection, Tree Viewer;  
   - Identificar possíveis padrões e redundâncias.

2. **Seleção de Atributos**  
   - Aplicar PCA para reduzir dimensionalidade e extrair pesos de atributos;  
   - Utilizar MDS para visualizar separabilidade e escolher atributos relevantes;  
   - Comparar uso de atributos selecionados vs. uso direto de componentes PCA.

3. **Geração de Modelos**  
   - Testar algoritmos: Árvore de Decisão, Random Forest, K‑NN, SVM, Rede Neural (Backpropagation) e Regressão Linear;  
   - Dividir dados em treino/teste via “Test and Score” do Orange;  
   - Ajustar parâmetros para maximizar acurácia e identificar o melhor modelo.

4. **Carga e Separação de Dados**  
   - Carregar com “File” + visualizar em “Data Table”;  
   - Separar treino (70 %) e teste (30 %) com “Data Sampler” (usar “Remaining Data” para teste);  
   - Converter variáveis nominais em ordinais com “Continuize” quando necessário.

## Ferramentas e Requisitos  
- **Plataforma**: Orange (sem implementar algoritmos em código);  
- **Artefatos a entregar**: relatório (mín. 2 páginas), arquivo de workflow (.ows) e screenshot da rede no Orange.
