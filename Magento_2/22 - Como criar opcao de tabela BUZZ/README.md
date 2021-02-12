# Como criar opção de tabela BUZZ

## Configurando o Atributo

1 -> No menu lateral esquerdo abra Lojas > Atributos > Produto;

![opção do atributo](https://github.com/Buzz-Dev-Web/Tutoriais/blob/master/Magento_2/22%20-%20Como%20criar%20opcao%20de%20tabela%20BUZZ/images/imagem1.png)

2 -> Abra o atributo criado previamente;

3 -> Desça até gerenciar opções e clique em adicionar opção;

![opção do atributo](https://github.com/Buzz-Dev-Web/Tutoriais/blob/master/Magento_2/22%20-%20Como%20criar%20opcao%20de%20tabela%20BUZZ/images/imagem2.png)

4 -> Clique em SALVAR E CONTINUAR EDITANDO, após salvo, clique com o botão direito do mouse na checkbox da opção a ser criado a tabela, posteriormente clique em inspecionar elemento;

![opção do atributo](https://github.com/Buzz-Dev-Web/Tutoriais/blob/master/Magento_2/22%20-%20Como%20criar%20opcao%20de%20tabela%20BUZZ/images/imagem3.png)

5 -> Irá abrir uma janela de código, você verá que tem uma linha destacada pois foi nela que você clicou para inspecionar, neste campo haverá uma palavra value e dentro dela terá um número, copie este número, pois é com ele que será vinculado a imagem, feito isso basta fechar essa janela e voltar para o painel principal do Magento;

![opção do atributo](https://github.com/Buzz-Dev-Web/Tutoriais/blob/master/Magento_2/22%20-%20Como%20criar%20opcao%20de%20tabela%20BUZZ/images/imagem4.png)

## Criando Bloco Estático

6 -> Agora vá para Conteúdo > Elementos > Blocos

![opção do bloco](https://github.com/Buzz-Dev-Web/Tutoriais/blob/master/Magento_2/22%20-%20Como%20criar%20opcao%20de%20tabela%20BUZZ/images/imagem5.png)

7 -> Clique em "Adicionar novo Bloco" no canto superior direito;

8 -> No título do bloco coloque de forma que você consiga encontrar com facilidade, o identificador é obrigatório seguir o padrão "tabela_de_medidas_XXXXX" no lugar do XXXXX coloque o número que você copiou do value no tópico 5. É através deste digito que você irá vincular com a opção criada;

9 -> Em conteúdo clique em insert > images, faça upload das tabelas de medidas, porém lembre-se de seguir a ordem expressa abaixo: 

DESKTOP/NOTEBOOK e posteriormente a imagem para dispositivos móveis;

10 -> Feito o upload das imagens clique em "Show / Hide Editor", a visão mudará para código, você verá duas tag img a primeira é referente a imagem desktop e a segunda referente a imagem de dispositivos móveis, efetue as inserções das classes CSS conforme segue: 

Depois da tag img coloque: class="zz-horizontal", na segunda imagem coloque: class="zz-vertical";

![opção do bloco](https://github.com/Buzz-Dev-Web/Tutoriais/blob/master/Magento_2/22%20-%20Como%20criar%20opcao%20de%20tabela%20BUZZ/images/imagem6.png)

11 -> Caso tenha seguido o processo de forma correta a tabela já estará disponível para você selecionar no cadastro do produto.

Dúvidas consulte o dept. de desenvolvimento