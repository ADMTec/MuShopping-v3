MuShopping-v3
=============

Código fonte original e completo do MuShopping v3 liberado somente para os clientes. Estes códigos são privados de uso pessoal dos clientes. Todos as classes e códigos referente a checagem de licença foram removidos.

Não nos responsabilizamos por qualquer vazamento destes arquivos, levando em consideração que o mesmo está liberado somente para acesso dos clientes. O uso destes arquivos são de total responsabilidade do cliente. Não há suporte, atualizações ou qualquer informação e/ou contato referente a estes arquivos e ao projeto.

PROJETO DEFINITIVAMENTE ENCERRADO!

Agradecemos a todos que nos ajudaram. Pedimos desculpas pelo encerramento de nossas atividades, mas infelizmente nossa hora chegou. Desejamos sucesso a todos e que algum dia possamos retornar nossas atividades.

Atenciosamente;

==================

Para adquirir a permissão de uso destes arquivos entre em contato com a www.xteamservers.com (Skype: xteam.servers)

==================

Shopping para MuOnline Automático Versão 3.2.4

Versão compativel com servidores antigos e novos.
Versões de 0.97d ate Season 6.3

Suporte de escolha no ato da compra de um item:
 - Level
 - Option (adicional)
 - Ancient
 - Skill
 - Luck
 - Opções Excelentes
 - Opções Harmony
 - Opções Level 380 (Refine)
 - Opções de Sockets


Área do cliente:
———————-
Sistema de login: 100% (Com captcha / ajax)

Mostrar Saldo de cash: 100%

Inicio: 100%

Produtos: 100% (Ajax)
 - Nas categorias:
   --- Promoções  
   --- Todos os Itens
   --- Kits
   - Defesa
   --- Helms
   --- Pants
   --- Gloves
   --- Boots
   --- Armors
   --- Shields
   --- Pendants
   --- Rings
   --- Wings
   - Ataque
   --- Axes
   --- Bows
   --- Crossbows
   --- Maces
   --- Scepters
   --- Spears
   --- Staffs
   --- Swords
   - Outros
   --- Amulets
   --- Castel Siege
   --- Events
   --- Events MIX
   --- Gifts/Boxs
   --- Guards/Pets  
   --- Jewels
   --- Jewels MIX
   --- Mix Items
   --- Mix Pets
   --- New/Test
   --- Potions
   --- Quests
   --- Orbs  
   --- Scrolls 

Cupom de desconto: 100% (Ajax, Com um codigo de cupom fornecido pela equipe do jogo, o player pode obter um valor em % de desconto em sua compra)

Histórico de compras: 100% (itens / kits [com opção de recuperar item deletado do servidor] / depositos)

Confirmar depósitos: 100% (Aceito: Banco Bradesco, Banco Postal, Banco Itaú, Banco do Brasil, Caixa Econômica Federal, Lotérica, Caixa Aqui)

Recuperar item / kit perdido: 100% (Recuperar item / kit deletado do servidor)

Consertar item quebrado: 100% (Consertar durabilidade de itens que não são consertados no jogo)

Sobre o shopping: 100%


Área da administração:
----------------------
Produtos [Gerenciar]: (Gerenciador de cadastro de itens / kits)

Cupons [Gerenciar]: (Gerenciar cupons de descontos)

Logs [Compra de itens]: (Logs de compras de itens)
 
Logs [Compra de kits]: (Logs de compras de kits) 

Pagamentos [Andamento]: (Gerenciador de depósitos)

Pagamentos [Concluidos]: (Gerenciador de depósitos)

Pagamentos [Rejeitados]: (Gerenciador de depósitos)

Relatórios Financeiros: (Relatórios financeiros de arrecadação do shopping)

Gerenciador de Logins: (Permite ver todos os players que estão visitando o shopping, ver a página que estão mexendo, permite deslogar o player do shopping e etc)

Buscar Itens (Serial): (Permite você busque itens em todo o servidor pelo serial listando onde tem cada copia dele)


Como funciona:
----------------------
Sistema de vendas sem trocar baus.
O player entra no site e compra o item e ele vai para o espaço vago no seu bau. 
Caso ele não tenha espaço em seu bau, o shopping avisa e pede para ele liberar espaço suficiente para adicionar o item.

