# Nexa-Trabalho-Design-Profissional
Trabalho da matéria Design Profissional
Projeto Integrador — Dark Kitchens
Com base no enunciado oficial da disciplina de Design Profissional e no prompt enviado, vamos estruturar o projeto de vocês como uma empresa fictícia de tecnologia, com uma solução de gestão para cozinhas que trabalham com delivery.

O trabalho seguirá as quatro fases exigidas pelo professor: pesquisa de campo, prototipagem UI/UX, desenvolvimento e validação do MVP, e documentação com publicação no GitHub. As entrevistas, os testes e as entregas que ainda não foram realizados ficarão identificados como pendentes, sem inventar resultados.
1. Resumo e definição do projeto









Tema 7 — Sistema Integrado de Gestão para Cozinhas Sob Demanda
Problema: pedidos, estoque e preparação podem ficar difíceis de organizar quando uma cozinha atende diferentes canais de delivery.

Solução proposta: um sistema web que reúne pedidos, acompanha o andamento da produção, controla insumos e ajuda a reduzir atrasos e erros operacionais.



Integrantes
Rafael Ribeiro

Organização do projeto, requisitos, documentação e integração das entregas.

Pedro Taddei

Pesquisa de campo, UI/UX, protótipos e avaliação da experiência.

Gustavo Broch

Implementação, banco de dados, testes e organização do GitHub.



Essas responsabilidades são uma proposta inicial. Os três integrantes devem participar da implementação e da apresentação final.
2. Nome da empresa e do sistema









Nexa FoodTech
Empresa fictícia de tecnologia
Nexa Kitchen
“Mais controle na cozinha, mais agilidade na entrega.”



Conceito da marca: tecnologia acessível para simplificar a rotina de cozinhas profissionais e estabelecimentos focados em delivery.

Missão: facilitar a gestão de pedidos, insumos e produção por meio de um sistema simples e organizado.

Visão: tornar-se uma referência em soluções digitais acessíveis para pequenos e médios negócios de alimentação.

Valores: praticidade, organização, confiabilidade, eficiência e melhoria contínua.
Identidade visual sugerida

Preto

#171717


Laranja

#F97316


Cinza claro

#F5F5F5


Tipografia sugerida: Inter ou Poppins. Logotipo: símbolo simples que combine uma chama ou prato com elementos digitais.

Os nomes e a identidade são sugestões para o trabalho acadêmico. A disponibilidade comercial e de registro das marcas ainda precisa ser verificada.
3. Contextualização e justificativa
As Dark Kitchens são cozinhas comerciais que trabalham principalmente com pedidos para entrega, sem depender de um salão tradicional para receber clientes. Nesse modelo, a organização da produção, o controle dos ingredientes e o cumprimento dos prazos de entrega são importantes para o funcionamento do negócio.

Quando os pedidos chegam por diferentes aplicativos ou canais, podem surgir dificuldades para acompanhar o andamento das preparações, evitar pedidos duplicados, controlar o estoque e identificar atrasos.

O sistema Nexa Kitchen pretende centralizar essas informações em uma única interface, permitindo que os funcionários visualizem os pedidos, atualizem seus status, acompanhem os insumos disponíveis e organizem a expedição.
Justificativa com base no enunciado
Segundo o documento oficial da disciplina, a pesquisa de referência foi realizada ao longo de dois anos e envolveu mais de 40 mil entrevistados. O segmento de cozinhas Dark Kitchens apresentou um índice de necessidade de 68% no levantamento apresentado pelo professor.

Esse dado contribui para justificar a escolha do tema. A proposta também está alinhada à orientação do enunciado de desenvolver soluções específicas para problemas concretos de rotina e logística.

O percentual de 68% pertence à pesquisa de referência do enunciado, não a uma pesquisa realizada pelo grupo. A necessidade de cada funcionalidade deverá ser investigada nas entrevistas de campo.

Objetivo geral: desenvolver um sistema web simples para centralizar pedidos e auxiliar no controle de estoque e no acompanhamento do tempo de preparação e expedição de cozinhas que trabalham com delivery.

