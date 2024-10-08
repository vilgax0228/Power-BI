# Learning Microsoft Power BI: Transforming Data Into Insights de *Jeremey Arnold*.

Como reunimos dados de diferentes fontes? Como lidamos com tabelas que são grandes demais para o Microsoft Excel? Como direcionamos grupos específicos ou subconjuntos de um grupo para análise de forma eficaz? Como visualizamos esses resultados para torná-los compreensíveis para nossa audiência?

![catBI](https://github.com/user-attachments/assets/75b49b0a-1fea-4b27-81c1-f1398a639537)

## Capítulo 1. Introdução ao Power BI
O **Power BI** é tanto um software quanto um ecossistema maior de produtos. Quando se discute como a maioria das pessoas irá compartilhar visualmente os resultados de seu trabalho com os outros, isso é feito no contexto do Power BI service, uma solução de software como serviço (*SaaS*) que hospeda conjuntos de dados e relatórios do Power BI, que podem ser utilizados por outros que têm acesso.

Esse livro foca no Power BI Desktop e no Power BI service pois são esses os blocos de construção mais básicos e valiosos.

O **Power BI Desktop** é uma ferramenta para investigação e visualização de dados. Analistas podem utilizar dados e criar relatórios interativos que permitem aos usuários finais obter insights que antes estavam ocultos.

No setor financeiro, você pode usar o Power BI para automatizar a geração de demonstrações de lucros e perdas (P&L) ou analisar os custos ao longo do tempo.

No setor de varejo, você pode identificar quais de seus produtos são os mais bem-sucedidos, ao mesmo tempo em que destaca quais estão prestes a decolar, caso recebam um pouco mais de incentivo por meio de uma análise de cenários hipotéticos (*what-if analysis*).

O **Power BI service** é uma solução online de SaaS que permite que os usuários finais compartilhem relatórios criados no Power BI Desktop com usuários de toda a organização.

### Power BI Desktop
O Power BI Desktop é um software que permite você conectar, transformar e visualizar dados. O Power BI Desktop é composto por seus próprios componentes. São eles:

O **Power BI Canvas** é o lugar onde você constrói visualizações. Aqui, você usará a funcionalidade de arrastar e soltar para inserir informações em diferentes visualizações, explorar seus dados e obter insights. Este também é o local onde você aplicará formatação às visualizações, adicionará imagens, caixas de texto e muito mais.

O **Power Query** é usado para importar e manipular dados, essencialmente moldando-os. No Power BI, diferentemente do Excel, por exemplo, você não edita células de dados; em vez disso, você manipula colunas de dados usando suas funções, assistentes e fórmulas.

O Power Query oferece opções para criar colunas personalizadas com base em regras que você define. Ele permite combinar várias tabelas de dados ou adicionar valores de uma tabela a outra.

Tudo no Power Query começa com a obtenção de dados de suas fontes, e o Power Query suporta uma enorme variedade de fontes de dados. Se conectar a um banco de dados SQL, a uma planilha do Excel para obter uma tabela, valores separados por vírgula (csv) ou fontes na nuvem.

Existem também *M* (a linguagem de programação do Power Query) e *DAX* (data analysis expressions) que são tópicos mais avançados.

### Power BI service
O Power BI service, uma solução SaaS online, permite com que usuários compartilhem seus relatórios do Power BI Desktop com outros usuários dentro da organização.

Todo mundo tem acesso ao seu próprio *workspace* pessoal de graça, mas apenas um.

Para compartilhar relatórios com outros usuários você precisa criar um novo workspace e convidar eles para esse workspace.

Desse jeito, o Power BI service deixa que outros usuários finais explorem relatórios que você criou para conseguir insights de seu trabalho.

O Power BI service também possui diversas outras *features*, como a capacidade de criar objetos especiais conhecidos como *dataflows*.

Esses dataflows podem ser usados para pegar informação no Power BI service fora de uma base de dados, enquanto permite que usuários finais tenham acesso a esses dados e combine com outros dados dentro de um modelo do Power BI Desktop.

Os desenvolvedores podem gerenciar pipelines de implantação para os workspaces no Power BI service, o que permite criar e gerenciar os espaços de trabalho de desenvolvimento, teste e produção.

Em resumo, o Power BI service cria um espaço compartilhado permitindo com que as pessoas vejam os mesmos insights de forma segura, enquanto convida elas a explorar elementos de dados compartilhados que podem ser organizados para servir necessidades específicas de cada usuário final (por usuário final lê-se clientes).

### Power Platform

---
## Capítulo 2. Os Relatórios e as Visualizações de Dados
Power BI Desktop é uma ferramenta robusta de visualização de dados que permite com que você pegue dados e crie insights visuais deles de formas variadas.

Este capítulo traz uma análise detalhada da Interface do Usuário (UI).

Nosso foco vai estar no *Report view* porque é lá que estaremos na maior parte do tempo.

As duas coisas mais importantes que você precisa saber sobre a UI são as funções do *Home tab* da barra de ferramentas (*ribbon*) e o *Visualizations pane*.

![its-not-a-feature-its-a-bug](https://github.com/user-attachments/assets/ed4b9397-d8bd-49b0-98e1-6d352d086758)
Power BI por padrão abre no Report view quando você inicializa.

Me parece que faz muito mais sentido não só acompanhar com o livro este capítulo por conta das descrições detalhadas e imagens como também usar o Power BI para conseguir se acostumar aos poucos com a interface, assim sendo, não irei transcrever tudo para cá;

e o mesmo vale para todo o restante do livro.
