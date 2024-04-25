## Requisitos Não Funcionais

### Usabilidade
- **RNF01:** O aplicativo deve carregar o cardápio em menos de 3 segundos para garantir uma experiência de usuário rápida e eficiente.
- **RNF02:** Todas as operações de pedido, incluindo seleção de itens e conclusão do pedido, devem ser realizadas em menos de 5 segundos para manter a fluidez do processo.

### Desempenho
- **RNF03:** O aplicativo deve ser capaz de suportar até 1000 usuários simultâneos durante os horários de pico sem comprometer o tempo de resposta.
- **RNF04:** O tempo médio de resposta do sistema ao acessar o cardápio e ao realizar operações de pedido não deve exceder 2 segundos, mesmo sob carga máxima.

### Segurança
- **RNF05:** O sistema de pagamento integrado deve utilizar criptografia SSL/TLS para proteger os dados financeiros dos usuários durante as transações.
- **RNF06:** O aplicativo deve implementar autenticação de dois fatores para garantir a segurança das contas dos usuários contra acesso não autorizado.

### Confiabilidade
- **RNF07:** O sistema deve ter uma disponibilidade de serviço de pelo menos 95%, garantindo que o aplicativo esteja acessível aos usuários a maior parte do tempo.
- **RNF08:** O sistema deve ser capaz de recuperar automaticamente de falhas, com um tempo máximo de indisponibilidade de 1 minuto em caso de falha inesperada.

### Compatibilidade
- **RNF09:** O aplicativo deve ser compatível com dispositivos móveis e tablets que executem iOS 11 ou posterior e Android 7.0 ou posterior.
- **RNF10:** O aplicativo deve ser testado e compatível com os navegadores mais recentes, incluindo Google Chrome, Safari, Mozilla Firefox e Microsoft Edge.

### Manutenção
- **RNF11:** O código-fonte do aplicativo deve ser de fácil compreensão e seguir as diretrizes de codificação definidas para facilitar a manutenção e o desenvolvimento futuro.
- **RNF12:** O sistema deve ser projetado com uma arquitetura escalável que permita a adição de novos recursos e funcionalidades sem interromper o funcionamento do aplicativo.

### Legal e Regulatório
- **RNF13:** O sistema deve estar em conformidade com a Lei Geral de Proteção de Dados Pessoais (LGPD) para garantir a privacidade e segurança dos dados dos usuários.
- **RNF14:** O aplicativo deve exibir claramente os termos de serviço e a política de privacidade, garantindo que os usuários estejam cientes das práticas de coleta e uso de dados.
