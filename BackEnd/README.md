# BACK END
Back end do desafio bridge fullstack

## Como rodar localmente
Para funcionar, é necessário configurar o banco de dados antes de mais nada. Depois disso, basta executar o programa via IDE ou via executável.

## Configurando o banco de dados

### Postgresql
1. Vá <a href="#">neste link</a> e aperte na primeira opção da segunda linha caso seja windows. Caso não...
2. Execute o instalador para baixar
3. Aperte next, next e finish, porém, quando pedir uma senha, escreva a que deseja.
4. Vá na aba server e crie um banco de dados de nome DB_HISTORY (sugestão).
5. Pronto, o banco de está configurado.


## Executando o programa

### Rodando via NetBeans
### Passos
1. Baixe o arquivo zip.
2. Inicie o netBeans. Caso não tenha <a href="#">baixe aqui</a> e configure-a.
3. Após aberto, modifique o arquivo 
3. Depois que estiver aberta e carregado, vá no canto superior esquerdo e aperte em files e em seguida import zip.
4. Feito isso, vá onde está o zip do projeto e clique nele duas vezes e aperte ok.
5. Após carregar tudo certinho, aperte para rodar lá em cima da barra de ferramentas no play verde.
6. Pronto, o backend está rodando

### Rodando via executável (preferêncial)
### Passos
1. Baixe o arquivo zip. 
2. Extraia o arquivo no local que deseja.
3. Copie o caminho dele, abra o terminal cmd, digite nele "cd caminho_copiado" e aperte enter.
4. Em seguida digite "mvn clean package" e copie o nome do arquivo jar gerado na pasta target dentro do projeto.
5. Quando terminar o build do projeto, escreva ainda no cmd "cd target" e, em seguida, "java -jar nome_arquivo.jar" para executar.
6. Pronto, o backend já está rodando


