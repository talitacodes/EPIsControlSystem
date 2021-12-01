# EPIsControlSystem
O sistema em desenvolvimento tem como objetivo permitir ao empregado de uma empresa solicitar EPI´s (Equipamento de Proteção Individual) e ao empregado com cargo de TST(Técnico de Segurança do Trabalho) fazer a análise da solicitação, podendo esta ser aprovada ou reprovada. Além disso, o TST também realiza o cadastro de novos lotes de EPIs atualizando o estoque. 

## Diagrama de Contexto
  O Diagrama de Contexto abaixo descreve o sistema de Controle de EPIs de forma que o empregado solicitará EPIs e acesserá informações sobre as solicitações realizadas. Enquanto o empregado TST analisará essas solicitações e atualizará o estoque com novas remessas de EPIs. 
![image](https://user-images.githubusercontent.com/73146109/138180433-a699170c-0568-4124-9c24-3c0eb2ba9477.png)

## Diagrama de Classes
O Diagrama de Classes abaixo utiliza o GOF no padrão Factory Method
![image](https://user-images.githubusercontent.com/73146109/144165011-2feafecb-194c-4a2b-9fe9-38f4c419089f.png)
 
## Diagrama de Containers
  No Diagrama de Containers, podemos ampliar o sistema em si mostrando a aplicação, o armazenamento de dados e microserviços utilizados.  A aplicação é um sistema em Java que exibe o conteúdo que compõe a página fornecendo todos os recursos do software. A página utiliza uma API JSON/HTTPS, que outra aplicação Java executando no lado do servidor fornece. A aplicação na API obtém informações do usuário, das solicitações e do estoque de EPIs pelo banco de dados. Também é utilizado o sistema de email automático para atualizar o usuário sobre o status da solicitação. 
  
![image](https://user-images.githubusercontent.com/73146109/144154429-99335df3-da5e-4e81-a9ff-9a428625fe82.png)

## Diagrama de Componente
  No Diagrama de Componentes, amplia-se mais uma uma vez, agora mostrando o container com os componentes dentro dele utilizado.
![image](https://user-images.githubusercontent.com/73146109/144157855-a2c1727b-c405-4e3c-9b3c-894709346207.png)







