---
title: "Resumo Reunião"
output:
  html_document:
  toc: yes
toc_depth: 2
---

# Execução de testes-piloto para refinamento e escolha do modelo de mapeamento de dados pessoais 

## Dúvidas, decisões, limitações da planilha em excel - modelo PRODEMGE 

Há campos em que mais de uma opção é aplicável.
1) No caso das colunas: K (Forma de armazenamento), L (Local de armazenamento), Q (Local de armazenamento do backup), U (Tipos de tratamento), AA (Hipótese para tratamento de dados), AF (Controles existentes); como proceder quando há mais de uma opção de preenchimento? 

Preencher com o principal? Especialmente no caso dos Tipos de Tratamento, há várias possibilidades aplicáveis.

* _Alternativa (ver primeira pergunta do próximo título): replicar tantas linhas quantas forem as diversas formas de armazenamento (K), local de armazenamento (L), backup (Q), tipos de tratamento (U), hipóteses para controle (AA) e controles existentes (AF) = estas seriam informações úteis sobre os dados pessoais mapeados (p. ex: 47% dos dados mapeados no setor X têm 2 ou 3 formas de backup - o que aumenta o risco, enquanto que no setor Y há apenas uma forma) - em que pese o trabalho adicional_

2) Quanto às colunas M (Período de retenção do armazenamento) e R (Período de retenção do backup), vamos considerar as orientações do guia do governo federal, às páginas 40 "2.6 Término do tratamento" e 41 "3 O CICLO DE VIDA DO TRATAMENTO DOS DADOS PESSOAIS"?

3) Na coluna Y (Existe compartilhamento com terceiros), estamos considerando terceiros outros órgãos, ou seriam setores/áreas dentro do próprio órgão? 

* _Consideração: dependendo do grau de agregação do levantamento (superintendência, subsecretaria), o compartilhamento com outro setor implica em maior exposição do dado a riscos_ 

Isso traz ainda uma questão sobre a abrangência dos papéis do controlador e operador. O controlador poderá ser definido como o órgão? E o operador? Também poderá ser definido como o órgão?

4) Quais justificativas seriam aplicáveis para a hipótese de tratamento? De ordem prática (atribuir ação, responder, etc.)?

5) Gostaríamos de saber se a SEPLAG aplicou a planilha no Sistema Fale Conosco, que contém um campo aberto com variadas informações pessoais fornecidas espontaneamente. Se sim, vocês pensaram em mapear as informações contidas nesse campo?


## Dúvidas, decisões, limitações relatadas em março -  Grau de itemização/especificidade de cada dado

* Reprisar um dado para cada processo em cada processo/sistema que ele aparece, mesmo que a finalidade (coluna G), a forma de armazenamento (coluna K) e/ou o tratamento sejam similares? __a depender do número de locais de armazenamento (coluna L) e do número de locais de backup (coluna Q)__
> P. ex., 'nome' do mesmo titular, em consultas diferentes do Portal, ou em demandas diferentes do e-SIC, ou em processos diferentes do RH (posse, cadastro)

* Reprisar os mesmos dados para cada titular distinto em cada processo/sistema que ele aparece, mesmo que a finalidade, a forma de armazenamento e/ou o tratamento sejam similares? __a depender do número de locais de armazenamento (coluna L) e do número de locais de backup (coluna Q)__
> P. ex., cpf do prestador de serviço ou cpf do beneficiário de política pública na consulta de despesa do Portal da Transparência ([o único caso de cpf de beneficiário a ser anonimizado no Portal será de ganhador de prêmio lotérico](https://github.com/transparencia-mg/especificacoes-portal-transparencia/pull/1/commits/8d736fe0cdfb82fd1a810c3e902405081e9dd073) - benefícios previdenciários [ainda serão objeto de consulta jurídica](https://github.com/transparencia-mg/notas-tecnicas/blob/master/notas/consulta-juridica-dados-pessoais.md)).

* Quando o mesmo dado é armazenado em locais diferentes, nos arquivos físicos ou eletrônicos, repisá-lo em linhas distintas para evidenciar o tratamento que é dado para cada forma de arquivo? 
> P. ex., nome e remuneração de servidores que são salvos em pastas diferentes na rede da SUTI/SCT/DTA para diferentes finalidades (planilha de remuneração em uma pasta, especificações para PRODEMGE em outra, registro de erros em uma terceira); processos no RH que compõem sistema, planilha, pasta funcional física

* _'Ações para conformidade'_ podem determinar o grau de especificidade em que dado é registrado na planilha de mapeamento?

##### Etapas do processo de trabalho em que o mesmo dado é necessário

* Como considerar cada evento em que o dado pessoal sensível é acessado ou usado? Existe um momento definidor que determina o mapeamento de cada dado? Criação, edição, confirmação, envio/compartilhamento? P. ex., dados pessoais nos processos de RH: cada consulta para esclarecer uma situação específica de determinado servidor é um evento relevante para o mapeamento? 

### Ponderação de risco e ações para conformiadade

* Qual medida utilizar para ponderar, classificar e comparar o risco de cada dado?

* Como desdobrar cada ação proposta. Por setor, por processo, por dado? (Vide experiências recentes do IACM, Planejamento Estratégico, GT de Riscos)

* Referências para ponderação de risco:

* [Integrating Healthcare Enterprise/IHE De-identification handbook](https://www.ihe.net/wp-content/uploads/uploadedFiles/Documents/ITI/IHE_ITI_Handbook_De-Identification_Rev1.1_2014-06-06.pdf)

* [IHE Algorithm Mapping Spreadsheet](https://www.ihe.net/wp-content/uploads/2018/02/IHE_ITI_Handbook_De-Identification-Mapping_Rev1.1_2014-06-06.xlsx) 

## Reuniões anteriores - registros
<a href="#top">(inicio)</a>

* [Março](https://github.com/transparencia-mg/notas-reunioes/blob/master/notas/2020-03-13_pauta_LGPD_SUTI_ESCRITORIO.md)

* [Fevereiro](https://github.com/transparencia-mg/notas-reunioes/blob/master/notas/2020-02-10_resumo_LGPD_SUTI_ESCRITORIO.md)

