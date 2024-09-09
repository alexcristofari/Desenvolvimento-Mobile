# Projeto: Cadastro de Aluno

Este projeto é uma aplicação Android simples para **cadastrar alunos**, onde o usuário pode inserir o nome, CPF e telefone de um aluno e salvar as informações. A interface conta com três campos de entrada e botões para realizar as operações de salvar, atualizar e excluir alunos de uma lista.

## Funcionalidades:

1. **Cadastro de Aluno**: 
   - O usuário pode inserir o nome, CPF e telefone de um aluno, e ao clicar no botão "Salvar", os dados são adicionados a uma lista exibida na interface.

2. **Listagem de Alunos**:
   - Após o cadastro, o aluno aparece em uma lista de visualização (ListView). Cada aluno é exibido como um item na lista.

---

# Projeto: Métodos de Excluir e Atualizar Aluno

Além da funcionalidade de cadastro, o projeto também inclui os métodos para **atualizar** e **excluir** alunos da lista.

## Funcionalidades adicionais:

1. **Atualizar Aluno**:
   - O botão "Atualizar" permite que o usuário selecione um aluno da lista, modifique os dados e, ao clicar no botão, as informações desse aluno são atualizadas na lista. O botão de "Atualizar" fica desabilitado até que um aluno seja selecionado.

2. **Excluir Aluno**:
   - O usuário pode selecionar um aluno da lista e, ao clicar no botão "Excluir", esse aluno será removido da lista.

3. **Interação com a Lista**:
   - Ao selecionar um aluno na lista, os dados são preenchidos nos campos de entrada, permitindo que o usuário atualize ou exclua o aluno selecionado.

---

## Tecnologias Usadas

- **Kotlin**: Linguagem de programação usada no projeto Android.
- **View Binding**: Para manipulação eficiente dos elementos da interface.
- **ListView**: Para exibir a lista de alunos cadastrados.

---

## Instruções de Uso

1. Clone este repositório para sua máquina local.
2. Abra o projeto no **Android Studio**.
3. Execute o aplicativo em um dispositivo ou emulador Android.
4. Use os campos de entrada para adicionar alunos e interaja com os botões de "Atualizar" e "Excluir" para gerenciar os alunos cadastrados.

---

## Próximos Passos

- **Armazenamento Persistente**: Adicionar suporte para armazenar os dados em um banco de dados SQLite ou Room, para que os dados dos alunos não se percam ao fechar o aplicativo.
- **Melhorias de Interface**: Melhorar a responsividade da interface e adicionar animações para as interações.


