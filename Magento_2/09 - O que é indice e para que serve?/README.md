# Índice do Magento

## O que é índice do Magento ?

Em resumo índice é onde armazena as informaçoes como preço, posição no catálogo, vinculo de categoria, quantidade disponível em estoque, entre outras informações que tem como foco a otimização da navegação e versatilidade do Magento.


![Indice do Magento](https://github.com/Buzz-Dev-Web/Tutoriais/blob/master/Magento_2/09%20-%20O%20que%20%C3%A9%20indice%20e%20para%20que%20serve%3F/images/1-indice.png)


## Para que serve?

para melhorar o desempenho de sua vitrine . Conforme os dados mudam, os dados transformados devem ser atualizados ou reindexados. Magento tem uma arquitetura muito sofisticada que armazena muitos dados do comerciante (incluindo dados de catálogo , preços, usuários e lojas) em muitas tabelas de banco de dados. Para otimizar o desempenho da vitrine, o Magento acumula dados em tabelas especiais usando indexadores.

Por exemplo, se você alterar o preço de um item de R$ 4,99 para R$ 3,99. O Magento deve reindexar a mudança de preço para exibi-la em sua vitrine.

Sem a indexação, o Magento teria que calcular o preço de cada produto na hora, levando em consideração as regras de preços do carrinho de compras , preços de pacotes, descontos, preços de camadas, etc. Carregar o preço de um produto levaria muito tempo, possivelmente resultando em abandono de carrinho.

## Como realizar indexação (reindex) ?

A reindexação pode ser realizada em dois modos:

**Atualizar ao salvar** - as tabelas de índice são atualizadas imediatamente após a alteração dos dados.

**Atualizar por agenda** - este nativamente não oferece suporte ao administrador do painel. Para fazê-lo você deve acessar o terminal SSH da sua loja.

## Preciso de conhecimento especifico para reindexar via terminal?

Sim, pois o acesso da loja via terminal exige conhecimento específico, uma vez que você possui acesso ao terminal, pode executar funções de desenvolvedor e todo cuidado é pouco na realização dos procedimentos, pois pode afetar a estabilidade e consequentemente o funcionamento da loja.

Existem módulos no mercado que quando instalados permitem que você consiga realizar a reindexação total e/ou parcial via painel administrativo do Magento e ainda manter por agenda para executar automaticamente via CRON.


![Reindexação via terminal](https://github.com/Buzz-Dev-Web/Tutoriais/blob/master/Magento_2/09%20-%20O%20que%20%C3%A9%20indice%20e%20para%20que%20serve%3F/images/2-reindex-terminal.png)


## Por agenda pode ser programável?

Sim, o CRON que é um utilitário Linux que agenda um comando ou script no servidor, permite que você coloque a tarefa de reindexação para ser executada automaticamente com um intervalo de tempo, fazendo com que não seja necessário intervenção manual do administrador da loja.

### Dúvida/Suporte:

Em caso de dúvidas entre em contato com o dept de suporte.