Objetivos específicos:
- Organizar pedidos em diferentes etapas de atendimento.
- Cadastrar produtos e controlar os insumos disponíveis.
- Alertar sobre níveis baixos de estoque.
- Registrar os horários e acompanhar o tempo de preparo.
- Apresentar informações resumidas em um painel.
- Validar a facilidade de uso com pessoas do público-alvo.
4. Fase 1 — Planejamento da pesquisa de campo
O professor exige uma pesquisa primária com uma ou duas pessoas reais do público-alvo. Portanto, esta seção contém o planejamento da pesquisa, que precisa ser aplicado antes de registrar conclusões como resultados reais.
4.1. Objetivo
Identificar como cozinhas que trabalham com delivery recebem pedidos, organizam a produção, controlam os insumos e lidam com atrasos e dificuldades operacionais.
4.2. Quem entrevistar
- Proprietário ou gerente de uma Dark Kitchen.
- Funcionário responsável pelos pedidos ou pela produção.
- Responsável por estoque e expedição de um estabelecimento com operação de delivery.
4.3. Roteiro de entrevista
Modelo preenchível para registrar as respostas do entrevistado. As informações não são enviadas a ninguém; copie-as para a documentação do grupo.
1. Como os pedidos chegam ao estabelecimento atualmente?

2. Como vocês organizam os pedidos que precisam ser preparados?

3. Quais dificuldades aparecem nos horários de maior movimento?

4. Como é feito o controle dos ingredientes e demais insumos?

5. Como vocês identificam quando um produto está acabando?

6. Já ocorreram atrasos ou erros por falhas na organização dos pedidos? Como foram tratados?

7. Como vocês acompanham o tempo de preparo e de expedição?

8. Utilizam mais de uma plataforma de delivery? Como organizam as informações recebidas?

9. Quais tarefas de gestão consomem mais tempo durante o expediente?

10. Se pudesse melhorar uma parte da operação com um sistema, qual seria?

Copiar roteiro e respostas
4.4. Matriz de dores e oportunidades
Esta matriz é um modelo inicial de investigação, e não um conjunto de resultados confirmados.
Aspecto investigado	Possível dificuldade a verificar	Oportunidade para o sistema
Pedidos	Informações espalhadas em diferentes canais	Painel centralizado
Produção	Dificuldade para identificar prioridades	Status e horários dos pedidos
Estoque	Falta de visibilidade sobre os insumos	Controle de quantidades
Desperdício	Ingredientes vencidos ou mal utilizados	Histórico de movimentações
Expedição	Dificuldade em acompanhar atrasos	Registro do tempo de preparo
Gestão	Falta de visão geral da operação	Dashboard com indicadores

Após realizar as entrevistas, o grupo deverá substituir as hipóteses pelas dificuldades efetivamente relatadas e ajustar os requisitos do sistema.
5. Fase 2 — Requisitos do sistema
Os requisitos a seguir são uma proposta inicial. A prioridade definitiva deverá considerar os resultados da pesquisa e a capacidade de implementação do grupo.
5.1. Requisitos funcionais
Prioridades: alta = essencial para o MVP; média = útil, mas pode ser simplificada ou adiada.
Código	Requisito	Prioridade
RF01	Cadastrar e consultar produtos	Alta
RF02	Cadastrar pedidos e seus itens	Alta
RF03	Visualizar pedidos por status	Alta
RF04	Alterar o status dos pedidos	Alta
RF05	Cadastrar e atualizar insumos	Alta
RF06	Registrar entradas e saídas de estoque	Alta
RF07	Alertar sobre estoque baixo	Alta
RF08	Registrar horário de início e conclusão do preparo	Alta
RF09	Exibir resumo de pedidos e estoque no dashboard	Alta
RF10	Editar e consultar informações cadastradas	Alta
RF11	Gerar relatórios básicos	Média
RF12	Autenticar usuários e controlar permissões	Média para o protótipo; importante para uma versão de produção

