# Alerta Simples Nacional

## Opções de configuração (deploy)

### Variáveis de ambiente:
* **AMBIENTE**: Ambiente de execução pode ser desenv, homolog e prod;
* **CHAVE_SECRETA_JWT**: Chave secreta JWT, deve ser a chave compartilhada salva no Vault no caminho secret/sefaz/**AMBIENTE**/delivery atributo sfz-vault-jwt-secret-key;
* **ROLE_ID**: Role Id do app role da aplicação;
* **SECRET_ID**: Secret Id do app role da aplicação;
* **SENHA_JKS_CADEIA_SEFAZ**: Senha do JKS com a cadeia certificadora da sefaz, pode ser encontrado no caminho do vault secret/sefaz/**AMBIENTE**/delivery sfz-vault-jks-cadeia-sefaz-password;