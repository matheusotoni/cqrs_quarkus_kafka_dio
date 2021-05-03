## Sobre CQRS - Command Query Responsibility Segregation
> CQRS significa Command Query Responsibility Segregation. Como o nome já diz, é sobre separar a responsabilidade de escrita e leitura de seus dados.
> CQRS é um pattern, um padrão arquitetural assim como Event Sourcing, Transaction Script e etc. O CQRS não é um estilo arquitetural como desenvolvimento em camadas, modelo client-server, REST e etc.

## A Aplicação
Simula um cenário de conta bancária em que um usuário final adiciona uma transação de receita ou despesa e é processado em uma fonte de eventos ascíncrona e arquitetura CQRS para recalcular o saldo da conta bancária do usuário. O usuário também pode solicitar o saldo de sua conta. Aqui embaixo você pode ver o design:

![Design](/images/design.png)