A integração automática com aplicativos comerciais de delivery não será considerada implementada no MVP sem uma integração real, desenvolvida e testada. A primeira versão poderá utilizar cadastro manual de pedidos.
5.2. Requisitos não funcionais
- Usabilidade: apresentar telas simples, com informações legíveis e botões claros.
- Desempenho: permitir operações comuns sem demora excessiva.
- Segurança: validar entradas e proteger as operações de alteração dos dados.
- Privacidade: armazenar somente os dados necessários para o funcionamento.
- Confiabilidade: manter os dados consistentes, inclusive ao atualizar o estoque.
- Manutenção: organizar o código em arquivos e funções com responsabilidades claras.
- Compatibilidade: funcionar nos navegadores modernos usados em computadores.
- Persistência: conservar os dados no banco mesmo depois de fechar e reiniciar a aplicação.
5.3. Regras de negócio
1. Todo pedido deve possuir identificação, data e hora, itens e status.
2. Os pedidos devem seguir etapas definidas: recebido, em preparação, pronto para expedição, concluído ou cancelado.
3. Um pedido cancelado não deve continuar aparecendo como pendente de preparo.
4. O sistema deve impedir movimentações que deixem o estoque negativo, salvo se houver uma regra específica aprovada para isso.
5. A baixa dos insumos deve ocorrer de maneira consistente, sem descontar os mesmos ingredientes duas vezes para um único pedido.
6. Produtos ou insumos abaixo da quantidade mínima configurada devem gerar um alerta.
7. O tempo de preparo deve ser calculado a partir do início da produção até a conclusão dessa etapa, distinguindo-o do tempo de expedição.
8. Alterações de estoque devem ser registradas para permitir consulta posterior.
6. Fase 2 — Personas e jornada do usuário
As personas abaixo são hipotéticas e deverão ser revistas depois da pesquisa de campo.









Persona 1 — Gerente da cozinha

Nome fictício: Mariana, 32 anos

Objetivo: acompanhar pedidos, identificar atrasos e evitar falta de ingredientes.

Dificuldade a investigar: precisar consultar várias fontes para entender a situação da operação.

Necessidade: visualizar pedidos, estoque e indicadores em um único painel.












Persona 2 — Auxiliar de produção

Nome fictício: Lucas, 24 anos

Objetivo: preparar os pedidos na sequência correta e encaminhá-los no tempo previsto.

Dificuldade a investigar: receber informações incompletas ou não saber quais pedidos são prioritários.

Necessidade: consultar rapidamente os itens, os horários e o status de cada pedido.



Jornada principal do usuário
1

Receber

O funcionário cadastra o pedido recebido.


2

Conferir

O sistema exibe os itens e permite verificar os insumos necessários.


3

Preparar

O pedido muda para o status de preparação e o horário é registrado.


4

Finalizar

O funcionário marca o pedido como pronto para expedição.


5

Concluir

O pedido é marcado como concluído e os dados ficam disponíveis para consulta.



7. Protótipos de baixa e alta fidelidade
O enunciado solicita protótipos estruturais e uma interface visual interativa, preferencialmente feita no Figma ou ferramenta similar.
7.1. Wireframes de baixa fidelidade
Estes esboços textuais representam a estrutura inicial das telas.
Tela 1 — Login
Nexa Kitchen
E-mail
Senha
Entrar



Tela 2 — Dashboard
Nexa Kitchen | Painel principal
Pedidos ativos
--


Estoque baixo
--



Pedidos recentes
Pedido #001 — Em preparação
Pedido #002 — Recebido


Tela 3 — Pedidos
Recebidos
Preparação
Prontos

Pedido #001 · 2 itens · R$ --
Pedido #002 · 3 itens · R$ --
Valores e pedidos acima são ilustrativos.


Tela 4 — Estoque
Ingrediente

Quantidade


Queijo

-- kg

Tomate

Estoque baixo

Desenvolver esta tela


