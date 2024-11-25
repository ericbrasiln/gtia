## Introdução

**a) Resumo Geral**  
A análise dos dados coletados sobre o uso de Inteligência Artificial (IA) no ensino e pesquisa na UNILAB revela percepções, desafios e possibilidades identificadas pelos docentes. O objetivo principal foi compreender como essas ferramentas estão sendo integradas às práticas acadêmicas e propor estratégias para promover o uso ético e produtivo da IA no ambiente universitário.

**b) Metodologia Usada**  
Os dados foram coletados por meio de um questionário aplicado exclusivamente a docentes, abordando questões relacionadas às ferramentas utilizadas, contribuições para o ensino e pesquisa, desafios enfrentados e sugestões de políticas institucionais. As respostas foram categorizadas e analisadas qualitativamente, com destaque para temas recorrentes e pontos críticos apontados pelos participantes.

**c) Principais Resultados**  
1. **Uso de Ferramentas de IA**: Ferramentas como ChatGPT, Prezi e Mentimeter foram destacadas para tarefas como planejamento de aulas, criação de materiais didáticos e apoio à comunicação.  
2. **Contribuições para o Ensino e Pesquisa**: A IA é vista como potencial para automação de tarefas, personalização do aprendizado e análise de grandes volumes de dados.  
3. **Desafios Identificados**: Os principais desafios incluem questões de plágio, dificuldade em avaliar trabalhos gerados por IA e barreiras técnicas, como custo e falta de ferramentas acessíveis.  
4. **Propostas de Melhoria**: Os docentes sugerem capacitação contínua, criação de diretrizes institucionais e disponibilização de ferramentas específicas para promover o uso ético e eficaz da IA.

Esta análise fornece subsídios para futuras discussões e ações voltadas ao aprimoramento do uso de IA na UNILAB, fomentando práticas que alavanquem a qualidade do ensino e da pesquisa acadêmica.

---

## Metodologia Detalhada

**Ferramentas Utilizadas**
- **Jupyter Notebook**: Utilizado como ambiente principal para desenvolver o código e realizar as análises.
- **Quarto**: Ferramenta utilizada para renderizar o notebook e transformá-lo em uma visualização final acessível em HTML.
- **Python**: Linguagem de programação empregada, com foco nas seguintes bibliotecas:
  - **Pandas**: Para leitura, manipulação e limpeza dos dados.
  - **Plotly**: Para geração de gráficos interativos.
  - **Wordcloud**: Para criar nuvens de palavras representando a frequência de termos utilizados.

**Etapas da Análise**

1. **Coleta e Leitura dos Dados**
   - Os dados foram coletados via formulário online e armazenados em um arquivo CSV.
   - A leitura dos dados foi realizada com o Pandas:
     ```python
     import pandas as pd
     data = pd.read_csv("dados_docentes.csv")
     ```

2. **Limpeza e Filtragem**
   - Foram removidas colunas irrelevantes, como "Carimbo de data/hora" e respostas de não-docentes.
   - Tratamento de valores ausentes e padronização das respostas para facilitar a análise.

3. **Análise Temática**
   - **Familiaridade com IA**: Contagem das respostas e criação de gráficos de barras.
   - **Ferramentas Utilizadas**: Análise textual para identificar ferramentas mais mencionadas, representadas em uma nuvem de palavras.
   - **Contribuições e Desafios**: Categorização das respostas para identificar padrões recorrentes e preocupações.

4. **Visualização**
   - Utilização de **Plotly** para gráficos interativos que representam os resultados de forma clara.
   - Geração de uma nuvem de palavras para destacar as ferramentas de IA mais mencionadas.

5. **Renderização e Publicação**
   - O Jupyter Notebook foi exportado e renderizado com **Quarto** para criar a visualização final no formato HTML.
   - O Quarto permitiu integrar o conteúdo e os gráficos em uma interface acessível e navegável, ideal para compartilhamento público.

6. **Repositório e Transparência**
   - Todos os códigos, dados brutos e análises estão disponíveis em um repositório no GitHub, garantindo transparência e reprodutibilidade da pesquisa.

