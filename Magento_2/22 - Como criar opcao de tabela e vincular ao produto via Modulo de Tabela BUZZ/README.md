# Como criar opção de tabela BUZZ

## Configurando o Atributo

1 -> No menu lateral esquerdo abra Lojas > Atributos > Produto;
(IMAGEM 1)

2 -> Abra a tabela que você criou;

3 -> Desça até gerenciar opções e clique em adicionar opção (adicione pelo menos 2. ex: Nenhuma, Tabela);
(IMAGEM 2)

4 -> Clique em Salvar e continuar, salvo, agora clique com o botão direito do mause na checkbox da opção (ex: Tabela) e clique em especionar elemento;
(IMAGEM 3)

5 -> Irá abrir uma janela de código, você verá que tem uma linha destacada pois foi nela que demos o especinar, nela averá uma palavra value e dentro dela terá um número, copie ele, iremos precisar dele mais tarde, feito isso basta fechar essa janela e voltar para o menu do magento;
(IMAGEM 4)

## Criando Bloco Estático

6 -> Agora vá para Conteúdo > Elementos > Blocos;
(IMAGEM 5)

7 -> Clique em "Adicionar novo Bloco" no canto superior direito;

8 -> No título do bloco coloque o nome que quiser, mas no identificador é obrigatório ter "tabela_de_medidas_XXXXX" no lugar do XXXXX coloque o número que você copiou do Value no tópico 5;

9 -> Em conteúdo clique em insert > images, faça upload das imagens que quiser usar, mas faça upload primeiro da imagem que será visualizada no Desktop e depois a do Mobile;

10 -> Feito o upload das imagens clique em "Show / Hide Editor", a visão mudará para código, terá duas tag img a primeira é o desktop, depois de img coloque esse código class="zz-horizontal", na segunda imagem coloque essa class="zz-vertical" no mesmo lugar;
(IMAGEM 6)


Dúvidas consulte o dept. de desenvolvimento