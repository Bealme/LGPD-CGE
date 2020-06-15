---
title: "Resumo Reunião"
output:
  html_document:
  toc: yes
toc_depth: 2
---

# Execução de testes-piloto para refinamento e escolha do modelo de mapeamento de dados pessoais 


## Discussão:

### Escopo dos dados que integrarão o escopo do mapeamento:

* Pessoais > pessoais sensíveis

* Tempo disponível para mapeamento X prazo da entrada em vigência da lei (5 meses)


### Razões para escolha do setor-piloto:

* RH percebido como o custodiador do maior volume de dados pessoais tratados na organização (NUCC? COGE?);

* Percepção de risco potencial no tratamento de dados custodiados no setor de RH;

* RH não está atrelado a uma das 3 subcontroladorias finalísticas (pedido do Controlador)

 
### Elaboração e validação do [instrumento](https://docs.google.com/spreadsheets/d/1Ko5LX9-tcBHLLczmn3YW_7pJFeL6NGxr/edit?dls=true#gid=160748431)

* Necessidade, forma de preenchimento e ordem das questões

* Quem preenche, quem valida, como, em qual prazo

* _'Base legal'_ = _'hipótese para tratamento de dados'_ ? (vide planilha SEPLAG)

* Listas pré-definidas para _'finalidade'_ como para _'hipótese para tratamento de dados'_?

##### Grau de itemização/especificidade de cada dado

* Reprisar um dado para cada processo em cada processo/sistema que ele aparece, mesmo que a finalidade, a forma de armazenamento e/ou o tratamento sejam similares? 
> P. ex., 'nome' do mesmo titular, em consultas diferentes do Portal, ou em demandas diferentes do e-SIC, ou em processos diferentes do RH (posse, cadastro)

