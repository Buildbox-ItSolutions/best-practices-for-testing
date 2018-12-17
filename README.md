# practices-for-testing
Manual de boas práticas para a realização de testes da Buildbox IT Solutions

## 1 - Abertura de ocorrências (bugs)
* Abrir o [Jira](https://buildbox.atlassian.net)
* Verificar se a sprint de bugs está criada, senão é necessário criá-la, exemplo: **"Projeto - Sprint 1 [Bugs]"**
* Ao abrir um bug, utilizar padronização no título e descrição. Exemplo:
  * **Título do Card**: [Web - Painel] [Login Admin, Login Convidado] Mensagem incorreta
  * **Descrição do Card**: 
    * **Cenário**: Realização de login com a senha incorreta
    * **Resultado esperado**: A mensagem esperada é "Usuário e/ou senha incorretos"
    * **Resultado obtido**: Após a realização de login com a senha incorreta, a mensagem esperada é "Usuário e/ou senha incorretos"
* Estar atento para evitar a duplicação de Bugs na mesma plataforma, exemplo 
* Ajustes de design precisam ser previamente aprovados pelo Product Owner (para feedback com o cliente) e Scrum Master (para análise de esforço e priorização do Backlog) para então serem discutidos com o a Equipe UI/UX
* A partir do momento que o bug do card em questão for corrigido, porém existam novas situações que geraram bugs, novos cards precisam ser abertos

## 2 - Classificação das ocorrências
* É desejável que o problema seja identificado e classificado para criar uma melhor orientação para a equipe técnica.
* Podemos classificar com os seguintes rótulos:
	* [Plataforma] Regra de Negócio
	* [Plataforma] Layout
	* .... //TODO

## 3 - Observações para testes
### 3.1 - Web (Painel)
* Em componentes Datatables, por limitações técnicas, palavras acima de 20 caracteres podem o layout do componente. Por outro lado é uma situação que é muito difícil de acontecer, logo este caso de teste pode ser despriorizado.
* //TODO

