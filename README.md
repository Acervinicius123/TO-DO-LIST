
# To-Do List App README

Este é um aplicativo simples de lista de tarefas (to-do list) desenvolvido em JavaScript, HTML e CSS, utilizando o armazenamento local do navegador para manter os dados das tarefas.

## Funcionalidades

### Adicionar Nova Tarefa

- Os usuários podem adicionar novas tarefas digitando o texto no campo de entrada e pressionando Enter ou clicando em um botão de adicionar.
- Se o campo estiver vazio, o usuário será alertado para digitar algo antes de adicionar à lista.
- Se a tarefa já existir na lista, o usuário será alertado sobre isso.

### Remover Tarefa

- Cada item da lista de tarefas tem um botão de marcação para remoção.
- Ao clicar no botão de marcação, a tarefa correspondente será removida da lista.

### Persistência de Dados

- As tarefas adicionadas são armazenadas localmente no navegador do usuário usando o armazenamento local.
- Isso significa que as tarefas permanecerão mesmo se o usuário atualizar a página ou fechar o navegador.

## Estrutura do Código

O código é composto por três funções principais:

1. **validateExiste()**: Esta função valida se a tarefa já existe na lista.

2. **newtask()**: Esta função é chamada quando o usuário adiciona uma nova tarefa. Ela verifica se a entrada é válida e se a tarefa já existe. Se tudo estiver correto, a nova tarefa é adicionada à lista.

3. **removeItem(data)**: Esta função remove a tarefa da lista quando o usuário clica no botão de marcação.

## Como Utilizar

1. Clone ou baixe este repositório para o seu computador.

2. Abra o arquivo `index.html` em um navegador da web.

3. Comece a adicionar suas tarefas na lista!

## Contribuindo

Sinta-se à vontade para contribuir com melhorias neste projeto. Se você tiver alguma ideia ou encontrar problemas, abra uma issue ou envie um pull request.

---

Este README fornece uma visão geral básica do aplicativo e como utilizá-lo. Se desejar, você pode adicionar mais detalhes, como instruções de instalação ou personalizações possíveis.
