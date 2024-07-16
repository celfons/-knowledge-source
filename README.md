# História de Usuário 1: Iniciação de um Pix

**Como** um usuário pagador, **Eu quero** iniciar um pagamento via Pix, **Para que** eu possa transferir dinheiro de forma rápida e segura.

## Entrega de Valor 1: Inserção Manual dos Dados

**Regra de Negócio:**
- O usuário deve ser capaz de inserir manualmente os dados do recebedor, incluindo CPF/CNPJ, ISPB, número da agência, tipo de conta e número da conta.
- O sistema deve validar os dados inseridos para garantir que estão no formato correto e que todos os campos obrigatórios foram preenchidos.
- Se os dados forem inválidos, o sistema deve exibir uma mensagem de erro clara e específica para o usuário.

## Entrega de Valor 2: Utilização de Informações Previamente Disponibilizadas

**Regra de Negócio:**
- O sistema deve permitir que o usuário selecione informações de recebedores previamente armazenadas.
- As informações armazenadas devem ser exibidas de forma clara e organizada, permitindo fácil seleção.
- O sistema deve garantir que as informações selecionadas estejam atualizadas e válidas antes de iniciar a transação.

# História de Usuário 2: Recebimento de um Pix

**Como** um usuário recebedor, **Eu quero** receber um pagamento via Pix, **Para que** eu possa obter fundos de forma rápida e segura.

## Entrega de Valor 1: Notificação de Recebimento

**Regra de Negócio:**
- O sistema deve notificar o usuário recebedor imediatamente após o recebimento de um Pix.
- A notificação deve incluir detalhes da transação, como valor, nome do pagador e data/hora do recebimento.
- A notificação deve ser enviada através dos canais configurados pelo usuário (e.g., push notification, email, SMS).

## Entrega de Valor 2: Confirmação de Recebimento

**Regra de Negócio:**
- O usuário recebedor deve ser capaz de visualizar e confirmar o recebimento do Pix.
- A confirmação deve registrar a data e hora em que o usuário confirmou o recebimento.
- O sistema deve atualizar o status da transação para "confirmado" após a confirmação do usuário.

# História de Usuário 3: Devolução de um Pix

**Como** um usuário recebedor, **Eu quero** devolver um pagamento via Pix, **Para que** eu possa corrigir transações erradas ou não desejadas.

## Entrega de Valor 1: Iniciação da Devolução

**Regra de Negócio:**
- O usuário recebedor deve ser capaz de iniciar a devolução de um Pix através da interface do sistema.
- O sistema deve permitir a seleção da transação a ser devolvida e a inserção do motivo da devolução.
- O sistema deve validar a solicitação de devolução e exibir uma confirmação antes de processar a devolução.

## Entrega de Valor 2: Confirmação da Devolução

**Regra de Negócio:**
- O sistema deve notificar o usuário pagador sobre a devolução do Pix.
- A notificação deve incluir detalhes da transação devolvida, como valor, motivo da devolução e data/hora da devolução.
- O sistema deve registrar a confirmação da devolução e atualizar o status da transação para "devolvido".

# História de Usuário 4: Autenticação do Usuário Final

**Como** um usuário do Pix, **Eu quero** me autenticar de forma segura, **Para que** eu possa realizar transações Pix com segurança.

## Entrega de Valor 1: Implementação de Autenticação

**Regra de Negócio:**
- O sistema deve exigir autenticação do usuário antes de permitir a iniciação, recebimento ou devolução de um Pix.
- A autenticação deve ser realizada através de métodos seguros, como senha, biometria ou autenticação de dois fatores (2FA).
- O sistema deve bloquear o acesso após várias tentativas de autenticação falhadas e notificar o usuário sobre atividades suspeitas.

# História de Usuário 5: Registro de Chave Pix no DICT

**Como** um usuário do Pix, **Eu quero** registrar minha chave Pix no DICT, **Para que** eu possa utilizar essa chave para receber pagamentos.

## Entrega de Valor 1: Registro de Chave

**Regra de Negócio:**
- O usuário deve ser capaz de registrar uma chave Pix (e.g., CPF/CNPJ, email, telefone, chave aleatória) no DICT.
- O sistema deve validar a chave inserida e verificar se já está em uso.
- O sistema deve registrar a chave no DICT e confirmar o registro ao usuário.

# História de Usuário 6: Exclusão de Chave Pix no DICT

**Como** um usuário do Pix, **Eu quero** excluir minha chave Pix do DICT, **Para que** eu possa parar de usar essa chave para receber pagamentos.

## Entrega de Valor 1: Exclusão de Chave

**Regra de Negócio:**
- O usuário deve ser capaz de excluir uma chave Pix registrada no DICT.
- O sistema deve validar a solicitação de exclusão e confirmar a identidade do usuário.
- O sistema deve excluir a chave do DICT e notificar o usuário sobre a exclusão bem-sucedida.

# História de Usuário 7: Portabilidade de Chave Pix no DICT

**Como** um usuário do Pix, **Eu quero** portar minha chave Pix para outra instituição, **Para que** eu possa continuar usando a mesma chave em uma nova conta.

## Entrega de Valor 1: Portabilidade de Chave

**Regra de Negócio:**
- O usuário deve ser capaz de portar uma chave Pix para outra instituição financeira.
- O sistema deve validar a solicitação de portabilidade e confirmar a identidade do usuário.
- O sistema deve registrar a portabilidade no DICT e notificar ambas as instituições envolvidas.

# História de Usuário 8: Reivindicação de Posse de Chave Pix no DICT

**Como** um usuário do Pix, **Eu quero** reivindicar a posse de uma chave Pix, **Para que** eu possa usar essa chave para receber pagamentos.

## Entrega de Valor 1: Reivindicação de Posse

**Regra de Negócio:**
- O usuário deve ser capaz de reivindicar a posse de uma chave Pix no DICT.
- O sistema deve validar a solicitação de reivindicação e confirmar a identidade do usuário.
- O sistema deve registrar a reivindicação no DICT e notificar o usuário sobre a posse bem-sucedida.

# História de Usuário 9: Transparência e Clareza nas Tarifas

**Como** um usuário do Pix, **Eu quero** ter clareza sobre as tarifas e gratuidades, **Para que** eu possa entender os custos associados ao uso do Pix.

## Entrega de Valor 1: Divulgação de Tarifas

**Regra de Negócio:**
- O sistema deve divulgar de forma clara e acessível as tarifas, gratuidades e benefícios relativos ao envio e recebimento de um Pix.
- As informações devem ser atualizadas regularmente e estar disponíveis em todos os canais de atendimento ao usuário.
- O sistema deve garantir que o usuário tenha acesso fácil às informações antes de realizar uma transação.

# História de Usuário 10: Bloqueio Cautelar em Caso de Suspeita de Fraude

**Como** um participante do Pix, **Eu quero** que os recursos sejam bloqueados cautelarmente em caso de suspeita de fraude, **Para que** eu possa garantir a segurança das transações.

## Entrega de Valor 1: Implementação de Bloqueio Cautelar

**Regra de Negócio:**
- O sistema deve ser capaz de bloquear recursos cautelarmente em caso de suspeita de fraude.
- O bloqueio deve ser automático e baseado em regras de detecção de fraude predefinidas.
- O sistema deve notificar o usuário e as autoridades competentes sobre o bloqueio e fornecer instruções para resolução.
