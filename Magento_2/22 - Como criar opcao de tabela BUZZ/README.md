# Como criar opção de tabela BUZZ

## Configurando o Atributo

1 -> No menu lateral esquerdo abra Lojas > Atributos > Produto;

![opção do atributo](https://github.com/Buzz-Dev-Web/Tutoriais/blob/master/Magento_2/22%20-%20Como%20criar%20opcao%20de%20tabela%20BUZZ/images/imagem1.png)

2 -> Abra a tabela que você criou;

3 -> Desça até gerenciar opções e clique em adicionar opção (adicione pelo menos 2. ex: Nenhuma, Tabela);

![opção do atributo](https://github.com/Buzz-Dev-Web/Tutoriais/blob/master/Magento_2/22%20-%20Como%20criar%20opcao%20de%20tabela%20BUZZ/images/imagem2.png)

4 -> Clique em Salvar e continuar, salvo, agora clique com o botão direito do mouse na checkbox da opção (ex: Tabela) e clique em inspecionar elemento;

![opção do atributo](https://github.com/Buzz-Dev-Web/Tutoriais/blob/master/Magento_2/22%20-%20Como%20criar%20opcao%20de%20tabela%20BUZZ/images/imagem3.png)

5 -> Irá abrir uma janela de código, você verá que tem uma linha destacada pois foi nela foi usado a opção inspecionar, nela haverá uma palavra value e dentro dela terá um número, copie ele, iremos precisar dele mais tarde, feito isso basta fechar essa janela e voltar para o menu do magento;

![opção do atributo](https://github.com/Buzz-Dev-Web/Tutoriais/blob/master/Magento_2/22%20-%20Como%20criar%20opcao%20de%20tabela%20BUZZ/images/imagem4.png)

## Criando Bloco Estático

6 -> Agora vá para Conteúdo > Elementos > Blocos

![opção do bloco](https://github.com/Buzz-Dev-Web/Tutoriais/blob/master/Magento_2/22%20-%20Como%20criar%20opcao%20de%20tabela%20BUZZ/images/imagem5.png)

7 -> Clique em "Adicionar novo Bloco" no canto superior direito;

8 -> No título do bloco coloque o nome que quiser, mas no identificador é obrigatório seguir o padrão "tabela_de_medidas_XXXXX" no lugar do XXXXX coloque o número que você copiou do Value no tópico 5;

9 -> Em conteúdo clique em insert > images, faça upload das tabelas de medidas, porém lembre-se de seguir a ordem: DESKTOP e posteriormente a imagem para dispositivos móveis;

10 -> Feito o upload das imagens clique em "Show / Hide Editor", a visão mudará para código, terá duas tag img a primeira é referente a imagem desktop e a segunda referente a imagem do responsivo, efetue as inserções das classes CSS conforme segue: 

depois da tag img coloque: class="zz-horizontal", na segunda imagem coloque: class="zz-vertical";

![opção do bloco](https://github.com/Buzz-Dev-Web/Tutoriais/blob/master/Magento_2/22%20-%20Como%20criar%20opcao%20de%20tabela%20BUZZ/images/imagem6.png)


Dúvidas consulte o dept. de desenvolvimento