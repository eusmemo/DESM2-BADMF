
# Desafio Módulo 2: Fundamentos em Ciências de Dados

***

### Enunciado

Você foi selecionado por um prestigiado hospital para desenvolver um modelo de classificação capaz de identificar pacientes com elevado risco de sofrer um
ataque cardíaco. Como cientista de dados, você reconhece a importância crucial de detectar esses casos precocemente, visando proporcionar intervenções preventivas oportunas e salvar vidas. O hospital dispõe de um extenso conjunto de dados médicos, contendo informações de histórico médico, exames laboratoriais e registros de sintomas de diversos pacientes.
Esses dados foram meticulosamente coletados ao longo de vários anos e incluem informações sobre pacientes que tiveram ataques cardíacos confirmados, assim como aqueles que não tiveram.

Seu propósito é criar um modelo de classificação utilizando o algoritmo Random Forest, que seja competente para analisar essas informações e identificar padrões e características-chave indicativos de um elevado risco de
ataque cardíaco. Isso viabilizará aos profissionais de saúde concentrarem seus esforços nos pacientes que mais necessitam de cuidados e intervenções
preventivas.

Seu papel como cientista de dados é de extrema relevância, pois contribui para a saúde e bem-estar dos pacientes, disponibilizando aos profissionais
médicos uma ferramenta valiosa para a detecção precoce e intervenção adequada em casos de elevado risco de ataques cardíacos.

Informações sobres os dados do dataset:

![](./doc_img/dataset_info.png)

***

### Atividades

Para este desafio, os alunos deverão realizar as seguintes atividades:

1. Criar uma virtualenv e instalar as bibliotecas necessárias.
2. Coletar o arquivo heart.csv.
3. Analisar os dados coletados.
4. Avaliar a necessidade de tratamentos de dados ausentes.
5. Criação modelo de Random forest Classifier.
6. Avaliar os resultados obtidos.
7. Responder às questões teóricas e práticas do trabalho.

***

### Dicas do professor:

1. Analise com cuidado os dados.
2. Realize todo tratamento de dados antes de responder às questões.
3. Antes de enviar as respostas, verifique se o gabarito está correto.
4. Atenção no momento de filtrar e corrigir dados (se necessário).
5. Tenha atenção no que pede cada questão.
6. Realize o balanceamento dos dados.
    1. RandomUnderSampler(random_state = 42)
    2. TomekLinks(sampling_strategy='all')
7. Separe 80% dos dados para treinar o algoritmo e 20% para testar.
    1. Utilize o parâmetro de random_state=42.
8. Elimine dados duplicados, caso existam.
9. Siga fielmente todos os passos contidos no enunciado das questões.
10. dataset utilizado no trabalho pode ser obtido no link:

    - <https://github.com/ProfLeandroLessa/classroom-datasets/tree/master/ANC/BTC%201/Desafio>

11. Outras dicas de análises de dados e geração de gráficos em:

    - <https://leandrolessa.com.br/tutoriais/grafico-de-dispersao-como-criar-e-analisar-na-pratica/>

12. Abaixo segue as versões utilizadas das bibliotecas neste trabalho:

    ![](./doc_img/lib_version.png)

***

### <font color="red">ATENÇÃO PARA TRATAMENTO DE DADOS</font>

Avalie se será necessário realizar tratamento de dados ausentes no datasets
disponibilizado.

Instruções para correção de dados ausentes
1. Para dados numéricos, utilize a estratégia de exclusão dos dados.
2. Para os dados categóricos, utilize a moda dos valores da coluna.

***
