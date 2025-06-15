<!-- antes de enviar a versão final, solicitamos que todos os comentários, colocados para orientação ao aluno, sejam removidos do arquivo -->
# Nome do projeto

#### Aluno: [Jorge Antonio da Costa Mattos](https://github.com/JorgeACMattos-BI/bi-master-final-project)
#### Orientadora: [Nome Sobrenome](https://github.com/link_do_github).
#### Co-orientador(/a/es/as): [Nome Sobrenome](https://github.com/link_do_github). <!-- caso não aplicável, remover esta linha -->

---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

<!-- para os links a seguir, caso os arquivos estejam no mesmo repositório que este README, não há necessidade de incluir o link completo: basta incluir o nome do arquivo, com extensão, que o GitHub completa o link corretamente -->
- [Link para o código](https://github.com/link_do_repositorio). <!-- caso não aplicável, remover esta linha -->

- [Link para a monografia](https://link_da_monografia.com). <!-- caso não aplicável, remover esta linha -->

- Trabalhos relacionados: <!-- caso não aplicável, remover estas linhas -->
    - [Nome do Trabalho 1](https://link_do_trabalho.com).
    - [Nome do Trabalho 2](https://link_do_trabalho.com).

---

### Resumo

Este projeto visa desenvolver um modelo de otimização para a alocação de sondas offshore em poços exploratórios no Brasil. Utilizando dados simulados e ferramentas de programação linear inteira em Python, o modelo busca minimizar custos operacionais e maximizar a eficiência das campanhas.

### Abstract <!-- Opcional! Caso não aplicável, remover esta seção -->

This project aims to develop an optimization model for the allocation of offshore rigs in exploratory wells in Brazil. Using simulated data and integer linear programming tools in Python, the model aims to minimize operational costs and maximize campaign efficiency.

### 1. Introdução

A contratação de sondas offshore representa uma parte significativa dos custos das campanhas exploratórias no setor de óleo e gás. Este trabalho propõe um modelo de otimização para apoiar a tomada de decisão, considerando variáveis técnicas, ambientais e financeiras, com foco em poços exploratórios no Brasil.

### 2. Modelagem

O modelo foi desenvolvido em Python, utilizando a biblioteca PuLP para a modelagem de programação linear inteira. Os dados de entrada incluem características técnicas das sondas e poços, além de parâmetros de custo e restrições operacionais. O modelo visa:

- Minimizar o custo total de operação das sondas.
- Garantir que cada poço seja atendido por uma sonda compatível.
- Considerar setups, janelas de parada e outros parâmetros logísticos.

Os dados utilizados no projeto são simulados, com base em estruturas públicas da ANP e conhecimento técnico da operação. Eles incluem:

- sondas.csv: Dados técnicos das sondas (tipo, profundidade máxima, capacidade, BOP, etc.).
- pocos.csv: Dados técnicos dos poços (profundidade, ambiente, janela de perfuração, etc.).
- relatorio_final.pdf: relatório com resultado da otimização da campanha, com alocação dos poços em gráfico e tabela com valores calculados e custo total da campanha.

Tecnologias Utilizadas
- Python 3.x
- Pandas: manipulação e análise dos dados.
- PuLP: modelagem de programação linear inteira.
- Plotly / Matplotlib: visualização de resultados (Gantt e dashboards).
- Jupyter Notebook: desenvolvimento e documentação do modelo.
- GitHub: versionamento e entrega final.

### 3. Resultados

Este projeto visa gerar resultados que demonstrem:

- A alocação ótima das sondas para cada poço, minimizando custos operacionais e respeitando todas as restrições técnicas.
- Um cronograma claro e visualmente intuitivo (Gantt) para cada campanha de perfuração, facilitando o entendimento operacional.
- Indicadores de eficiência, como utilização das sondas, custos totais e distribuição das janelas de operação.
- A viabilidade e robustez do modelo para futuras expansões ou integração em sistemas corporativos.

### 4. Conclusões

A proposta apresentada alia conceitos acadêmicos de otimização com desafios reais do setor de óleo e gás. Mesmo com dados simulados, a modelagem e os outputs permitem entender a aplicabilidade de soluções de ciência de dados e programação linear inteira para auxílio na tomada de decisões estratégicas para contratação de sondas offshore.

O trabalho reforça a importância de projetos que conectam teoria e prática, mostrando como ferramentas de dados podem apoiar a redução de custos e a maximização da eficiência em soluções de alta complexidade.

---

Matrícula: 222.100.473

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*
