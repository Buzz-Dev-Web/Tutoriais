# O que é cache?

Para que serve e como ele ajuda meu site?

## Cache do navegador:

### Para que serve?

O cache nada mais é que informações que ficam salvas no seu navegador (do seu dispositivo) por um curto periodo de tempo, eles podem tornar a navegação mais rápida e eficiente uma vez que evita que o seu dispositivo efetue o download de todas as informações do site a qual você quer acessar naquele momento, já que é mais rápido ler arquivos no seu computador do que requisitá-los do servidor a qual está hospedado o site.

Vale lembrar que o cachê ocupa espaço de armazenamento e a depender da configuração do navegador de seu dispositivos ele pode manter esta memória por mais ou menos tempo.

### Como limpar o cache do navegador?

Primeiramente você precisa saber que efetuar este processo pode causar uma lentidão temporária para você acessar este site novamente, pois exigirá que seu navegador faça a requisição de todas as informações novamente. Usando o Firefox como exemplo, basta abrir as opções do navegador e, na aba de “Privacidade e Segurança”, encontrar o botão “Limpar dados” no campo “Cookies e dados de sites”. Uma caixa de diálogo será exibida e então, basta marcar apenas o cache para a exclusão. Embora o processo possa variar um pouco de navegador a navegador, a dinâmica é parecida: basta procurar nas opções de privacidade e segurança as ferramentas de limpeza para eliminar o cache.


## Cache do Magento:

O Magento possui diferentes caches que servem para otimizar a navegação e usabilidade por parte do usuário, similar ao cache do navegador o Magento também armazena as informações que são mais utilizadas ou facilita que sua leitura seja realizada para otimizar a velocidade de navegação. É interessante entender o que cada um executa para que você otimize a navegação de seu site.


![Caches do Magento](https://github.com/Buzz-Dev-Web/Central-do-Frete-Magento-2-/blob/main/images/1-cachemagento.png)


```

1 -> Configuration: O Magento coleta a configuração de todos os módulos, mescla e salva o resultado mesclado no cache. Esse cache também contém configurações específicas da loja armazenadas no sistema de arquivos e no banco de dados. Limpe ou libere este tipo de cache após modificar os arquivos de configuração.

2 -> Layouts de página compilados (ou seja, os componentes de layout de todos os componentes). Limpe ou libere este tipo de cache após modificar os arquivos de layout.

3 -> Blocks: Fragmentos de página HTML por bloco. Limpe ou libere este tipo de cache após modificar a camada de visualização.

4 -> Collections Data: Resultados de consultas de banco de dados. Se necessário, o Magento limpa esse cache automaticamente, mas os desenvolvedores de terceiros podem colocar todos os dados em qualquer segmento do cache. Limpe ou libere este tipo de cache se seu módulo personalizado usa lógica que resulta em entradas de cache que o Magento não pode limpar.

5 -> Reflection Data: Remove uma dependência entre o módulo Webapi e o módulo Cliente.

6 -> Database DDL: Esquema de banco de dados. Se necessário, o Magento limpa esse cache automaticamente, mas os desenvolvedores de terceiros podem colocar todos os dados em qualquer segmento do cache. Limpe ou libere esse tipo de cache depois de fazer alterações personalizadas no esquema do banco de dados. (Em outras palavras, atualizações que o Magento não faz sozinho.) Uma maneira de atualizar o esquema do banco de dados automaticamente é usando o magento setup:db-schema:upgradecomando.

7 -> Compiled Config: Configuração de compilação

8 -> EAV types and attributes: Metadados relacionados a atributos EAV (por exemplo, rótulos de loja, links para código PHP relacionado, renderização de atributo, configurações de pesquisa e assim por diante). Normalmente, você não precisa limpar ou liberar esse tipo de cache.

9 -> Customer Notification: Notificações temporárias que aparecem na interface do usuário.

10 -> Integrations Configurations: Integrações compiladas. Limpe ou libere esse cache após alterar ou adicionar integrações.

11 -> Integrations API Configuration: Configuração de APIs de integração compilada das Integrações da Loja.

12 -> Page Cache: Páginas HTML geradas. Se necessário, o Magento limpa esse cache automaticamente, mas os desenvolvedores de terceiros podem colocar todos os dados em qualquer segmento do cache. Limpe ou libere esse tipo de cache após modificar o nível de código que afeta a saída HTML. Recomenda-se manter esse cache ativado porque o armazenamento em cache de HTML melhora o desempenho significativamente.

13 -> Web Services Configuration: Armazenamento em cache da estrutura da API da Web.

14 -> Translation: Após mesclar as traduções de todos os módulos, o cache de fusão será limpo.

```

É importante manter o cache do Magento sempre habilitado para otimizar a navegação do usuário e reduzir esforço por parte do servidor.

## Como ele pode ajudar meu site?

Como explicado anteriormente o cache faz uma "memória" do site em seu navegador, somado este recurso com o cache do Magento torna a navegação de certa forma mais rápida, causando com isso uma melhor experiência para seu cliente. 

Existem outros recursos como REDIS, VARNISH, OpCache e serviços como CDN (CloudFlare, GoCache, Akamai, etc.) que também auxiliam na otimização de navegação e podem ser inseridos no escopo do seu site a depender de alguns fatores compatibilidade da hospedagem e versão instalada de seu Magento.

### Dúvida/Suporte:

Em caso de dúvidas entre em contato com o dept de suporte.