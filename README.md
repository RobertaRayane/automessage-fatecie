# AutoMessage — Automatizando o Primeiro Contato com o Aluno na Mensageria

## 📌 Sobre o projeto

O **AutoMessage** é uma solução de automação desenvolvida para agilizar o primeiro contato com os alunos por meio da mensageria.

Após a atribuição do aluno ao colaborador, é necessário realizar a saudação inicial dentro de um determinado período. Em uma rotina com grande volume de alunos atribuídos, localizar cada conversa, personalizar a mensagem com o nome do aluno e realizar o envio manualmente demanda um tempo significativo.

O AutoMessage automatiza essa etapa, permitindo realizar vários contatos iniciais de forma rápida, organizada e personalizada.

## 🎯 Objetivo

Automatizar uma tarefa repetitiva do atendimento para que o colaborador possa dedicar mais tempo à análise e resolução das demandas dos alunos.

A solução busca:

- Reduzir o tempo gasto com tarefas repetitivas;
- Agilizar o primeiro contato com o aluno;
- Personalizar a saudação com o nome do aluno;
- Padronizar a comunicação inicial;
- Organizar o fluxo de atendimento;
- Aumentar a produtividade em períodos de alto volume.

## ⚙️ Como funciona

O colaborador seleciona a mensagem padrão que deseja utilizar e inicia a automação.

A solução então:

1. Identifica o aluno que está em atendimento;
2. Obtém o nome do aluno;
3. Personaliza a saudação;
4. Preenche a mensagem;
5. Verifica se a mensagem foi preenchida corretamente;
6. Realiza o envio;
7. Confirma o envio no histórico da conversa;
8. Atualiza a fila de atendimentos;
9. Identifica e abre o próximo aluno;
10. Repete o processo até finalizar a fila ou atingir o limite de segurança.

### Fluxo

**Identificar → Personalizar → Preencher → Validar → Enviar → Confirmar → Atualizar fila → Próximo atendimento**

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

## 🚀 Benefícios

- Maior agilidade no primeiro contato;
- Redução de tarefas manuais repetitivas;
- Personalização das mensagens;
- Padronização da saudação;
- Melhor aproveitamento do tempo do colaborador;
- Possibilidade de utilização em diferentes setores que trabalham com mensageria.

## 🛠️ Tecnologias utilizadas

- **JavaScript**;
- **Extensão de navegador**;
- **Automação RPA**.

A automação atua na interface da mensageria realizando ações como localização de informações, preenchimento, cliques e envio das mensagens.

## 🔄 Possibilidades de evolução

O projeto pode ser ampliado para outras tarefas repetitivas do processo de atendimento, permitindo novas automações e possibilidades de ganho de produtividade.

Entre as possibilidades futuras estão:

- Automação de outras etapas do atendimento;
- Criação de novos fluxos automatizados;
- Utilização de diferentes modelos de mensagens;
- Aplicação em outros processos que envolvam tarefas repetitivas;
- Expansão para diferentes setores que utilizam a mensageria.

## 💡 Impacto

O AutoMessage **não substitui o atendimento humano**.

Seu objetivo é automatizar uma etapa operacional e repetitiva para que o colaborador possa dedicar mais tempo ao que realmente importa: **atender, analisar e resolver a demanda do aluno**.

## 📌 Resumo

**Automatizar o que é repetitivo para dedicar mais tempo ao que realmente importa: atender e resolver a demanda do aluno.**

---

**Projeto desenvolvido para o FAIS — Fatecie AI Solutions.**
