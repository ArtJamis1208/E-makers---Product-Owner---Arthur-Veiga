# E-makers---Product-Owner---Arthur-Veiga

*Eis aqui meu projeto, equivalente ao terceiro período do aluno Arthur de Carvalho Veiga (2026/1) e sua respectiva documentação referente à área de Product Owner 
(PO) em meu processo seletivo (PS) de trainee da Empresa Júnior (EJ) E-makers, instituição de extensão da Universidade Federal de Lavras (UFLA).*

Tal levantamento de requisitos tem como propósito a simulação do mapeamento, para fins didáticos, de todo o ciclo de desenvolvimento de um produto fictício, cujo 
qual se trata de uma plataforma online de correção de redação chamado CorrijaMe+, cujo enfoque abrange redações tanto do modelo padrão do ENEM como quanto de 
outros vestibulares, a exemplo de FUVEST (USP), Unicamp, Unesp, UnB, ESA e EsPCEx.

Nessa perspectiva, tal repositório tratar-se-á da criação de um Product BackLog completo que reflita as necessidades do cliente, nosso querido patrono José Vitor, 
e as tarefas técnicas dos membros pertencentes à equipe que auxiliem de forma organizada ao desenvolvimento da plataforma de correções. 

-------------------------------------------------------------------------------------------------------------------------------------------------------------------
----------

Dentre os membros, podemos citar: 

• Arthur de Carvalho Veiga: o Product Owner/Scrum Master da Empresa Júnior (EJ) E-makers, da Universidade Federal de Lavras (UFLA); 

• Jorginho: responsável pela área de Front-End da E-makers; 

• Dorotéia: encarregada pela parte relativa ao Back-End da E-makers;

• Mariazinha: incumbida ao setor de Design da Interface da E-makers.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------
----------

Sob essa ótica, cabe a Arthur criar tasks referentes à organização do labor a ser realizado pelos membros da equipe, assim como a definição de Histórias de 
Usuário (com critérios de Aceite), o levantamento de requisitos com base nos stakeholders do projeto, o planejamento de sprints e a priorização de BackLog.

Ademais, ao Jorginho, confere-se a criação da estrutura inicial da aplicação, a construção das páginas principais, o consumo da API do Back-End, o tratamento de 
erros no cliente, o controle de estado e a garantia da responsividade no sistema de correção de redação.

Não obstante, à Dorotéia, é concedido a função de desenvolver os CRUDs para diferentes entidades, a autenticação dos usuários, o tratamento de exceções, a 
integração com serviços externos e a estruturação inicial do projeto, assim como a tarefa de considerar testes automatizados e documentação da API usufruída no 
programa.

Atribui-se, também, à Mariazinha a incumbência perante a construção de wireframes, a definição da paleta de cores, a tipografia, a criação de protótipos
navegáveis,a adaptação para mobile e a documentação do design system, como também as revisões de layout e os testes de aderência visual mediante o que foi
implementado.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------
----------

Em decorrência disso, o software CorrijaMe+, com funcionalidades para cada um dos três perfis de usuários que usufruirão do sistema de correções: Aluno, Corretor 
e Administrador, foi estruturado em torno de 28 telas, cujas quais são:

• Módulo Geral (Fluxo Transversal - 2 Telas)

1 - Login / Autocadastro 

Portal de acesso unificado para os três tipos de usuários (Aluno, Corretor e Admin) e ponto de partida para o autocadastro público de 
novos alunos.

2 - Checkout (Mercado Pago)

Interface integrada à API do Mercado Pago para o processamento seguro de pagamentos e compra de créditos/pacotes de redação pelos alunos.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------
----------

• Módulo do Aluno (10 Telas)

3 - Dashboard / Hall

Painel de boas-vindas do aluno, exibindo o saldo de créditos disponíveis e atalhos rápidos para as principais ações da plataforma.

4 - Vitrine de Planos

Catálogo com os pacotes de correção disponíveis para compra, detalhando valores, quantidade de envios e descrições comerciais.

5 - Seleção de Temas e Envio

Espaço onde o aluno escolhe o tema cadastrado que deseja desenvolver e realiza o upload da foto de sua redação (restrito a arquivos de imagem).

6 - Histórico de Redações (Listagem)

Tabela de acompanhamento contendo todas as redações já enviadas pelo aluno e seus respectivos status atuais (ex: Pendente, Em Correção, Corrigida).

7 - Visualização da Correção

Tela interativa onde o aluno visualiza sua folha de redação com pontinhos vermelhos clicáveis (comentários do corretor) e a nota detalhada por competência.

8 - Meu Perfil

