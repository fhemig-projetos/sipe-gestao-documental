No dia 14/01/2026, nós da equipe do **Projeto RH +Simples** da **Fundação Hospitalar do Estado de Minas Gerais** nos reunimos com o responsável pela **Diretoria Central de Sistemas Corporativos de Gestão de Pessoas - DCSCGP** da **Subsecretaria de Transformação Digital e Atendimento ao Cidadão da Secretaria de Estado de Planejamento e Gestão - SUBDIGITAL/SEPLAG**, cuja equipe realiza a gestão do **Sistema de Indexação de Documentos em Pastas Funcionais Eletrônicas - SIPE**.

## Funcionamento geral do sistema
- Após a digitalização do documento e armazenagem no SEI, as pastas funcionais de cada servidor são vinculadas ao seu órgão de atuação e a informações de identificação desse servidor (CPF, MASP, Nome).
- Em seguida, para cada pasta funcional do servidor, são listados todos os documentos relacionados à sua vida funcional, além de outras informações relevantes: 
Nº doc., Nº proc., Processo, Documento, Nome na Árvore,	Instituição, Data SEI, Data SIPE, Tag, Ações
- Cada linha dessa tabela representa um documento funcional e, ao ser clicada, aponta para um link no SEI, relativo a este documento: por isso se diz que o SIPE é um _sistema indexador_. 

## Registro das informações SIPE
Na sua implementação na SEPLAG, uma vez que o documento especificado já encontre-se digitalizado no SEI, o registro dessas informações no SIPE, a _indexação_ propriamente dita, é realizado manualmente por servidores do RH, vinculados à determinada unidade SEI. 

## Melhoria de processos de aposentadoria SEE
Por conta de limitações tecnológicas e apontamentos feitos pela **Controladoria Geral do Estado - CGE** ao SIPE, o Diretor nos apresentou nova solução que está sendo desenhada atualmente como melhoria do sistema. 

Essa foi uma solução proposta inicialmente junto à **Secretaria de Estado de Educação - SEE**, para melhoria de processos de RH (mais especificamente do processo de aposentadoria), que contaria com a digitalização dos documentos a partir da integração dos diferentes sistemas utilizados pelo RH, como o SEI e SISAP, e o desenvolvimento de nova solução mais robusta que o SIPE, junto à **PRODEMGE**.

A fim de atender a realidade atual da FHEMIG, concordamos em realizar nesse primeiro momento a implementação do SIPE na sua estrutura atual e contribuir para o desenho dessa solução que está sendo pensada pela equipe da **DCSCGP**.

## Encaminhamentos
1. Nesse sentido, nos foi solicitado o mapeamento de algumas informações para avaliar a possibilidade de uso do sistema por parte da FHEMIG, em termos de hospedagem, capacidade do sistema e volumetria de documentos.

> - Quantidade de servidores ativos.
- Quantidade de servidores inativos.
- Quantidade de documentos por pasta funcional.
- Quantidade de pastas funcionais.

2. Solicitamos também a liberação de acesso em ambiente de testes do SIPE, a ser providenciado pela **Superintendência Central de Administração de Pessoal - SCAP**.

3. Possível ponto de melhoria identificado para o fluxo atual: automatização via API SEI do cadastro das informações no SIPE.
> Confirmar após análise do processo de registro das informações no sistema. 