Na hora da instalação:
 - O shopping usa um banco de dados pré-programado com todos os itens até season 4.0.
   Esse banco de dados usa como base o DB do MuMaker v1.12 alterado para funcionamento correto do shopping.
   Esse processo dispensa de você ter que ficar digitando codigos na hora de cadastrar o item no shopping causando um desgaste fisico e mental no administrador do servidor pois são centenas de itens e consequentemente milhares de codigos poupados.

Shopping ideal para servidores de grande porte que precisam de um ótimo shopping para gerenciar suas vendas automatizando todo o processo desde a escolha de itens a entrega de item no jogo.

///////////////////////////

28/08/2009
 - Corrigido nos templates: default / 23920
   - Fixado o javascript que faz atualização de preços ancients. [product_details.php]

05/09/2009
 - Corrigido erro na leitura de baus nas versões velhas. [modules/vault.class.php]
 - Corrigido erro no consertar item quebrado para os itens que não estavam cadastrados no banco de dados. [modules/recover_broken_item.class.php]
 - Corrigida classe repetida na área de gerenciar produtos no painel admin. [admin/modules/products.class.php]
 - Corrigido opções nome das excelentes dos pendants, categoria 6:
   - modules/catalog.class.php
   - modules/history.class.php
   - admin/modules/products.class.php
 - Adicionado opções excelentes das asas level 3, categoria 7:
   - modules/catalog.class.php
   - modules/history.class.php
   - admin/modules/products.class.php
 - Adicionada caracteristica que mostra na hora de selecionar o item se ele está disponível para compras ou não. [admin/modules/products.class.php]
 - Adicionado a opção de desaticar / ativar vendas de kits no painel admin. [admin/modules/products.class.php]

07/09/2009
 - Correção da durabilidade 1 no consertar item quebrado.  [modules/recover_broken_item.class.php]

06/11/2009
 - Corrigido opções nome das excelentes:
   - modules/catalog.class.php
   - modules/history.class.php
   - admin/modules/products.class.php

10/11/2009
 - Adicionado no settings.php a opção para alterar no nome da sessao.
  - index.php
  - settings.php
  - modules/captcha.php
  - admin/index.php

Adicione no settings.php as seguintes linhas:

/*
    @Nome da sessão;
*/
define("SESSION_NAME_SHOP", "iwuhf98f4fv");

1/12/2009
 - Alterado o esquema de sockets option
  - settings.php
  - modules/sockets.lib.php
  - modules/item.class.php
  - modules/history.class.php
  - admin/modules/logsitems.class.php
  - admin/modules/logskits.class.php
  - admin/modules/products.class.php

Adicione no settings.php as seguintes linhas:

/*
    @ Sistema de socket item.
    @ Selecione o seu muserver abaixo
    
    LEGENDA:
       
       0 = Sistema da Webzen original (TNS Games, Diel, Eduardo (welcomevoce, phpnuke))  
       1 = Sistema da SCF / SCFMT (MuMaker)
*/
define("SOCKET_USE_LIB", 0);

9/12/2009
 - Adicionada checagem de max. options excelentes [finishbuy.class.php]
 
23/12/2009
 - Fixado o erro da opção refine na compra de kits. [finishbuykits.class.php]

8/1/2010
 - Fixada as opções sockets. [catalog.class.php]
 - Fixada as opções sockets. [finishbuykits.class.php]
 - Fixada os logs das opções sockets. [finishbuykits.class.php]
 - Fixada as opções sockets para SCF / SCFMT (MuMaker) [sockets.lib.php]

11/02/2010
 - Fixado erro na alteração de durabilidade do consertar itens. [recover_broken_item.class.php]
 - Fixado erro de checagem de compra na recuperação de item. [recover_lost_item.class.php]

09/04/2010
 - Alterado o sistema de licenças.
   * Funcionamento com licenças multiplas.
   * A porta do endereço agora não tem influencia sobre a licença.
   * Sistema igual para todos os produtos MuSite, MuShopping e Etc...
   * Sistema de autenticação via protocolo http em dois servidores.
   * Nova linha no settings.php
	define("countryPreference", 0x01); // Para Brasil 0x01, Estados Unidos da América 0x02
   [ Todas as paginas .php foram alteradas para funcionamento do novo sistema. ]

 - Corrigido problema de invasão no sistema de arquivos (php inject). [index.php / admin/index.php]

15/05/2010
 - Adicionado um limite global para limitar o numero de vezes que itens vendidos podem ser recuperados. [recover_lost_item.class.php]
   Adicione no settings.php as seguintes linhas:

/*
    @ Sistema de recuperação de itens.
*/
define("RECOVERY_LIMIT_ITEM", 0); // Use essa opção para limitar que todos os itens vendidos possam ser recuperados ate X vezes pelo player. Deixe 0 para ilimitado.

05/07/2010
 - Corrigido a compra de socket option sem permissão. [finishbuy.class.php]
 - Corrigido a compra de ancient option sem permissão. [finishbuy.class.php]
 - Corrigido a compra de harmony option sem permissão. [finishbuy.class.php]
 - Corrigido a compra de refine option sem permissão. [finishbuy.class.php]
 - Corrigido tamanho final do item. [items.class.php]
 - Unificação do codigo de obfuscação. [*.php]

02/08/2010
 - Fixado erro na alteração de durabilidade do consertar itens (tamperdata). [recover_broken_item.class.php]
 - Alterado tempo de limite da autenticação para 2 horas. [index.php]
 - Alterado sistema de licenças, agora compativel sem o allow_url_fopen ligado pois usa a biblioteca CURL caso esteja indisponivel a allow_url_fopen. [index.php]
 - Sistema de licenças usando cache de 1 hora. (Necessária permissão de escrita na pasta /licenses/) [index.php]
   Adicionar no settings.php as linhas:
	
	define("autenticationCache", true); // Guarda a chave de segurança em cache para não fazer requisições a cada pagina acessada. 

 - Regulado checagem de loopback apenas para o servidor selecionado. [index.php]

10/09/2010
 - Colocada nova tabela [ExtWarehouseVirtual] para busca de serial para recuperar item. [recover_lost_item.class.php]
 - Fixado byte do item ancient level 2. [items.class.php]
 - Adicionado suporte aos dois tipos de set ancients. [catalog.class.php / history.class.php / product_details.php]
 - Adicionado suporte a busca de itens para todas as colunas que são varbinary na warehouse. [recover_lost_item.class.php / itemfind.class.php]
 - Adicionado botão para mostrar itens de um determinado Kit na pagina de Kits, evitando que ela fique muito grande. [catalog.class.php]
 - Paginação na opção de confirmar pagamento. [payments.class.php / payments[*].tpl.php]
 - Proteção para compras ao mesmo tempo. [finishbuy.class.php, finishbuykits.class.php]

30/09/2010
 - Colocada nova tabela [ExtWarehouseVirtual] para busca de serial no painel admin. [itemfind.class.php]
 - Fixado busca de serial no painel admin. [itemfind.class.php]
 - Inserida trava para não permitir comprar sockets repetidos. [finishbuy.class.php]
   Adicionar no settings.php as linhas:
	
	define("LOCK_REPEAT_SOCKET", true); //Não permitir que sejá vendido item socket com opções repetidas.

 - Inserida trava para não permitir comprar de options excelentes com ancient. [finishbuy.class.php]
   Adicionar no settings.php as linhas:
	
	define("LOCK_ANCIENT_AND_EXCELLENT", false); //Não permitir que sejá vendido item com opções excelentes e ancient juntos.

 - Alterada a versão para 3.1.4 [index.php]

11/11/2010
 - Inserida trava para não permitir comprar categoria de sockets repetidos. [finishbuy.class.php]
   Adicionar no settings.php as linhas:
	
	define("LOCK_REPEAT_CATEGORIE_SOCKET", false); //Não permitir que sejá vendido item socket com categorias repetidas.

 - Alterada a versão para 3.1.5 [index.php]

12/11/2010
 - Inserida trava para não permitir comprar opções sockets do mesmo tipo repetidos. [finishbuy.class.php]
   Adicionar no settings.php as linhas:
	
	define("LOCK_REPEAT_SOCKET_TYPE", false); //Não permitir que sejá vendido item socket com tipos de sockets repetidos.

 - Alterada a versão para 3.1.6 [index.php]


29/11/2010
 - Fixado problema de realizar compras sem ter o baú aberto pelo menos uma vez no jogo. [vault.class.php]
 - Cadastrada novas classes da versão Season 6. [general.class.php, catalog.class.php, products.class.php, odbc.class.php]

 - Inserida trava para não permitir comprar opções socket com harmony. [finishbuy.class.php]
   Adicionar no settings.php a linha:
	
	define("LOCK_SOCKET_AND_HARMONY", false); //Não permitir que sejá vendido item com opções sockets e harmony juntos.

 - Colocada trava para não deixar o player comprar item com o level acima do permitido [finishbuy.class.php]
  Adicionar no settings.php a linha:
	
	define("LOCK_MAX_LEVEL", 13); //Configure aqui o level máximo que um player pode selecionar na hora de comprar um determinado item.

 - Alterações necessárias no banco de dados! Acesse a página: update_3.1.6_to_3.1.7.php no navegador!

 - Alterada a versão para 3.1.7 [index.php]

