# Tabela de medidas usando o módulo SizeChart MagePlaza

## Requisitos:

* Módulo SizeChart Mageplaza instalado,

* Acesso ao painel administrativo do Magento,

## Antes de configurar:

Você pode configurar o módulo de diferentes maneiras, porém uma opção mais administrável é utilizar via atributo especifico, selecionando o atributo em cada cadastro do produto, para isso é importante saber criar e configurar o atributo antes de partirmos para a criação das tabelas, vamos lá:

## Criando o atributo:

1 -> No painel Magento, acesse LOJAS > ATRIBUTO > PRODUTO;

![lojas produto e atributo](https://github.com/Buzz-Dev-Web/Tutoriais/blob/master/Magento_2/26%20-%20Tabela%20de%20Medidas%20M%C3%B3dulo%20MagePlaza/images/1-lojas-produto-atributo.png)


2 -> Na tela que se abrir, no canto superior direito clique em ADICIONAR NOVO ATRIBUTO;

![atributo criação](https://github.com/Buzz-Dev-Web/Tutoriais/blob/master/Magento_2/26%20-%20Tabela%20de%20Medidas%20M%C3%B3dulo%20MagePlaza/images/2-atributo.png)

3 -> Prencha com o nome que deseja no atributo e proceda com as seguintes configurações:

* TIPO DE ENTRADA: DROPDOWN,
* VALORES NECESSÁRIOS: este preencha conforme você achar conveniente, caso SIM será obrigatório preencher em todos os produtos,

* GERENCIAR OPÇÕES: Crie obrigatoriamente a opção Sem tabela e deixe como padrão, abaixo adicione mais opções clicando em Adicionar opção,

Clique em Propriedade de Atributo Avançado:

* Preencha o código do atributo,
* Escopo: deve ser global,
* Valor único: Não,
* Adicionar a coluna de opções: Não,
* Uso em opções de filtro: Não,

### Ao topo clique na aba PROPRIEDADES DA LOJA

* Uso em pesquisa: Não,
* Comparável na Loja: Não,
* Utilizar em navegação por camadas: Não,
* Usar por resultados de pesquisa [...]: Não,
* Usar para condições de regra [...]: Sim << IMPORTANTE >>
* Permitir Tags [...]: Não,
* Visível nas páginas do [...]: Não,
* Usado na listagem de [...]: Não,
* Usado para ordenação na [...]; Não

4 -> Clique no canto superior direito SALVAR ATRIBUTO, você será direcionado a tela anterior,

5 -> Novamente clique em LOJAS > ATRIBUTO > CONJUNTO DE ATRIBUTO  e insira o atributo anteriormente criado na listagem do seu conjunto principal, a organização fica a seu critério.

![Conjunto de atributos](https://github.com/Buzz-Dev-Web/Tutoriais/blob/master/Magento_2/26%20-%20Tabela%20de%20Medidas%20M%C3%B3dulo%20MagePlaza/images/3-conjunto-de-atributos.png)

6 -> Feito isso clique novamente em SALVAR, localizado no canto superior direito;

## Configurar a tabela de medidas:

7 -> Clique em CATALOGO > TABELA DE MEDIDAS > GERENCIAR REGRAS,

![Tabela de medidas](https://github.com/Buzz-Dev-Web/Tutoriais/blob/master/Magento_2/26%20-%20Tabela%20de%20Medidas%20M%C3%B3dulo%20MagePlaza/images/3-catalogo-tabela.png)

8 -> No canto superior direito clique em ADICIONAR REGRA

![criar regra](https://github.com/Buzz-Dev-Web/Tutoriais/blob/master/Magento_2/26%20-%20Tabela%20de%20Medidas%20M%C3%B3dulo%20MagePlaza/images/4-adicionar-regra.png)

9 -> Preencha os itens da primeira tela, conforme segue abaixo:

* Atenção especial para o nome (como você encontrará na listagem para futuras manutenções),
* Visões de loja: Selecionar a opção TODAS AS VISÕES DE LOJA,
* Prioridade: Informe de 0 a 99, sendo 0 o mais alto,

### Aba O QUE MOSTRAR:

* Crie a sua tabela via HTML, clicando em SHOW/HIDE EDITOR ou insira utilizando o editor,
* Caso possuir alguma customização CSS especifica é no campo CSS DO MODELO que deve ser informado,
* Ao final da página possui modelos que você pode utilizar como base,

### Aba ONDE MOSTRAR:

Nesta tela você deve montar a regra de como será exibido, neste exemplo usaremos conforme instruido acima, utilizando a opção de atributo.

10 -> Clique no + que indica o seletor de opções,

![opções de atributo](https://github.com/Buzz-Dev-Web/Tutoriais/blob/master/Magento_2/26%20-%20Tabela%20de%20Medidas%20M%C3%B3dulo%20MagePlaza/images/5-opcoes-atributo.png)

11 -> Selecione o atributo que você criou anteriormente,

![tabela de medidas selecionada](https://github.com/Buzz-Dev-Web/Tutoriais/blob/master/Magento_2/26%20-%20Tabela%20de%20Medidas%20M%C3%B3dulo%20MagePlaza/images/6-tabela-de-medidas-e.png)

12 -> Ao lado do nome do atributo ficou o texto: é...

![tabela de medidas opcoes do atributo](https://github.com/Buzz-Dev-Web/Tutoriais/blob/master/Magento_2/26%20-%20Tabela%20de%20Medidas%20M%C3%B3dulo%20MagePlaza/images/7-tabela-de-medidas---.png)

13 -> Clique no ... e selecione a opção do atributo que você criou que será vinculado a esta tabela,

### Aba COMO MOSTRAR:

Aqui é a etapa mais importante (visualmente), pois referencia onde a tabela de medidas será exibida.

14 -> Selecione como sua tabela deve ser exibida, iremos utilizar a opção Guia Produto.

15 -> Pronto, você configurou a tabela de medidas.

Agora você deve acessar o cadastro do produto e selecionar a opção da tabela a qual você vinculou no atributo na etapa 10. Caso tenha mais tabelas repita o processo desde a etapa 7, desde que você já tenha previamente criado as opções dos atributos. Caso não tenha criado as opções dos atributos, retorne AO GERENCIAR OPCOES da etapa 3 e insira novas opções.

16 -> Resultado esperado:

![Resultado esperado](https://github.com/Buzz-Dev-Web/Tutoriais/blob/master/Magento_2/26%20-%20Tabela%20de%20Medidas%20M%C3%B3dulo%20MagePlaza/images/8-resultado-tabela.png)


Dúvidas consulte o dept. de desenvolvimento.