* Reprisar os mesmos dados para cada titular distinto em cada processo/sistema que ele aparece, mesmo que a finalidade, a forma de armazenamento e/ou o tratamento sejam similares? 
> P. ex., cpf do prestador de serviço ou cpf do beneficiário de política pública na consulta de despesa do Portal da Transparência ([o único caso de cpf de beneficiário a ser anonimizado no Portal será de ganhador de prêmio lotérico](https://github.com/transparencia-mg/especificacoes-portal-transparencia/pull/1/commits/8d736fe0cdfb82fd1a810c3e902405081e9dd073) - benefícios previdenciários [ainda serão objeto de consulta jurídica](https://github.com/transparencia-mg/notas-tecnicas/blob/master/notas/consulta-juridica-dados-pessoais.md)).

* Quando o mesmo dado é armazenado em locais diferentes, nos arquivos físicos ou eletrônicos, repisá-lo em linhas distintas para evidenciar o tratamento que é dado para cada forma de arquivo? 
> P. ex., nome e remuneração de servidores que são salvos em pastas diferentes na rede da SUTI/SCT/DTA para diferentes finalidades (planilha de remuneração em uma pasta, especificações para PRODEMGE em outra, registro de erros em uma terceira); processos no RH que compõem sistema, planilha, pasta funcional física

* _'Ações para conformidade'_ podem determinar o grau de especificidade em que dado é registrado na planilha de mapeamento?

##### Etapas do processo de trabalho em que o mesmo dado é necessário

* Como considerar cada evento em que o dado pessoal sensível é acessado ou usado? Existe um momento definidor que determina o mapeamento de cada dado? Criação, edição, confirmação, envio/compartilhamento? P. ex., dados pessoais nos processos de RH: cada consulta para esclarecer uma situação específica de determinado servidor é um evento relevante para o mapeamento? 

##### Ponderação de risco e ações para conformiadade

* Qual medida utilizar para ponderar, classificar e comparar o risco de cada dado?

* Como desdobrar cada ação proposta. Por setor, por processo, por dado? (Vide experiências recentes do IACM, Planejamento Estratégico, GT de Riscos)

#### Referências
<a href="#top">(inicio)</a>

* [Resolução CGE 15, de 09/10/2015](http://jornal.iof.mg.gov.br/xmlui/handle/123456789/153152), que Dispõe sobre a classificação de informação de natureza sigilosa no âmbito da Controladoria-Geral do Estado:

> Art. 12. Fica instituída a Comissão de Gestão de Informação composta por representantes das seguintes unidades da Controladoria-Geral do Estado:

I – Gabinete;
II – Assessoria Jurídica;
III – Assessoria de Comunicação Social;
IV – Subcontroladoria de Auditoria e Controle de Gestão;
V – Subcontroladoria de Correição Administrativa;
VI – Superintendência de Planejamento, Gestão e Finanças.

§ 1º A Comissão de Gestão de Informação será presidida pelo Subcontrolador da Informação Institucional e da Transparência.

§ 2º __À Comissão de Gestão de Informação cabe monitorar a aplicação desta Resolução bem como propor medidas e requisitos de proteção física e lógica da informação gerida pela Controladoria-Geral do Estado__, competindo-lhe ainda:

I – opinar sobre a identificação e classificação ou reavaliação de informação em qualquer grau de sigilo;
II – assessorar o Controlador-Geral do Estado e o Controlador-Geral Adjunto;
III – propor o destino final da informação desclassificada, indicando-a para guarda permanente, observado, no que couber, o disposto na Lei Federal n° 8.159, de 8 de janeiro de 1991, e na Lei Estadual nº 19.420, de 11 de janeiro de 2011; e
IV – subsidiar a elaboração das listas anuais de informações classificadas em cada grau de sigilo e desclassificadas, a serem disponibilizadas no sítio eletrônico da Controladoria-Geral do Estado

> Art. 13. A Controladoria-Geral do Estado manterá, __independentemente de classificação, acesso restrito à informação produzida ou custodiada__, relativa a:

I – informação pessoal, de caráter privado;
II – informação caracterizada em norma específica como de natureza sigilosa, tal como sigilo de correspondência, fiscal, patrimonial, comercial, industrial, bancário ou médico;
III – processo judicial sob segredo de justiça;
IV – identificação do denunciante;
V – trabalho de auditoria não concluído;
VI– sindicância administrativa ou processo administrativo disciplinar não concluído.

§ 1º Considera-se concluído o trabalho de auditoria após a finalização do respectivo documento técnico contendo a manifestação do órgão ou entidade auditados.
§ 2º O acesso à informação produzida pelas Auditorias Setorial e Seccional e pelos Núcleos de Auditoria observará os procedimentos previstos nesta Resolução.
§ 3º Consideram-se concluídos a sindicância administrativa e o processo administrativo disciplinar após a publicação do ato ou decisão de arquivamento, absolvição, imposição de penalidade ou extinção da punibilidade.

Art. 14. A restrição prevista nos incisos I, V e VI, do artigo 13 não se aplica ao interessado que tenha necessidade de conhecer a informação para defesa de seu direito.

Art. 15. O acesso à informação produzida pela Assessoria Jurídica, Assessoria de Planejamento, Assessoria de Comunicação Social, Superintendência de Planejamento, Gestão e Finanças observará as __diretrizes previstas em resolução do respectivo órgão central__.

Art. 16. A Controladoria-Geral do Estado dispensará o __mesmo tratamento ao grau de sigilo e prazo atribuído pelo órgão ou entidade de origem à informação sob sua custódia__.

Art. 17. A Subcontroladoria da Informação Institucional e da Transparência adotará __medidas de capacitação dos servidores designados para o cumprimento dos objetivos desta Resolução__.

* [Informações Classificadas e Desclassificadas no site da CGE](http://cge.mg.gov.br/transparencia/informacoes-classificadas-e-desclassificadas):

> As informações sigilosas são classificadas pelos órgãos e entidades quanto ao grau do sigilo, conforme orientações do Decreto 45.969/12. Devem ser disponibilizadas todas as informações classificadas em cada grau de sigilo e aquelas desclassificadas nos últimos 12 meses.

A Controladoria-Geral do Estado de Minas Gerais não teve informações classificadas ou desclassificadas nos graus de sigilo reservada, secreta e ultrassecreta, definidos no art. 23 da Lei Federal nº 12.527/11 (Lei de Acesso à Informação).