# NOME DO PRODUTO

## Equipe
* Adalberto Dias Franco Filho
* Bruno Dias Del Claro
* Pedro Delavechia Risso

## 1. Visão 
_Forneça uma declaração que resuma o problema que sendo resolvido pelo sistema. O seguinte formato pode ser usado._

O problema de <descrição do problema> afeta os <interessados afetados pelo problema> cujo impacto é <qual o impacto do problema?>. Neste contexto, uma solução de sucesso resultaria em <benefícios chaves trazidos por essa solução>.

## 2. Envolvidos
_Forneça uma descrição dos papéis ou persona envolvidos ou interessados no projeto._

| Nome                      | Descrição     |
| -------------             |:-------------:|
| Nome do papel ou persona  | Descrição do papel ou persona |

## 3. Product Backlog
_O product backlog é basicamente uma lista priorizada de requisitos, estórias, features ou restrições. Coisas que o cliente ou usuário deseja descritas utilizando a terminologia do ambiente de negócios cliente ou usuário. Ele deverá conter no mínimo dez (20) estórias  de valor priorizadas pela sua importância._ 

| No. | Nome do requisito      | Importância | Estória   | Critérios de Aceitação | Link para o Protótipo de Baixa Fidelidade  |
| ----|:---------------------: |:----------: | :-------: | :--------------------: | :----------------------------------------: |
|   1 | Visualização           |     10      | Como dono da loja ou usuário autorizado eu devo ser capaz de visualizar todos gráficos e tabelas de uma maneira simples e direta ao acessar o site. | 1. Ao acessar o site abrir diretamente na tela de visualização dos gráficos.                      |                                            |
|  2  | Exportação de gráficos          |     9        | Como dono da loja ou usuário autorizado eu devo ser capaz de exportar esse gráficos e tabelas de uma maneira simples a partir de um menu acessível na tela inicial | 1. Ter um menu na tela inicial que a partir dele possa acessar uma opção de exportação e realizar a mesma no formato desejado pelo usuário | |
|  3  | Alterar visualização  | 5 | Como dono da loja eu devo ser capaz de alterar as disposições dos gráficos e tabelas de uma maneira simples, como em um drag'n drop. | 1. Ter uma opção que permita o usuário entrar em um modo de edição de visualização para que ele altere em forma de drag'n drop os elementos já criados. | |
| 4   | Criar items | 4 | Como dono da loja eu devo ser capaz de criar novos items de maneira intuitiva a partir de um contexto de edição | 1. No menu de edição criado na estória `3` existir uma opção para criar um novo item para a tela de visualização. | |
| 5   | Importação             |   6    | Como dono da loja ou usuário autorizado eu devo ser capaz de acessar através de um menu  acessível na tela inicial e realizar uma importação dos dados para gerar os items da visualização | 1. Através do menu citado na estória `2`  o usuário deve ser capaz de acessar uma opção de importação para que ele possa fazer o upload dos dados que serão usados para gerar a tela de visualização. ||
| 6   | Listar transações             |   3    | Como dono da loja ou usuário autorizado eu devo ser capaz de acessar uma lista de todas as transações em um período determinado | 1. Através do menu principal o usuário deve ser capaz de acessar um menu voltado à vendas e que contenha um botão para uma lista de todas as transações (10 por página, em ordem de recência crescente ou decrescente ou de um período determinado por ele) e os detalhes delas (quais itens foram vendidos, seus preços e o total, por exemplo). ||
| 7   | Alerta de estoque             |   2    | Como dono da loja ou usuário autorizado eu devo ser capaz de configurar uma notificação quando um determinado item tenha pouco estoque, e "pouco estoque" deve ser uma quantidade definida por mim. | 1. Através do menu de adição (citado no item `4`) e edição de item (que terá o mesmo layout do menu citado no item `4`) o usuário deve ser capaz de configurar um alerta que é acionado quando o estoque desse item atingir um número configurado pelo usuário.  ||
| 8   | Número de vendas por item             |   1    | Como dono da loja ou usuário autorizado eu devo ser capaz de ver quantas unidades de cada item foram vendidas. | 1. Através do menu de catálogo de itens, a quantidade em estoque e o número de vendas devem ser mostrados próximos um do outro em cada um dos itens listados. ||
| 9   | Criar transações             |   8    | Como dono da loja ou usuário autorizado eu devo ser capaz de criar transações e salva-las em uma lista. | 1. Através do menu principal deve ser possível acessar o menu de vendas, onde existe o acesso ao catálogo inteiro de itens da loja. Os itens podem ser adicionados à transação assim como outras informações ou características, como nome do cliente (se aplicável) ou descontos. ||
| 10   | Criar clientes             |   6    | Como dono da loja ou usuário autorizado eu devo ser capaz de criar "clientes" para atribuir às vendas e para que eu possa controlar vendas fiado com maior segurança. | 1. Através do menu de transação citado no item `9` deve haver a opção de se atribuir um cliente à ela. Um "cliente" deve ter algumas características, como nome, descrição e descontos inerentes em porcentagem e/ou em categorias. Um cliente também deve armazenar informações como compras fiado, seus valores e quais itens foram comprados. Esses clientes devem ser listados em um outro contexto de interface e devem ser editáveis a partir dessa lista. ||
| 11   | Listar clientes             |   4    | Como dono da loja ou usuário autorizado eu devo ser capaz de acessar uma lista com todos os clientes registrados no sistema da minha loja. | 1. Através do menu de vendas citado no item `6` deve haver também um botão que leva a uma lista que contenha todos os clientes (10 por página, por exemplo) com informações resumidas, como nome. Ao clicar, as informações completas do cliente se abrem em um menu flutuante. ||
| 12   | Customizar tema de cores             |   1    | Como dono da loja ou usuário autorizado eu devo ser capaz de personalizar a aparência da interface. | 1. Através de um menu nas configurações deve haver um contexto de opções para customizar as cores da interface. ||
| 13   | Multiplataforma             |   3    | Como dono da loja ou usuário autorizado eu devo ser capaz acessar informações importantes pelo meu celular. | 1. Através de um aplicativo de celular conectado a um servidor contendo as informações da loja, o lojista deve conseguir acesso às informações no sistema. ||
| 14   | Armazenar informações antigas |   9  | Como dono ou usuário autorizado devo ser capaz de armazenar informações antigas de modo pratico. |  1.No final do período selecionado pelo usuário, existira um caminho na qual os dados serão salvos e forma pratica, rápida e segura. ||
| 15   | Comparar meses                 |  7  | Como dono ou usuário autorizado eu devo ser capaz de comparar as vendas, lucros e perdas de meses anteriores. | 1.Na tela principal citada na estória 1, existir uma opção de incluir um mês desejado a fins comparativos. || 
| 16   | Simulações de lucro           |  4   | Como dono ou usuário autorizado devo ser capaz de fazer simulações da lucratividade a partir de valores especulados. | 1.Ter uma opção que permita o usuário inserir valores dos produtos com preço de custo, valores dos impostos, estimativa de preço e frete. Calculando assim, o lucro esperado. || 
| 17   | Apresentação para novos usuários |  2  | Como futuro usuário, gostaria de ter uma boa apresentação do software, para que assim, busque utilizar o produto | 1.Ter uma aba de novos usuários, para apresentar o software para novos usuários ||
| 18   | Assistência |   5   | Como dono ou usuário autorizado, devo ter acesso a uma aba de ajuda com perguntas frequentes e atendimento online. | 1. Um banco de dados para armazenar perguntas e respostas frequentes. 2. Opção para enviar e-mails para a assistência técnica e/ou chat online. || 
| 19  | Alterar opções de linguagem |  1  | Como um usuário internacional gostaria de ter uma acessibilidade no programa | 1. Opção de linguagens, no canto superior direito  ||
| 20  | Enviar Feedback |  2  | Como desenvolvedor, gostaria de receber feedback dos usuários |  1.Opção de estrelas com comentários. ||

