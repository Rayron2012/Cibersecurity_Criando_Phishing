#Criando um Phishing no Kali Linux

Utilizando o KALI para criar um clone da pagina de login do Facebook, basta seguir os passos abaixo que você tera o mesmo resultado :)

1. Primeiramente precisaremos de ter o Kali, pode ser em uma VM.

2. Para essa técnica, vamos utilizar o social engineering toolkit (Setoolkit), você pode procurar no menu do kali, ou apenas abrir o terminal com o CTRL+ALT+T, logo em seguida digite sem aspas "sudo su" de enter, logo em seguida digite a senha adm. Após a senha basta digitar setoolkit e apertar enter como na imagem abaixo:

![image](https://user-images.githubusercontent.com/100003639/205455246-5fe2fb2f-a713-42c9-887d-f73745c64242.png)

3. Após o passo anterior aparecera um menu com algumas opções e para nós escolheremos a primeira 1 Social engineering attacks:

![image](https://user-images.githubusercontent.com/100003639/205455350-6888fdac-5f3b-4bba-9a4e-adb2aae07798.png)

4.Depois selecione a opção de numero 2 Website atack vectors:

![image](https://user-images.githubusercontent.com/100003639/205455389-887e7fcd-4b41-43c4-af68-481d3723a57f.png)

5. Em seguida selecionar a opção 3 Credential Harvester Attack Method:

![image](https://user-images.githubusercontent.com/100003639/205455610-8c4f6364-2081-4a85-b0c1-1283f5ad64c5.png)

6. Nesta ocasião iremos testar um clone de um site, então selecione a opção de numero 2 Site Cloner:

![image](https://user-images.githubusercontent.com/100003639/205455748-89677f51-69a8-49ff-91f2-fd9a2c1e4930.png)

7. Para o próximo passo, basta apenas digitar o IP que você quer que seja criado o clone, podemos utilizar o IP da nossa maquina, basta apenas dar enter ou digitar ifconfig:

![Captura de tela 2022-12-03 151740](https://user-images.githubusercontent.com/100003639/205455824-6ca7974c-a401-4fa0-85a6-22f8a3fe0f69.png)

8. Escolha o site no qual deseje clonar, no nosso caso o escolhido foi o Facebook, basta apenas digitar http://www.facebook.com:

![image](https://user-images.githubusercontent.com/100003639/205455952-09a6f7fa-ab81-4ab5-951b-2205664ffb49.png)

9. Agora jogue o seu IP no Chrome, por exemplo e vera a tela de ‘login’, faça o teste e digite um e-mail e uma senha “podendo ser Fake”:

![image](https://user-images.githubusercontent.com/100003639/205456263-3ace9e07-0d2e-42f2-bfe9-46530846abb5.png)

10. Pronto, após tentar logar na pagina volte ao setoolkit e veja os resultados como na imagem abaixo:

![image](https://user-images.githubusercontent.com/100003639/205456824-00a4a40c-7b14-4655-8235-cbff7c69b74d.png)

Apenas um lembrete, todo o conteúdo tem o teor completamente didático, me tirando qualquer responsabilidade pelo uso ou consequência do que foi ensinado aqui para outros meios.

Espero que tenha gostado!