Outras telas previstas: detalhes do pedido, cadastro de produtos e relatórios.
7.2. Protótipo de alta fidelidade
Para transformar os esboços em uma interface visual no Figma:
1. Criar um projeto chamado Nexa Kitchen.
2. Definir uma moldura para desktop e outra para tablet.
3. Aplicar a paleta preta, laranja e cinza claro.
4. Criar componentes reutilizáveis para botões, campos, tabelas e cartões.
5. Diferenciar os status dos pedidos com cores e textos.
6. Conectar as telas com interações de navegação.
7. Testar o fluxo completo de recebimento até a conclusão de um pedido.
O protótipo visual ainda precisa ser construído e testado. Os esboços apresentados não substituem o link e as capturas do protótipo de alta fidelidade solicitados no relatório.
8. Fase 3 — Definição do MVP
O Produto Mínimo Viável deverá concentrar-se nas funções necessárias para demonstrar o fluxo principal sem tornar o desenvolvimento excessivamente complexo.
Funcionalidade	Escopo inicial
Cadastro de produtos	Criar, editar e consultar produtos
Pedidos	Cadastrar pedidos e seus itens
Status	Atualizar e visualizar o andamento
Estoque	Cadastrar insumos e suas quantidades
Alertas	Identificar insumos abaixo do mínimo
Tempo	Registrar início e conclusão da preparação
Dashboard	Mostrar pedidos ativos e alertas de estoque

Fluxo de demonstração: cadastrar os produtos e os insumos, criar um pedido, verificar a disponibilidade dos ingredientes, acompanhar a preparação, registrar a conclusão e consultar o resumo no painel.
Plano de validação
A validação deve ser realizada com usuários reais, preferencialmente pessoas entrevistadas na primeira fase.
Teste	Resultado esperado	Resultado obtido
Cadastrar um produto	Produto salvo e exibido na lista	Pendente
Criar um pedido	Pedido exibido no painel	Pendente
Alterar o status	Novo status apresentado corretamente	Pendente
Registrar movimentação de estoque	Quantidade atualizada corretamente	Pendente
Simular estoque baixo	Alerta exibido	Pendente
Reiniciar a aplicação	Dados anteriores preservados	Pendente
Informar dados inválidos	Erro tratado sem corromper os dados	Pendente

Os resultados devem ser preenchidos somente após executar cada teste.
9. Fase 4 — Arquitetura técnica recomendada
Para manter o projeto viável para estudantes do segundo período de Engenharia de Software, uma combinação inicial seria:
Front-end

HTML, CSS e JavaScript

Telas, formulários, tabelas e interações


Back-end

Python com Flask

Regras de negócio, validação e processamento dos pedidos


Banco de dados

SQLite

Persistência de produtos, pedidos, itens e estoque

Versionamento

Git e GitHub para histórico, colaboração e documentação


Modelo inicial do banco de dados
Tabela	Campos principais
usuarios	id, nome, email, senha_hash
produtos	id, nome, preco, ativo
insumos	id, nome, unidade, quantidade, estoque_minimo
pedidos	id, data_hora, status, inicio_preparo, fim_preparo
itens_pedido	id, pedido_id, produto_id, quantidade, preco_unitario
movimentacoes_estoque	id, insumo_id, tipo, quantidade, data_hora

As chaves estrangeiras de itens_pedido ligam cada item ao seu pedido e produto. As movimentações de estoque ficam vinculadas ao insumo correspondente. Para controlar a baixa automática de ingredientes por produto, será necessário definir também quais insumos e quantidades são utilizados em cada receita.

Esse modelo é uma proposta inicial; os tipos SQL, as restrições e as operações transacionais precisam ser definidos na implementação.
10. Organização do GitHub
A estrutura sugerida para o repositório é:
nexa-kitchen/
├── app.py
├── database.py
├── schema.sql
├── requirements.txt
├── README.md
├── .gitignore
├── templates/
│   ├── base.html
│   ├── dashboard.html
│   ├── pedidos.html
│   ├── produtos.html
│   └── estoque.html
├── static/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── app.js
└── tests/
    └── test_app.py


