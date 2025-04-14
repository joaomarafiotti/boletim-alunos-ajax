# boletim-alunos-ajax
## Boletim de Alunos com AJAX

Este projeto implementa uma aplicação de gerenciamento de alunos utilizando AJAX, com integração com um webservice JSON para realizar operações como adicionar, remover e atualizar notas de alunos.

### Funcionalidades:
- **Listagem de Alunos**: Exibe todos os alunos com suas notas e status.
- **Adicionar Aluno**: Permite adicionar novos alunos ao sistema.
- **Remover Aluno**: Remove alunos selecionados da lista.
- **Aumentar ou Diminuir Nota**: Atualiza as notas dos alunos, incrementando ou decrementando 0.5 pontos.
- **Remover o Pior Aluno**: Remove o aluno com a menor média de notas.

### Como Funciona:
A aplicação se comunica com o webservice via AJAX para:
1. **Obter a lista de alunos**.
2. **Adicionar um novo aluno**.
3. **Atualizar as notas de um aluno**.
4. **Remover um aluno específico**.
5. **Remover o aluno com a menor média de notas**.

### Tecnologias Usadas:
- **HTML**: Estrutura da página.
- **CSS**: Estilização da interface com Bulma.
- **JavaScript**: Manipulação de DOM e requisições AJAX.
- **Webservice**: Comunicação com o servidor remoto para gerenciamento dos alunos.

### Como Rodar:
1. Clone o repositório: `git clone https://github.com/joaomarafiotti/boletim-alunos-ajax`
2. Abra o arquivo `boletim.html` no seu navegador.
