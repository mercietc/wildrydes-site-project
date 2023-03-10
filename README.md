# Wild Rydes Site
![image](https://user-images.githubusercontent.com/68623425/222940777-7545cc3d-b48d-4e70-acbe-03862b0407c1.png)

Acesse a aplicação: https://master.dpdjaoqqo1r3b.amplifyapp.com/

Aplicação Web com tecnologia sem servidor que permite que os usuários solicitem caronas em um unicórnio da frota da Wild Rydes. O aplicativo apresenta uma interface de usuário baseada em HTML para indicar o local onde os usuários gostariam de ser apanhados e interage no back-end com um serviço web RESTful para enviar a solicitação e despachar um unicórnio próximo. O aplicativo também oferece facilidades para que os usuários se cadastrem no serviço e façam login antes de solicitar caronas.

A arquitetura da aplicação usa o AWS Lambda, o Amazon API Gateway, o Amazon DynamoDB, o Amazon Cognito e o console do AWS Amplify. O console do Amplify fornece implantação e hospedagem de recursos Web estáticos, inclusive HTML, CSS, JavaScript e arquivos de imagem que são carregados no navegador do usuário. O JavaScript executado no navegador envia e recebe dados de uma API de back-end pública criada usando o Lambda e o API Gateway. O Amazon Cognito oferece funções de autenticação e gerenciamento de usuários para proteger a API do back-end. Por fim, o Amazon DynamoDB fornece uma camada de persistência onde os dados podem ser armazenados pela função do Lambda da API.

![image](https://user-images.githubusercontent.com/68623425/221295676-054ada90-a105-4a6b-b722-524ad90c0c0d.png)
