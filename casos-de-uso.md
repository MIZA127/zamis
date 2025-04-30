# Diagrama de Casos de Uso – Controle de Estoque de uma Sorveteria

```mermaid
graph TD
  Funcionario((Funcionário))
  Gerente((Gerente))

  Funcionario --> VerificarEstoque
  Funcionario --> RegistrarEntrada
  Funcionario --> RegistrarSaida

  Gerente --> CadastrarProduto
  Gerente --> AtualizarProduto
  Gerente --> RemoverProduto
  Gerente --> VerRelatorioEstoque
  Gerente --> VerificarEstoque

  VerificarEstoque([Verificar Estoque])
  RegistrarEntrada([Registrar Entrada de Produtos])
  RegistrarSaida([Registrar Saída de Produtos])
  CadastrarProduto([Cadastrar Novo Produto])
  AtualizarProduto([Atualizar Produto])
  RemoverProduto([Remover Produto])
  VerRelatorioEstoque([Ver Relatórios de Estoque])
