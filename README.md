# Uninga
Classe Despesa
descricao: String  // Para descrever a despesas
valor: double // valor do pagamento
dataV: LocalDate // Data do vencimento

categoria: CategoriaDespesa
exibirDetalhes() // Método para exibir informações da despesa


abstract Classe CategoriaDespesa
calcularValorTotal(List<Despesa> despesas)


Classe Pagamento
dataPagamento: LocalDate
valorPago: double


Classe Usuario
nome: String
login: String
senha: String // criptografada
autenticar(String senhaDigitada) // Verifica se a senha digitada corresponde à senha do usuário



Classe MenuPrincipal
exibirMenu() // Exibe as opções do menu principal
processarOpcao(int opcao) // Chama os métodos correspondentes à opção escolhida pelo usuário




Classe GerenciadorDespesas
inserirDespesa(Despesa despesa) //Adiciona uma despesa à lista de despesas
listarDespesas() // Lista todas as despesas
listarDespesasPendentes() // Lista despesas pendentes
listarDespesasPagas() // Lista despesas pagas





Classe GerenciadorTiposDespesa
criarTipoDespesa(String nome) // Cria um novo tipo de despesa
listarTiposDespesa() // Lista todos os tipos de despesa




Classe GerenciadorUsuarios
cadastrarUsuario(String nome, String login, String senha) // Cadastra um novo usuário
listarUsuarios() // Lista todos os usuários cadastrados
Programação Web