22/12/2010
 - Colocada a opção do DBVersion ser configuravel [vault.class.php]
  Adicionar no settings.php as linhas:

/*
    Exemplo de como configurar a opção: SYSTEM_DBVERSION
    //1 = (Versões antigas sem personal store), 2 = (Versões antigas com personal store), 3 = (Versões novas com personal store e harmony)  
    
    Para versões 97d, use a opção numero 1;
    Para versões 1.0 use a opção numero 2; 
    Para versões 1.2n ou acima use a opção numero 3; 
*/
define("SYSTEM_DBVERSION", 1); //1 = (Versões antigas sem personal store), 2 = (Versões antigas com personal store), 3 = (Versões novas com personal store e harmony) 

 - Alterada a versão para 3.1.8 [index.php]

11/02/2011
 - Fixado a opção de comprar kit (cobrava pelo kit com o player online, e não deixava realizar a entrega) [finishbuykits.class.php]
 - Alterada a versão para 3.1.9 [index.php]

15/04/2011
 - Inserida trava para não permitir comprar tipos de sockets repetidos por slot. [finishbuy.class.php]
  Adicionar no settings.php a linha:
	
	define("LOCK_REPEAT_SLOT_SOCKET", true); //Não permitir que sejá vendido item socket com slots repetidos.
 - Alterada a versão para 3.1.10 [index.php]

22/06/2011
 - Fixado venda de options harmony para itens +15 [catalog.class.php]
 - Adicionada trava de options sockets para não vender options que não são compativeis com as categorias correspondentes [finishbuy.class.php]
 - Adicionada a opção de deletar logs de compras pelo painel de administração. [logskits.class.php / logsitems.class.php]
 - Alterada a versão para 3.1.11 [index.php]

06/07/2011
 - Fixado trava de options sockets para não vender options que não são compativeis com as categorias correspondentes [finishbuy.class.php]
 - Fixado erro de variavel na compra de kits. [finishbuykits.class.php]
 - Alterada a versão para 3.1.12 [index.php]

25/07/2011
 - Removido checagem de loopback devido erro de rotas com o no-ip. [index.php]
 - Alterada a versão para 3.1.13 [index.php]
 
03/08/2011
 - Fixado erro de segurança. [protect.class.php]
 - Alterada a versão para 3.1.14 [index.php]

21/11/2011
 - Fixado erro na compra de item com harmony. [finishbuy.class.php] 
 - Alterada a versão para 3.1.15 [index.php]

21/01/2012
 - Adicionada trava de options sockets para não vender options que não são compativeis com as categorias correspondentes [finishbuy.class.php]
 - Alterada a versão para 3.1.16 [index.php]

11/02/2012
 - Adicionado suporte para versão Season 6.3 [vault.class.php]
 - Alterada a versão para 3.2.0 [index.php]

21/04/2012
 - Colocada trava na seleção de ancient para evitar ancient não suportado. [finishbuy.class.php]
 - Adicionada trava de segurança de tempo no recuperar item perdido de 3 minutos após sair do jogo. [recover_lost_item.class.php]
 - Alterada a versão para 3.2.1 [index.php]

28/04/2012
 - Adicionada trava de segurança de tempo regulável no recuperar item perdido após sair do jogo. [recover_lost_item.class.php]
   Adicionar no settings.php a linha:
	
	define("RECOVERY_LIMIT_MIN_TIME", 15); //Tempo mínimo a ser aguardado com o player offline para recuperar um item no shopping; Tempo recomendado 15 minutos. (Evitar dupers em versão com personal store)

 - Alterada a versão para 3.2.2 [index.php]

01/07/2012
 - Adicionado compatibilidade com a versão Season 6 Epi 3 da ENC Games. [vault.class.php]
   Adicionar no settings.php a linha:
	
	define("ENCGAMES_S6", true); //Coloque true para versão Season 6 Epi 3 da ENC Games

 - Adicionado compatibilidade com a versão Season 6 da Titans Tech. [recovery_lost_item.class.php]

 - Alterada a versão para 3.2.3 [index.php]

04/04/2014
- Fixado calculo incorreto de espaço nas versões 97d. [vault.class.php]
- Alterada a versão para 3.2.4 [index.php]
