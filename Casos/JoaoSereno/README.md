# Laboratório de Investigação

Investigar consiste em identificar problemas, colocar questões, refletir, admitir erros, aprender novas coisas e tentar encontrar soluções utilizando um método científico, o que pode ser recompensador:

![Job Offer](./img/oferta.jpg)

Documentação e recursos para a disciplina de Laboratório de Investigação. Como é que podemos abordar o problema, onde se procura responder a questões como:
* Como é que podemos fazer uma revisão de literatura? 
* Como é que podemos fazer uma pesquisa bibliográfica? 
* Quais são as ferramentas que podemos utilizar?
* Como é que podemos utilizar ASReview para a seleção de artigos? 
* Como é que podemos utilizar o Zotero para a gestão de referências bibliográficas?
* Como é que podemos utilizar a inteligência artificial para apoiar a investigação?

# Workflow para a elaboração de um plano de investigação
* Qual é o problema subjacente à investigação do estudo ou projeto? 
  * Formular uma questão de investigação
  * Depois de formular a questão de investigação, podemos definir sub-questões, e.g. Questão qual é o impacto da pandemia COVID-19 no ensino à distância? Sub-questões: Quais são as vantagens e desvantagens do ensino à distância? Quais são as ferramentas tecnológicas mais utilizadas no ensino à distância? Quais são as competências necessárias para o ensino à distância?
  * Explicar sucintamente cada uma das sub-questões, frase curtas, 1 ou 2 linhas
