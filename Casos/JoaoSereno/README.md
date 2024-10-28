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

* Efficiency
  * RQ1: How effectively does the proposed protocol balance energy loads across devices in managed IoT networks?
  * RQ2: What impact does the protocol have on overall energy consumption compared to unmanaged IoT networks?
* Scalability
  * RQ3: How well does the protocol handle an increasing number of devices without degradation in performance or efficiency?
  * RQ4: Are there limits to the network size and complexity within which the protocol can operate efficiently?
* Reliability
  * RQ5: Can the protocol maintain stable network operations under varying load conditions and fluctuating energy availability?
  * RQ6: How does the protocol handle unexpected power demands or failures within the network?
* Adaptability
  * RQ7: How quickly and accurately does the protocol respond to real-time changes in energy demand and environmental conditions?
  * RQ8: Can the protocol dynamically adjust to both short-term (real-time) and long-term (scheduled) energy needs of devices?
* Priority Management
  * RQ9: How effective is the protocol in allocating resources to high-priority devices without compromising the needs of lower-priority ones?
  * RQ10: What are the most suitable criteria for determining device priority within the network?
* Security and Integrity
  * RQ11: How secure is the protocol’s communication framework in terms of protecting data exchanged between IoT devices and the central load balancer?
  * RQ12: What mechanisms are in place to prevent unauthorized access or manipulation of energy load settings?
* Resource Optimization
  * RQ13: Does the protocol lead to observable cost savings in energy consumption over time?
  * RQ14: How does the protocol influence device lifespan by reducing energy spikes and preventing overloads?
* Comparative Performance
  * RQ15: How does the proposed protocol compare to other existing energy management protocols or algorithms in terms of efficiency, reliability, and scalability?
  * RQ16: What are the benefits and potential drawbacks of a centralized load balancer in IoT networks compared to a decentralized approach?
* Environmental Impact
  * RQ17: How does the protocol contribute to sustainable energy practices within IoT networks?
  * RQ18: Does the protocol help in reducing carbon footprint or other environmental impacts by minimizing unnecessary power usage?
*User and Device Feedback
  * RQ19: How do end-users perceive the performance of IoT devices under the proposed protocol’s management?
  * RQ20: Is there evidence of improved device performance or user satisfaction due to more stable energy provision?

The authors used the Petticrew and Roberts (CITACAO) Population, Intervention, Comparison, Outcome and Context (PICOC).

* Population: Managed IoT networks with various connected devices requiring efficient energy use.
* Intervention: Protocols and techniques for energy load balancing and dynamic power distribution across IoT devices.
* Comparison: Different energy management strategies, such as centralized vs. decentralized protocols or priority-based vs. uniform distribution methods.
* Outcome: Optimized energy consumption, extended device lifespan, and improved stability of IoT networks under fluctuating energy loads.
* Context: IoT environments where energy efficiency is crucial, such as smart cities, industrial IoT applications, and home automation systems.

Based no PICOC following the approached recomended by Kitchmen and Charters (REF) the search criteria was the following: 

Keywords:
"Energy load balancing," "IoT energy management," "dynamic power allocation," "centralized vs. decentralized load balancing," "priority-based energy distribution," "smart energy protocols," "managed IoT networks," "energy optimization in IoT."

* Inclusion Criteria:
  * Peer-reviewed articles, 
  * technical reports, or industry publications on energy management and load balancing in IoT.
  * Studies that specifically address energy efficiency and load management within IoT network protocols.

* Exclusion Criteria:
  * General articles on IoT without focus on energy management or load balancing.
  * Studies that do not address managed IoT networks or are focused solely on theoretical models without practical application.

Based on this keywords we will search on the following databases:
* SpringerLink, 
* Science@Direct, 
* IEEE Digital Library
* ACM Digital Library.

The articles idenfitied can be placed on a resume board with the article number in the different datab bases.

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
