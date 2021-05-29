# Kit de Acesso dos participantes

Cada hacka recebeu um arquivo `batalha_de_dados_X_hacka_Y.zip` (X é um número de 1 a 9, indicando o número da conta e Y representa a equipe com letra 'A' ou 'B' para a equipe). Esse arquivo compactado contém 5 arquivos:

- **AcessosConsole.csv:** Um arquivo em formato `csv`, delimitado por vírgulas, com informações relacionadas aos usuários IAM para acesso ao console AWS, juntamento com as credenciais de `accessKey` e `secretKey`;

- **batalha_dedados_X_hacka_Y.pem:** *Key pair* para acesso ssh à instância *Thanos* (Unix) com privilégios de `admin/root`

- **bucket_dados.pdf:** Um slide com o nome do bucket de dados (batalhasocial-iu) e indicação do diretório para cada Estado.

- **LinkConsole_batalha_de_dados_X.txt:** Arquivo de texto com o link para acesso ao console AWS

- **UsuariosLocaisVMs.xlsx:** Arquivo em formato xlsx com as credenciais de usuário e senha para acesso à instância *Joker* (Windows) e ao R-Studio.
