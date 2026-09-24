## 🛡️ Validações e segurança da automação

O AutoMessage possui mecanismos de validação durante a execução para aumentar a segurança do processo e evitar envios incorretos ou duplicados.

Entre as validações realizadas estão:

- Limite de até **50 atendimentos por execução**;
- Verificação de que existe um atendimento carregado antes de iniciar o processo;
- Controle para evitar que o mesmo aluno seja processado duas vezes na mesma execução;
- Verificação de que o campo de mensagem está vazio antes de inserir uma nova mensagem;
- Confirmação de que a mensagem foi preenchida corretamente antes do envio;
- Verificação de que o botão de envio está habilitado;
- Confirmação de que a mensagem foi efetivamente registrada no histórico da conversa;
- Atualização da fila após cada envio;
- Verificação de que o próximo atendimento foi carregado corretamente antes de continuar.

Essas validações fazem com que a automação não apenas execute as etapas do processo, mas também **confirme cada ação antes de avançar para a próxima**.

Dessa forma, o AutoMessage foi desenvolvido para reduzir o risco de envios duplicados, mensagens incompletas ou avanço incorreto entre os atendimentos.
