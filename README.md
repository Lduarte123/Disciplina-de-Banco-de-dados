# Disciplina-de-Banco-de-dados

## Revisão de Banco de dados 

1. cadastro de alunos de uma escola 
-- Nome, idade, turma, contatos, turno, nome dos pais, cpf, comprovante de enderenço, historico escolar
2. Controle de Livros em biblioteca
 -- Tabela Biblioteca: Codigo de cadatro, Noem do livro, Ano do Livro, categoria
 -- Pessoa: nome , cpf, cep, endereço, numero de telefone
3. Sistema de registro de consultas medicas 
-- medico: nome, consultório, horário
-- paciente: nome, sintomas, idade, genero, peso, altura, condiçoes, laudo
-- Receita: Quantidades, Tratamento, nome do remedio
4. Gerenciamento de Pedidos em um Restaurante
-- Tabela Clientes: Nome, endereço, cpf, pedidos
-- Tabela Cardapio: Pratos, bebidas, acompanhamentos
-- Tabela pedidos: Clientes, Pedidos escolhidos 
5. Sistema de Matrículas em uma Academia
-- Tabelas Alunos: Nome, idade, cpf, endereço, cep, assinatura, data de pagamento, atividades físicas realizadas
-- Tabela instrutor: Nome, turno, período, alunos
-- Tabela Administrador: Nome, id
6. Loja de Eletrônicos
-- Tabela Produtos: Nome dos produtos, preco, descrição , Quantidades
-- Tabela Estoque: idproduto, Quantidades
7. Organização de Eventos
-- Tabela Eventos: Nome do evento, data do evento, organizadora
-- Tabela palestrante: Nome do palestrante
8. Sistema de Hospedagem em um Hotel
--Tabela Hóspedes: Nome, CPF, telefone, e-mail
--Tabela Quartos: Número do quarto, tipo (simples, duplo, suíte), preço por diária, status (livre/ocupado)
--Tabela Reservas: Hóspede, quarto, data de entrada, data de saída, valor total
9. Cadastro de Animais em um Pet Shop
--Tabela Animais: Nome do animal, espécie, raça, idade, peso, ID do dono
--Tabela Donos: Nome, CPF, telefone, endereço
--Tabela Serviços: Tipo de serviço (banho, tosa, vacinação), data, ID do animal, preço
10. Gerenciamento de Vendas em uma Loja de Roupas
--Tabela Clientes: Nome, CPF, telefone, e-mail
--Tabela Produtos: Nome, preço, categoria, tamanho, quantidade disponível
--Tabela Vendas: ID do cliente, ID do produto, data da venda, quantidade, valor total
11. Sistema de Biblioteca Escolar
--Tabela Livros: Código do livro, título, autor, editora, categoria, quantidade disponível
--Tabela Alunos: Nome, CPF, turma, telefone
--Tabela Empréstimos: ID do aluno, ID do livro, data de empréstimo, data de devolução
12. Controle de Estoque em uma Farmácia
--Tabela Medicamentos: Nome do medicamento, quantidade, data de validade, preço unitário
--Tabela Fornecedores: Nome do fornecedor, CNPJ, telefone, endereço
--Tabela Compras: ID do fornecedor, ID do medicamento, data da compra, quantidade adquirida
13. Sistema de Registro de Corridas de Táxi
--Tabela Motoristas: Nome, CPF, CNH, telefone, veículo (modelo/placa)
--Tabela Passageiros: Nome, CPF, telefone
--Tabela Corridas: ID do motorista, ID do passageiro, origem, destino, valor, data
14. Organização de Turmas em uma Escola de Música
--Tabela Alunos: Nome, CPF, idade, instrumento de interesse
--Tabela Professores: Nome, especialidade (instrumento), telefone
--Tabela Turmas: Nome da turma, instrumento, ID do professor, IDs dos alunos
15. Plataforma de Cursos Online
--Tabela Cursos: Nome do curso, categoria, preço, ID do professor
--Tabela Professores: Nome, CPF, especialidade, telefone
--Tabela Inscrições: ID do aluno, ID do curso, data de inscrição
16. Sistema de Gerenciamento de Viagens
--Tabela Pacotes: Nome do pacote, destino, preço, data de embarque, data de retorno
--Tabela Clientes: Nome, CPF, telefone, endereço
--Tabela Reservas: ID do cliente, ID do pacote, data da reserva, quantidade de pessoas
17. Plataforma de Streaming de Vídeos
--Tabela Filmes e Séries: Nome, categoria, ano de lançamento, classificação indicativa, duração
--Tabela Usuários: Nome, e-mail, data de assinatura
--Tabela Histórico de Visualização: ID do usuário, ID do filme/série, data de visualização
18. Sistema de Gerenciamento de Hospital
--Tabela Pacientes: Nome, CPF, idade, gênero, condições médicas
--Tabela Médicos: Nome, CRM, especialidade, telefone
--Tabela Tratamentos: ID do paciente, ID do médico, medicamentos prescritos, data de início, data de término
19. Sistema de Gerenciamento de Projetos
--Tabela Projetos: Nome do projeto, descrição, prazo, ID do gerente
--Tabela Funcionários: Nome, CPF, cargo, telefone
--Tabela Tarefas: ID do projeto, ID do funcionário, descrição da tarefa, status, prazo
20. Plataforma de Ensino com Avaliações Online
--Tabela Cursos: Nome do curso, descrição, ID do professor
--Tabela Professores: Nome, CPF, especialidade, contato
--Tabela Alunos: Nome, CPF, e-mail, ID do curso
--Tabela Avaliações: ID do aluno, ID do curso, nota, data da avaliação