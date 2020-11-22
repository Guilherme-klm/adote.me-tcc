
## Mapeamento das Personas
 - Usuário não cadastrado: Cliente que irá usar a plataforma
 
## História de Usuário - _três aspectos críticos ( 3Cs)_

## **História 1**

**Como um** usuário não cadastrado   
**Quero** me cadastrar  
**Para** para ter um perfil com os meus dados.

### CENÁRIOS:

**Cenário 1: Cadastro com sucesso**  
**Dado** que sou um usuário não cadastrado  
**E** desejo me cadastrar  
**E** preencher os campos nome completo, email, senha, data de nascimento e o endereço onde mora  
**Quando** clicar no botão “Cadastrar-me”  
**Então** o cadastro no usuário estará completo  
**E** pronto para entrar na sua conta  

**Cenário 2: Cadastro com email inválido**  
**Dado** que sou um usuário não cadastrado  
**E** desejo me cadastrar  
**E** preencher os campos nome completo, email, senha, data de nascimento e o endereço onde mora  
**E** o email estiver sem “@”  
**Quando** clicar no botão “Cadastrar-me”  
**Então** o cadastro dará erro  
**E** será avisado onde ocorre o erro para o usuário arrumar  

**Cenário 3:  Cadastro sem sucesso - senha inválida menos 4 caracteres**  
**Dado** que sou um usuário não cadastrado  
**E** desejo me cadastrar  
**E** preencher os campos nome completo, email, senha, data de nascimento e o endereço onde mora  
**E** a senha estiver com menos de 4 caracteres   
**Quando** clicar no botão “Cadastrar-me”  
**Então** o cadastro dará erro  
**E** será avisado onde ocorre o erro para o usuário arrumar  

**Cenário 4:  Cadastro sem sucesso-  senha inválida sem uma letra maiúscula**  
**Dado** que sou um usuário não cadastrado  
**E** desejo me cadastrar  
**E** preencher os campos nome completo, email, senha, data de nascimento e o endereço onde mora  
**E** a senha estiver sem uma letra maiúscula  
**Quando** clicar no botão “Cadastrar-me”  
**Então** o cadastro dará erro  
**E** será avisado onde ocorre o erro para o usuário arrumar  

**Cenário 5: Cadastro sem sucesso - menor de 14 anos**   
**Dado** que sou um usuário não cadastrado  
**E** desejo me cadastrar  
**E** preencher os campos nome completo, email, senha, data de nascimento e o endereço onde mora  
**E** o usuário tiver menos de 14 anos  
**Quando** clicar no botão “Cadastrar-me”  
**Então** o cadastro dará erro  
**E** será avisado onde ocorre o erro para o usuário arrumar  

## **História 2**

**Como um** um usuário não cadastrado   
**Quero** visualizar as publicações  
**Para** adotar um animal.

### CENÁRIOS:

**Cenário 1: Visualizar publicações**  
**Dado** que sou um usuário não cadastrado  
**E** desejo visualizar as publicações  
**Quand**o clicar no botão “Publicações”  
**Então** o usuário visualiza as publicações  

## **História 3**

**Como um** um usuário não cadastrado   
**Quero** criar uma publicação  
**Para** adotar um animal.

### CENÁRIOS:

**Cenário 1: Erro ao criar publicação**  
**Dado** que sou um usuário não cadastrado  
**E** desejo criar uma nova publicação  
**Quando** clicar no botão “Nova Publicação”  
**Então** o sistema deve bloquear esta ação  
**E** deve lançar a mensagem “É necessário estar logado”  
**E** deve aparecer um botão que redirecione o usuário a se cadastrar/logar.  

## **História 4**

**Como um** um usuário não cadastrado   
**Quero** editar minha publicação  
**Para** mudar a descrição.

### CENÁRIOS:

**Cenário 1: Erro ao editar publicação**  
**Dado** que sou um usuário não cadastrado  
**E** desejo editar uma publicação  
**Quando** clicar no botão “Editar Publicação”  
**Então** o sistema deve bloquear esta ação  
**E** deve lançar a mensagem “Não foi possível editar a publicação, entre em uma conta onde tenha permissão”  
**E** deve aparecer um botão que redirecione o usuário a se cadastrar/logar.   

## **História 5**

**Como um** um usuário não cadastrado   
**Quero** curtir minha publicação  
**Para** que o dono da publicação saiba que foi visualizado a publicação dele.

### CENÁRIOS:

**Cenário 1: Erro ao curtir publicação**  
**Dado** que sou um usuário não cadastrado  
**E** desejo curtir uma publicação  
**Quando** clicar no botão “Curtir”  
**Então** o sistema deve bloquear esta ação  
**E** deve lançar a mensagem “Vish, parece que você não está logado. Entra na sua conta”.  
**E** deve aparecer um botão que redirecione o usuário a se cadastrar/logar.  

## **História 6**

**Como um** um usuário não cadastrado   
**Quero** comentar uma publicação  
**Para** que possa informar o usuário com alguma informação.  

### CENÁRIOS:

**Cenário 1: Erro ao comentar publicação**  
**Dado** que sou um usuário não cadastrado  
**E** desejo comentar uma publicação  
**Quando** eu publico este comentário  
**Então** o sistema deve bloquear esta ação  
**E** deve lançar a mensagem “Vish, parece que você não está logado. Entra na sua conta”.  
**E** deve aparecer um botão que redirecione o usuário a se cadastrar/logar.  
