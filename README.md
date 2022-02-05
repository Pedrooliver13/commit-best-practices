## :computer: Commit 
- Cada commit deve ser uma única alteração lógica. Não faça várias alterações lógicas em um commit. Por exemplo, se corrigir um bug, e otimizar o desempenho de um recurso, divida-o em dois commits separados.

- <b>Não divida uma única alteração lógica em vários commits.</b> Por exemplo, a implementação de um recurso e os testes correspondentes devem estar no mesmo commit. Não divida uma única alteração lógica em vários commits.

- Commit cedo e com frequência . Commits pequenos e autocontidos são mais fáceis de entender e reverter quando algo dá errado.

- Os commits devem ser ordenados logicamente . Por exemplo, se o commit X depende das mudanças feitas no commit Y, então o commit Y deve vir antes do commit X.

## :fax: Mensagens

Uma mensagem de confirmação consiste em três partes distintas separadas por uma linha em branco: o título, o corpo (opcional) e o rodapé (opcional). O layout fica assim:

```
feat: teach how to write commit message

A further explanation is a good practice we recommend you follow.

```
O título é dividido em 2 partes: o tipo e o assunto .

## :mag: Tipos

- feat: Novo Recurso
- fix: Uma correção de bug
- docs: Alteração na documentação
- style: formatação, falta de ponto e vírgula, etc.; sem alteração de código
- test: adição de testes, refatoração de testes; sem alteração de código de produção
- chore: atualizar tarefas de compilação, configurações do gerenciador de pacotes, etc.;

## :book: Como escrever ?

Os assuntos não devem ter mais de 50 caracteres, devem começar com letra maiúscula e não terminar com ponto. Separe o assunto do corpo (quando houver) com uma linha em branco.

```
# GOOD
refactor: Refactor subsystem X for readability
fix: Remove deprecated methods

# BAD
Fixed bug with Y
More fixes from broken stuff

```

Use o corpo para explicar o que e o porquê de um commit, não o como – o código deve fazer isso.
Ao escrever uma mensagem de commit, pense no que você precisaria saber se você executasse o commit daqui a um ano.