O README deverá explicar o objetivo do projeto, as funcionalidades implementadas, as tecnologias, a estrutura, as instruções de instalação, a execução local, os testes, os integrantes e as limitações conhecidas.

O endereço do repositório deverá ser inserido depois que ele for criado e publicado.
11. Relatório técnico final
O relatório final exigido para 17/11 deverá ser organizado nas seis seções definidas pelo professor:
1. Capa e identificação da empresa: nome, logotipo, tema, integrantes e responsabilidades.
2. Justificativa e conexão com os dados globais: contextualização do segmento, dados do enunciado e justificativa.
3. Relatório da pesquisa primária: metodologia, entrevistas reais, matriz de dificuldades e conclusões.
4. Documentação de Design UI/UX: personas, jornada, requisitos, wireframes e protótipo de alta fidelidade.
5. Especificação técnica do MVP: funcionalidades, arquitetura, banco de dados, regras de negócio e resultados dos testes.
6. GitHub e guia de execução: link do repositório, organização dos arquivos e instruções de instalação e execução.
A versão final deve conter sumário, títulos numerados, paginação e referências quando necessárias. As partes que dependem de entrevistas, protótipos, testes ou implementação deverão ser atualizadas com os resultados reais antes da entrega.
12. Roteiro para a apresentação final
O cronograma do enunciado prevê a apresentação final em 17/11/2026.
Rafael

Empresa, problema e requisitos

Apresentar a Nexa FoodTech, explicar a proposta de valor e justificar o tema com os dados do enunciado.



Pedro

Pesquisa e experiência do usuário

Apresentar os resultados reais das entrevistas, os wireframes e o protótipo visual.



Gustavo

Sistema e demonstração

Explicar a arquitetura, demonstrar o MVP funcionando e apresentar o banco de dados e o GitHub.



Perguntas que o professor pode fazer
- Por que vocês escolheram esse tema? Porque o enunciado apresenta uma necessidade de 68% para o segmento e propõe soluções para problemas concretos de gestão.
- Como o sistema evita falta de ingredientes? Mantendo quantidades atualizadas e exibindo alertas quando o estoque fica abaixo do mínimo configurado.
- O sistema se integra diretamente ao iFood e a outros aplicativos? Somente se essa integração tiver sido efetivamente implementada e testada. Caso contrário, a demonstração utilizará cadastro manual de pedidos.
- Como vocês sabem que a solução funciona? Por meio de testes documentados e validação com usuários. Os resultados só poderão ser apresentados depois de obtidos.
- Por que utilizar SQLite? Porque permite persistência local com configuração simples, adequada a uma primeira versão acadêmica.
13. Checklist de entregas
Acompanhamento do grupo
0/7



[ ] Pesquisa de campo

Realizar e documentar as entrevistas reais.


[ ] Protótipos

Construir e conectar as telas de baixa e alta fidelidade.


[ ] MVP

Implementar pedidos, produtos, estoque e dashboard.


[ ] Testes

Executar os cenários e registrar os resultados.


[ ] GitHub

Publicar o código e completar o README.


[ ] Relatório

Consolidar as seis seções e inserir evidências reais.


[ ] Apresentação

Ensaiar as falas e testar a execução local.


Copiar checklist
Próximas datas do cronograma
Data	Entrega prevista
27/10/2026	Protótipos de baixa e alta fidelidade
03/11/2026	Desenvolvimento, integração e repositório GitHub
10/11/2026	Finalização do MVP, testes e documentação
17/11/2026	Apresentação final, relatório em PDF e link do GitHub

Como hoje é 26/10/2026, a apresentação dos protótipos está prevista para amanhã. O grupo deve priorizar as telas principais, sem deixar de planejar as demais fases.

Importante: o conteúdo acima organiza a proposta acadêmica, mas não representa um sistema já implementado, um protótipo publicado ou uma pesquisa já realizada. O próximo passo de desenvolvimento é transformar a especificação em arquivos executáveis, com banco de dados, interface, testes e documentação, verificando cada entrega antes de apresentá-la como concluída.
