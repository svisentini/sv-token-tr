# sv-token-tr
Gerador de token de acesso

Gera o token de acesso utilizando informações passadas como parametro

# Parametros

-user => É o usuário da aplicação

-pass => Senha de acesso à aplicação

-system => Código do sistema (Ex.: 2 para o Export)

Ambiente : Nesse caso, as opções disponíveis são "-DEV"  ou "-QA"

# Saída

Serão exibidas as informações juntamente com o token gerado.

Obs: O token será copiado automaticamente para o clipboard.

# Para gerar o .jar
Build >> Build Artifacts

Será gerado no seguinte diretorio:

sv-token-tr\out\artifacts\token_jar\token.jar

