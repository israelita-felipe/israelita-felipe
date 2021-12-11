# Olá, me chamo Israel Araújo. Tudo bem?

## Um pouco de minha formação:

Sou **Bacharel em Ciência da Computação** [2011-2017] pela UFRPE/UAG atualmente [UFAPE](http://ufape.edu.br/) com foco em [Inteligência Artificial Simbólica](http://www.cienciasecognicao.org/revista/index.php/cec/article/view/33/38).

Durante a graduação participei de projetos de **Extensão** envolvendo o Curso de Graduação em Letras e o Curso de Ciência da Computação. O qual propomos a criação de uma plataforma de ensino de **Latim** para auxiliar nas aulas ministradas na Graduação.

Fui **Monitor** da disciplina de Inteligência Artificial e Tópicos Avançados em Inteligência Atificial. O foco da monitoria era construção de [Ontologias](https://ww2.inf.ufg.br/sites/default/files/uploads/relatorios-tecnicos/RT-INF_001-07.pdf)
e processo de raciocínio utilizando o [Tableau](https://hal.archives-ouvertes.fr/hal-02090087v2/document) por meio da [OWL-API](https://github.com/owlcs/owlapi/wiki) e [Pellet](https://github.com/Galigator/openllet).
Ainda, investigávamos metodos de [Extração de Informação](https://towardsdatascience.com/from-text-to-knowledge-the-information-extraction-pipeline-b65e7e30273e) e [Processamento de Linguagem Natural](https://towardsdatascience.com/your-guide-to-natural-language-processing-nlp-48ea2511f6e1) utilizando o [Stanford Parser](https://nlp.stanford.edu/software/lex-parser.shtml).

**Iniciação Científica**, da qual realizei grande parte da pesquisa de meu Trabalho de Conclusão de Curso e fui bolsista durante 12 meses;

Alcancei meu título de Bacharel em Ciência da Computação ao desenvolver um [Chatterbot](https://www.researchgate.net/publication/341730184_An_Overview_of_Chatbot_Technology) capaz de criar Ontologias e realizar raciocínio em tempo de modelagem de conhecimento.

Sou **Mestre em Ciência da Computação** [2017-2019] pelo Centro de Informática ([CIn](https://portal.cin.ufpe.br/)) da [UFPE](https://www.ufpe.br/), onde adquiri o título pela extensão do meu trabalho de graduação, onde inseri mecanismos de [Aprendizagem de Máquina](https://www.sciencedirect.com/topics/computer-science/machine-learning) para uma melhor construção de conhecimento ontológico.

Possuo formação como **Técnico em Análise e Desenvolvimento de Sistemas** [2019-2021] pela ETE/PE PROFESSOR ANTÔNIO CARLOS GOMES DA COSTA Polo ANTÔNIO DOURADO CAVALCANTI, onde foquei no estudo de tecnologias voltadas ao mercado de trabalho.

## Atuação no mercado de trabalho:

Sou servidor público municipal efetivo da Cidade de [Lajedo/PE](https://www.lajedo.pe.gov.br/) lotado como **Auxiliar Administrativo II** [2012-atual] na Secretaria Municipal de Finanças. Atuei como Tesoureiro Substituto em 2015 [janeiro à julho] e como Diretor de Tributação e Rendas em 2019 [janeiro à julho]. Realizei uma pausa no exercício da função no período de agosto/2015 à dezembro/2018, período este que utilizei para concluir a Graduação e o Mestrado. 
Durante esse período desenvolvi agumas soluções computacionais para auxiliar na gestão administrativa. Descritos na seção **Projetos do qual participei**.

## Projetos do qual participei:

### SAL - PREFEITURA DE LAJEDO [~2014] - Sistema de Aviso de Lançamento

**TIPO:** Pessoal/Profissional

**Descrição:** Esse sistema importa arquivos de extratos bancários do Banco do Brasil e da Caixa Econômica Federal e identifica apenas os créditos realizados nas datas.  O software auxiliava no lançamento de receitas da Prefeitura contabilizando o montante por data e conta e exibindo relaório para que posteriormente fossem lançadas as receitas em sistema contábil próprio.

**Tecnologias:** 

1. Java Desktop (Swing);
2. Banco de Dados Derby (embarcado);
3. Hibernate para manipulação do Banco de Dados

**Metodologia de Desenvolvimento:**

1. Tamanho da equipe de desenvolvimento: 1;
2. Stakeholders: 3;

### CashFinder - PREFEITURA DE LAJEDO [~2014-2015]

**TIPO:** Pessoal/Profissional

**Descrição:** Aplicativo desktop que realiza a integração entre extrato bancário e relatório de sistema de tributação. A Caixa Econômica Federal ao depositar as taxas emitidas pela Prefeitura não possuia uma ordem de valores, podendo depositar várias quantidades em um mesmo dia ou juntar vários dias para fazer diferentes depósitos. 
Nesse contexto ao comparar o extrato bancário com o relatório de arrecadação de taxas do sistema de tributação, hão havia correspondência entre os valores.
Assim, a soma de diversos valores correspondiam a um valor do relatório tributário. Na computação esse problema é conhecido como [Subset Sum](https://www.geeksforgeeks.org/subset-sum-problem-dp-25/) (Somas parciais). Para mitigar esse problema foi desenvolvido um software que utiliza uma implemetação do CPLEX formecida pela IBM em Java. 
O tempo de identificação, antes realizado de forma manual, passou de dias para minutos, economizando horas de trabalho.

**Tecnologias:**

1. Java Desktop (Swing);
2. CPLEX - IBM
3. Modelagem Matemática

**Metodologia de Desenvolvimento:**

1. Tamanho da equipe de desenvolvimento: 1;
2. Stakeholders: 3;

### ARUAGI - UFRPE [2014-2015]

**TIPO:** Institucional/Projeto de Extensão

**Descrição:** O [ARUAGI](https://docplayer.com.br/18054063-Tecnologias-para-o-ensino-superior-desafios-na-formacao-do-professor.html) Foi proposto por uma parceria entre o Curso de Ciência da Computação e o Curso de Letras da UFAPE inicialmente em 2014 como um software mediador do ensino de Latim na Universidade.
Era composto por atividades que os professores podiam montar e passar para seus alunos de forma personalizada funcionando assim como uma plataforma de ensino.

**Tecnologias:**

1. Java Web: Servlets, Java Server Faces (JSF);
2. Hibernate;
3. Banco de Dados [PostgreSQL](https://www.postgresql.org/);
4. JavaScript;
5. CSS;
6. HTML;
7. MVC (Modelo: Model-View-Control)
8. Bootstrap

**Metodologia de Desenvolvimento:**

1. Desenvolvimento em Cascata/Incremental;
2. Foco no desenvolvimento e documentação (para apresentação de relatório e eventos);
3. Encontros presenciais mensais;
4. Tamanho da equipe de desenvolvimento: 3;
5. Stakeholders: 5;

### PUPO - UFRPE [2015-2017]

**TIPO:** Institucional/Iniciação científica/Trabalho de Conclusão de Curso

**Descrição:** O desenvolvimento do PUPO iniciou-se na Iniciação Científica e extendeu-se até o fim da gradução. Foi proposto um Chatterbot capaz de a partir de diálogo extrair e modelar conhecimento em Ontologias; e, realizar raciocíono em tempo de modelagem de conhecimento. O PUPO facilita o processo de modelagem escondendo o processo complicado de manipulação direta de OWL e retornando inferências ao usuáro fornecidas em linguagem natural.

**Tecnologias:**

1. Java Desktop: Swing;
2. MVC (Modelo: Model-View-Control)
3. Stanford Parser
4. Openllet
5. OWL-API

**Metodologia de Desenvolvimento:**

1. Desenvolvimento em Cascata/Incremental;
2. Foco no desenvolvimento e documentação (para apresentação de relatório e eventos);
3. Encontros presenciais semanais;
4. Tamanho da equipe de desenvolvimento: 1;
5. Stakeholders: 2;

### PUPO 2 - UFPE/CIn [2017-2019]

**TIPO:** Institucional/Dissertação

**Descrição:** O desenvolvimento do PUPO 2 adicionou ao PUPO a capacidade de utilizar aprendizagem de máquina para melhor modelar conhecimento. Extraindo informações mais coerentes por meio de uma SVM e confrontando essas informações, agora axiomas, com uma Ontologia de topo a SUMO. 
Refinando ainda mais o conhecimento modelado. O PUPO 2 permite uma expressividade maior (ALCHOQ) que sua versão anterior.

**Tecnologias:**

1. Java Web: Spring Framework;
2. Thymeleaf;
3. Hibernate: Spring JPA;
4. JavaScript;
5. CSS;
6. HTML;
7. Banco de dados H2
8. Bootstrap
9. MVC (Modelo: Model-View-Control)
10. Stanford Parser
11. Openllet
12. OWL-API
13. SVM (Support Vector Machine)
14. SUMO (SUper Merged Ontology)
15. Weka

**Metodologia de Desenvolvimento:**

1. Desenvolvimento em Cascata/Incremental;
2. Foco no desenvolvimento e documentação (para apresentação de relatório e eventos);
3. Encontros presenciais mensais;
4. Tamanho da equipe de desenvolvimento: 1;
5. Stakeholders: 3;

### Sistema Gestor de Frota [2019-2020]

**TIPO:** Empresarial

**Descrição:** Foi desenvolvido para uma empresa de tecnologia um ecossistema de controle de abastecimento de frota. Ateriormente todo o processo era realizado de forma escrita.
Um técnico da empresa ao precisar abastecer o veículo deveria ir a sede pegar uma autorização escrita e levar até o posto de abastecimento. Ao final do mês o posto apresentava todas as notas e recebia seu pagamento.
Para automatizar esso processo foi desenvolvido um sistema dividido em 3 (três) módulo. Um servidor RestFull, um aplicativo para android e uma interface web.
A interface web é utilizada no escritório da empresa pelos supervisores, assim podem aprovar ou recusar uma solicitação realiza por um técnico.
O aplicativo android é de responsabilidade do técnico, que realiza a requisição fotografando o painel do veículo e identificando sua placa. 
Por fim o sistema mensalmente emite relatórios contabilizando os abastecimentos por cada posto de combustível. 
Dessa forma o sistema desburocratizou e agilizou o processo de abastecimento da frota da empresa.

**Tecnologias:**

1. Java Web: Spring Framework, Spring Boot, Spring Security;
2. Thymeleaf;
3. Hibernate: Spring JPA;
4. JavaScript;
5. CSS;
6. HTML;
7. Banco de dados PostgreSQL
8. Bootstrap
9. MVC (Modelo: Model-View-Control)
10. RestFull
11. Android

**Metodologia de Desenvolvimento:**

1. Desenvolvimento em Ágil (Scrum adaptado);
2. Encontros virtuais mensais (ou conforme solicitado);
3. Tamanho da equipe de desenvolvimento: 1;
4. Stakeholders: 4;

### Sistema Gestor de Contas [2021]

**TIPO:** Pessoal/Profissional

**Descrição:** A aplicação busca por Faturas das empresas prestadoras de serviço de Energia Elétrica (CELPE/NEOENERGIA) e Saneamento e Abastecimento (COMPESA) vinculadas a Prefeitura, realiza o Download das mesmas e armazena em banco de dados. Esse processo até então era realizado de forma manual.
Uma de duas vantagens é o armazenamento histórico de suas faturas, e impressão de relatórios e faturas estruturadas prontos para realizar liquidação da despesa pública.

**Tecnologias:**

1. Java Desktop: JavaFX;
2. Spring Framework, Spring Boot;
3. Hibernate: Spring JPA;
4. Banco de dados h2
5. Jaspersoft para relatório
6. [htmlunit](https://htmlunit.sourceforge.io/)
7. MVC/MVP (Modelo: Model-View-Control/Presenter)

**Metodologia de Desenvolvimento:**

1. Tamanho da equipe de desenvolvimento: 1;
2. Stakeholders: 2;

## Conhecimento em:

1. Java:
  1.1. Web Servlet
  1.2. Web Spring Framework
    1.2.1. Spring Boot
    1.2.2. Spring Security
    1.2.3. Spring JPA
  1.3. Web Thymeleaf
2. PostgreSQL
3. HTML
4. CSS
5. JAVASCRIPT
6. Jaspersoft
7. Hibernate
8. JavaFX
9. Java Swing
10. REST/RESTFULL
11. OWL
12. Stanford Parser
13. Processamento de Linguagem Natural
14. Modelagem de Conhecimento
15. Bootstrap
16. Weka
17. SQL
18. SUMO
19. OWL-API
20. Openllet
21. Aprendizagem de Máquina
22. SQL

## Contato:

Lattes: [http://lattes.cnpq.br/0444370129900667](http://lattes.cnpq.br/0444370129900667)\
E-mail: [israelita.felipe@gmail.com](mailto:israelita.felipe@gmail.com)\
LinkedIn: [https://www.linkedin.com/in/israel-araújo-15b27128/](https://www.linkedin.com/in/israel-ara%C3%BAjo-15b27128/)
