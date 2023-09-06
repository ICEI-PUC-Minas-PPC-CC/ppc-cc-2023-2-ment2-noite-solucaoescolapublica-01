# Especificações do Projeto

## Personas

| Nº | Foto | Nome | Idade | Conhecimentos Prévios | Relação com a Tecnologia | Motivações | Relações Hierárquica |
| --- | --- | --- | --- | --- | --- | --- | --- | 
| 1 | <img src="https://github.com/ICEI-PUC-Minas-PPC-CC/ppc-cc-2023-2-ment2-noite-solucaoescolapublica-01/blob/main/src/assets/persona1.png?raw=true" width="50" height="50"/> | Gabriella Souza | 12 anos | Utiliza smartphones para jogar e assistir a vídeos, mas tem pouca experiência em pesquisas online. | Usuária ocasional de dispositivos eletrônicos, mas não se sente confortável com tarefas online complexas.| Encontrar livros de aventura para o trabalho escolar | Aluna da IEMG - Poços de Caldas. |
| 2 | <img src="https://github.com/ICEI-PUC-Minas-PPC-CC/ppc-cc-2023-2-ment2-noite-solucaoescolapublica-01/blob/main/src/assets/persona2.png?raw=true" width="50" height="50"/> | Carlos Rodrigues | 38 anos | Proficiente em tecnologia, utiliza sistemas de gestão escolar e recursos digitais em suas aulas. | Utiliza tecnologia regularmente para preparar e ministrar aulas. | Encontrar livros de referência para apoiar sua aula sobre história local. |Professor na IEMG - Poços de Caldas |
| 3 | <img src="https://github.com/ICEI-PUC-Minas-PPC-CC/ppc-cc-2023-2-ment2-noite-solucaoescolapublica-01/blob/main/src/assets/persona3.png?raw=true" width="50" height="50"/> | Ana Santos | 33 anos | Possui conhecimentos sólidos em catalogação e organização de bibliotecas. | Gerencia livros de bibliotecas em um sistema local, mas deseja uma solução mais eficiente. | Manter o catálogo de livros atualizado e acessível para os usuários. | Bibliotecária na Biblioteca Municipal de Poços de Caldas. | 
| 4 | <img src="https://github.com/ICEI-PUC-Minas-PPC-CC/ppc-cc-2023-2-ment2-noite-solucaoescolapublica-01/blob/main/src/assets/persona4.png?raw=true" width="50" height="50"/> | Francisca de Oliveira | 50 anos | Possui conhecimento em planejamento educacional e gestão de recursos. | Utiliza tecnologia para análise de dados educacionais e tomada de decisões. | Avaliar a demanda de livros nas escolas públicas e alocar recursos de forma eficaz. | Diretora da Secretaria Municipal de Educação. | 

## Histórias de Usuário

 `Pesquisa de Livro para Trabalho Escolar` 

 | COMO | QUERO / PRECISO | PARA | 
 | --- | --- | --- |
 | Persona 1 | pesquisar livros por gênero | encontrar facilmente livros de aventura para meu trabalho escolar. |
 | Persona 1 | ver informações detalhadas | identificar autor, sinopse e disponibilidade na biblioteca. | 
 | Persona 1 | pesquisar livro | encontrar biblioteca mais próxima que possui o livro que escolhi. |
 | Persona 3 | pesquisar livro | indicar outra biblioteca, na falta do exemplar desejado. |
 | Persona 2 | pesquisar livros por autor | usar como referência em minhas aulas. |
 | Persona 2 | pesquisar livros por tema | criar uma lista de indicações para meus alunos. | 


 `Manutenção do Catálogo de Livros`

 | COMO | QUERO / PRECISO | PARA | 
 | --- | --- | --- |
 | Persona 3 | gerar novos dados | adicionar novos livros ao catálogo da biblioteca, incluindo informações como título, autor, gênero e ISBN. |
 | Persona 3 | editar dados de um livro | corrigir informações tais como título, autor, gênero e ISBN.| 
 | Persona 3 | editar status um livro | alterar status de disponibilidade de um livro ou revista. | 


 `Alocação de Recursos Educacionais`

 | COMO | QUERO / PRECISO | PARA | 
 | --- | --- | --- |
 | Persona 4 | gerar relatório por biblioteca | identificar quais livros possuem maior demanda para aquisição de novos exemplares. |
 | Persona 4 | gerar relatório geral | ajudar na tomada de decisões para direcionar recursos para bibliotecas que possuem maior demanda. |  

## Requisitos 

`Funcionais`

| ID | DESCRIÇÃO DO REQUISITO | PRIORIDADE |
| --- | --- | --- |
| RF-001 | Pesquisa de livros por gênero.	| Alta |
| RF-002 | Exibição de informações detalhadas dos livros.	| Alta |
| RF-003 | Localização da biblioteca mais próxima com o livro desejado.	| Alta |
| RF-004 | Busca de livros de referência por temas específicos.	| Média |
| RF-005 | Criação de listas de livros recomendados para alunos. | Média |
| RF-006 | Adição de novos livros ao catálogo da biblioteca.	| Alta |
| RF-007 | Atualização do status de disponibilidade dos livros.	| Alta |
| RF-008 | Visualização de relatórios de demanda de livros nas escolas públicas.	| Alta |
| RF-009 | Gerenciar livros e seus exemplares.	| Alta |
| RF-010 | Renovação de livros. | Média |
| RF-011 | Categorização de livros quando cadastrar. | Média |
| RF-012 | Criação de um acervo digital. | Alta |

`Não-Funcionais`

| ID | DESCRIÇÃO DO REQUISITO | PRIORIDADE |
| --- | --- | --- |
|RNF-001 |	Conformidade com regulamentos de proteção de dados (LGPD). |	Alta |
|RNF-002 |	Compatibilidade com diferentes dispositivos (computadores, smartphones). |	Alta |
|RNF-003 |	Integração com sistemas de autenticação de usuário, como login único (SSO). |	Alta |
|RNF-004 |	Suporte a múltiplos idiomas. |	Baixa |
|RNF-005 |	Documentação detalhada para administradores do sistema.	| Média |
|RNF-006 |	Tempo de resposta aceitável para as consultas de catálogo. |	Alta |
|RNF-007 |	Manutenibilidade e escalabilidade do sistema.	| Média |
|RNF-008 |	Acessibilidade para usuários com deficiências. |	Alta |
|RNF-009 |	Backup e recuperação de dados confiáveis. |	Alta |
|RNF-010 | Emissão de alertas para devolução dos livros quando o prazo estiver próximo ao fim| Alta |

## Artefatos para levantamento de dados
---
*Nesta seção, caso seu grupo vá realizar algum tipo de levantamento de dados/entrevistas, descreva o(s) artefato(s) produzidos para tal. Também deverá ser descrita qual estratégia será utilizada para este levantamento. Por exemplo: como os questionários serão aplicados? (in loco, via disponibilização pela web etc), qual material/estratégia de divulgação será utilizado?*

*Não se preocupe em descrever os resultados agora, eles deverão ser descritos apenas na seção "Detalhamento preliminar" (Etapa 03).*