* Utilizar o PICOC (Population, Intervention, Comparison, Outcome, Context) como base para a criar a 'string' de pesquisa:
* Exemplificar uma questão de investigação e sub-questões a partir de um problema dos alunos
* Ferramentas que podemos utilizar para fazer uma revisão de literatura:
  * Exemplificar com um problema dos alunos como se faz uma revisão de literatura
  * Utilização do [Parsifal](https://parsif.al/about/) para ajudar nos objectivos, PICOC, questões de pesquisa, search string, keywords e sinónimos, seleção das fontes, critérios de inclusão e exclusão, bem como os mecanimos necessários para construir uma checklist para uma checklist para uma avaliação qualitativa e formulários extração de dados.
  * Um ficheiro Excel para a avaliação qualitativa das questões de investigação
  * Como importar os artigos selecionados para o zotero.... TODO...
  * Utilização do Zotero para a gestão de referências bibliográficas
* Pesquisar em bases de dados científicas
  * Scopus (Bom mas é pago e não é acessível a todos)
  * IEEE Digital Library (Conseguimos pesquisar)
  * SpringerLink (Conseguimos pesquisar)
  * Science@Direct (Conseguimos pesquisar)
* Exemplificar com um problema dos alunos como se faz uma pesquisa bibliográfica
* Utilização do ASReview para a seleção de artigos
  * Instalação	e exemplo de utilização do [ASReview](https://asreview.readthedocs.io/en/latest/index.html) 
    * Com conda: `conda install -c conda-forge asreview`
    * Com pip: `pip install asreview`
    * Com docker: `docker run -it asreview/asreview:latest`
  * Importação das referências selecionadas do ASReview para o Zotero
* Utilização do Zotero para a gestão de referências bibliográficas

# Bases de dados

* [ACM Digital Library](http://portal.acm.org)
* [IEEE Digital Library](http://ieeexplore.ieee.org)
* [ISI Web of Science](http://www.isiknowledge.com)
* [PubMed](https://www.ncbi.nlm.nih.gov/pubmed/)
* [Science@Direct](http://www.sciencedirect.comg
g [Scopus](http://www.scopus.com)
* [Springer Link](http://link.springer.com)

# Ferramentas apoio

* [ResearchKit](https://www.researchkick.com/start)
* [Scribbr](https://www.scribbr.com/plagiarism-checker/)
* Bibliometrix
* AI powered literature review and tools for researchers:
  * Revisão de literatura:
    * [Perplexity](https://perplexity.ai/):  Answering questions in a comprehensive and informative way, similar to a search engine but with more conversational abilities
    * [Elicit](https://elicit.com/): Research assistant that uses language models to automate research tasks, such as finding relevant papers, summarizing papers, and answering questions
    * [Sematicscholar](https://www.semanticscholar.org/)
    * [Anysummary](https://www.anysummary.app/)
    * [ChatPDF](https://chatpdf.com/)
  * Definição de hipóteses:
    * Utilização da inteligência artificial generativa para GPT3/4 a partir de uma prompt 

A Prompt mágica

```
You are an expert computer science. Your research interests are in Predictive Analytics, 
Machine Learning, and Data Mining. You are interested in generating hypotheses in the field of 
Computer Science and Artificial Intelligence.
Your task is to generate counterintuitive yet plausible hypotheses. They should
combine different sub fields of Computer Science and advance theoretical knowledge.
They should not be incremental.
Make sure that your hypotheses are precisely stated and incorporate a comparison
group. Begin each hypothesis with "Hypothesize that" and generate 100 hypotheses.
```


# Documentos de apoio

* Etapas gerais para revisão de literatura [aqui](./docs/01.revisao_literatura.pdf)
* Utilização do [Zotero](./docs/02.zotero_Ferramentas.pdf)
* Instalação [Docker](./docs/03.instalacao_docker.pdf), mais simples é mesmo com Anaconda para ASReview


# Exemplo 

## Caso 1

Study Problem: Proposal for a protocol of energy load balancer on a managed IoT
network

Based on this investigation the following questions were formulated:

* RQ1: How effectively does the proposed protocol balance energy loads across devices in managed IoT networks?
* RQ2: Can the protocol maintain stable network operations under varying load conditions and fluctuating energy availability?
* RQ3: Is there evidence of improved device performance or user satisfaction due to more stable energy provision?
* RQ4: How does the protocol contribute to sustainable energy practices within IoT networks?
* RQ5: What are the benefits and potential drawbacks of a centralized load balancer in IoT networks compared to a decentralized approach?

The authors used the Petticrew and Roberts (CITACAO) Population, Intervention, Comparison, Outcome and Context (PICOC).

* Population: Managed IoT networks with various connected devices requiring efficient energy use.
* Intervention: Protocols and techniques for energy load balancing and dynamic power distribution across IoT devices.
* Comparison: Different energy management strategies, such as centralized vs. decentralized protocols or priority-based vs. uniform distribution methods.
* Outcome: Optimized energy consumption, extended device lifespan, and improved stability of IoT networks under fluctuating energy loads.
* Context: IoT environments where energy efficiency is crucial, such as smart cities, industrial IoT applications, and home automation systems.

Based no PICOC following the approached recomended by Kitchmen and Charters (REF) the search criteria was the following: 

Keywords:
Energy load balancing, IoT energy management, dynamic power allocation, centralized vs. decentralized load balancing, priority-based energy distribution, smart energy protocols, managed IoT networks, energy optimization in IoT.

* Inclusion Criteria:
  * Review articles (37)
  * Research articles (35)

* Exclusion Criteria:
  * Book chapters (7)
  * Conference abstracts (8)
  * Mini reviews (8)

Based on this keywords we will search on the following databases:
* [SpringerLink]([https://link.springer.com/search?new-search=true&query=Energy+load+balancing%2C+IoT+energy+management%2C+dynamic+power+allocation%2C+centralized+vs.+decentralized+load+balancing%2C+priority-based+energy+distribution%2Csmart+energy+protocols%2Cmanaged+IoT+networks%2Cenergy+optimization+in+IoT.&content-type=research&content-type=review&date=custom&dateFrom=2020&dateTo=2025&sortBy=relevance](https://link.springer.com/search?date-facet-mode=between&facet-language=%22En%22&query=Energy+load+balancing%2C+IoT+energy+management%2C+dynamic+power+allocation%2C+centralized+vs.+decentralized+load+balancing%2C+priority-based+energy+distribution%2C+smart+energy+protocols%2C+managed+IoT+networks%2C+energy+optimization+in+IoT&facet-end-year=2025&facet-start-year=2020&facet-content-type=%22Article%22)) 
* [Science@Direct](https://www.sciencedirect.com/search?qs=Energy%20load%20balancing%2C%20IoT%20energy%20management%2C%20dynamic%20power%20allocation%2C%20centralized%20vs.%20decentralized%20load%20balancing%2C%20priority-based%20energy%20distribution%2Csmart%20energy%20protocols%2Cmanaged%20IoT%20networks%2Cenergy%20optimization%20in%20IoT.&years=2025%2C2024%2C2023%2C2022%2C2021%2C2020&show=100&subjectAreas=1700%2C2200%2C2100%2C1800&lastSelectedFacet=articleTypes&articleTypes=REV%2CFLA)
* [IEEE Digital Library](https://ieeexplore.ieee.org/search/searchresult.jsp?queryText=Energy%20load%20balancing,%20IoT%20energy%20management,%20energy%20optimization%20in%20IoT.&highlight=true&returnType=SEARCH&matchPubs=true&ranges=2020_2024_Year&returnFacets=ALL&rowsPerPage=100&pageNumber=1)
* ACM Digital Library.

The articles idenfitied can be placed on a resume board with the article number in the different databases.

The research is made by using the title, abstract, and keywords, defining a research interval within the last 5-10 years to ensure that the analysis includes up-to-date technologies and trends in IoT energy management, defining the exclusion criteria (Books, Patents, Master Teases and Articles that are not in English).

To generate the article screening / validation we can use ASReview to help on the selection process and article organization. We should also include the inclusion criteria.

Convém fazer uma contextualização em relação a problema, nomeadamente para perceber como é que se está a investigar, tipo
de terminologia utilizada, por exemplo para perceber que estudos estão a ser feitos para "afinar" as questões de pesquisa e 
termos/sinónimos a utilizar na string de pesquisa para fazer a introdução à revisão de literatura.
Ver exemplo [aqui](https://elicit.com/notebook/6b00c2c5-a34a-4df3-94ee-3db1663e53a5). Depois podem interagir com os PDFs dos artigos e pedirem para resumir as ideias principais, utilizando por exemplo ChatPDF ou analisando com mais detalhe, lendo com 
algum cuidado os artigos.
Outro aspeto importante é perceber se existem revisões de literatura similares ao que estão a fazer e não fazer o mesmo. Caso
existam, tentar alterar o âmbito ou o problema de estudo para diferenciar.

# Bibliografia

Biggam, J. (2021). Succeeding with Your Master’s Dissertation: A Step-by-Step Handbook. McGraw-Hill Education.
Dawson, C. (2019). Introduction to Research Methods 5th Edition: A Practical Guide for Anyone Undertaking a Research Project. Robinson
Press.