Página de gerenciamento de dados cadastrais pessoais do aluno, como nome, e-mail e telefone de contato.

9 - Histórico de Compras

Extrato financeiro pessoal do aluno listando todos os planos adquiridos, datas de transação e formas de pagamento utilizadas.

10 - Gráficos de Evolução

Painel estatístico visual que demonstra graficamente o desempenho do aluno e sua oscilação de notas ao longo do tempo em cada competência do ENEM.

11 - Ranking de Alunos

Painel de gamificação que exibe a classificação geral dos alunos com base em suas maiores pontuações acumuladas nas correções.

12 - Central de Ajuda (Aluno)

Área de FAQ e suporte interno com canais diretos para o aluno tirar dúvidas e abrir chamados sobre o uso da plataforma.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------
----------

• Módulo do Corretor (8 Telas)

13 - Dashboard da Fila de Correção

Tabela dinâmica de redações pendentes, ordenada por prioridade (ordem de chegada: mais antiga primeiro), onde o clique na linha redireciona para a correção.

14 - Área de Correção (Edição)

Interface interativa de trabalho do corretor para clicar sobre a imagem da redação, inserir marcações de erros com comentários e atribuir notas na barra lateral 
de competências.

15 - Histórico de Correções Feitas

Painel de consulta do corretor contendo o arquivo de todos os textos já avaliados por ele e os feedbacks enviados.

16 - Meu Extrato Financeiro

Dashboard financeiro do corretor para visualização de saldo acumulado por redações corrigidas, histórico de repasses recebidos e solicitações de saque.

17 - Meu Perfil / Pix

Página para atualização de dados cadastrais do corretor e gerenciamento de sua chave Pix para o recebimento automatizado de repasses (pagamentos).

18 - Painel de Desempenho

Gráficos e métricas de produtividade do próprio corretor, indicando tempo médio de correção, quantidade de textos avaliados no mês e nível de satisfação.

19 - Central de Treinamento

Repositório de mídias, diretrizes e materiais de capacitação para alinhar os critérios de correção dos profissionais com a banca oficial do ENEM.

20 - Central de Ajuda (Corretor)

Canal de suporte exclusivo para o corretor tirar dúvidas técnicas ou reportar problemas com os atendentes da plataforma CorrijaMe+.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------
----------

• Módulo do Administrador (8 Telas)

21 - Dashboard Estatístico Geral

Painel principal do dono do site com métricas agregadas do negócio (usuários ativos, redações pendentes x corrigidas, faturamento mensal).

22 - Logs de Alterações (Auditoria)

Painel de segurança que registra em tempo real o histórico de ações do Administrador (criação, edição e exclusão) para controle do sistema.

23 - Controle de Usuários

Painel para gerenciamento da base de usuários cadastrados (com botão de lápis para edição) e para o cadastro manual exclusivo de novos corretores.

24 - Cadastro de Planos

Formulário gerencial do Administrador para criar, editar ou desativar os pacotes de redação e definir seus respectivos preços e regras de créditos.

25 - Banco de Temas e Bancas

Painel de gerenciamento das propostas de redação (com upload de imagem de capa e textos de apoio) e edição dos critérios de pontuação da banca, a priori, do ENEM.

26 - Painel Financeiro e Repasses

Central macro de faturamento da plataforma, controle de repasses para os corretores parceiros e aprovação de fluxos de pagamento.

27 - Caixa de Entrada de Suporte

Painel para o Administrador visualizar, responder e gerenciar todos os chamados abertos pelas centrais de ajuda de alunos e corretores.

28 - Perfil do Admin / Logout

Área para atualização de dados do administrador, troca de foto de perfil e encerramento seguro da sessão.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------
----------

Conclui-se, portanto, que o CorrijaMe+ consolida-se como uma plataforma de ponta a ponta que soluciona o desalinhamento operacional e financeiro historicamente 
enfrentado por corretores independentes que atuam em canais informais como o WhatsApp. Por intermédio de uma arquitetura baseada em três pilares de usuários 
(Aluno, Corretor e Admin), o sistema substitui a desorganização de arquivos dispersos por uma experiência fluida de correção visual interativa sobre imagens, ao 
mesmo tempo em que garante transações seguras e automáticas via Mercado Pago. Trata-se de uma solução escalável, focada em usabilidade e inteligência de negócios, 
projetada para profissionalizar o mercado de redações preparatórias para o ENEM e demais vestibulares, além de, a posteriori, maximizar os resultados de alunos e 
educadores, a exemplo do nosso cliente/patrono/admin renomadíssimo no ramo educacional e acadêmico: José Vitor. <3
