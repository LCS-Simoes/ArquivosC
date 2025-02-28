# Cadastro de Clientes em C

Este projeto consiste em um sistema de cadastro de clientes desenvolvido em C, utilizando manipulação de arquivos para armazenar os registros. Ele permite realizar operações como inclusão, consulta, alteração e remoção de clientes.

## Funcionalidades

- **Inclusão de clientes**: Adiciona novos clientes ao arquivo de cadastro.
- **Geração de relatório**: Lista todos os clientes cadastrados.
- **Consulta de clientes**: Permite buscar um cliente pelo nome.
- **Alteração de dados**: Modifica os dados de um cliente cadastrado.
- **Remoção de clientes**: Exclui um cliente do cadastro.

## Estrutura do Projeto

O projeto é composto pelos seguintes arquivos e funções:

- **`struct cliente`**: Estrutura que define um cliente com os campos `codigo`, `nome`, `idade`, `cpf`, `endereco` e `telefone`.
- **`incluir()`**: Função para adicionar novos clientes ao arquivo.
- **`relatorio()`**: Exibe a lista de clientes cadastrados.
- **`consultar()`**: Busca um cliente pelo nome.
- **`alterar()`**: Modifica os dados de um cliente existente.
- **`remover()`**: Remove um cliente do cadastro.
- **`main()`**: Gerencia a interação com o usuário, exibindo um menu de opções.

## Como Compilar e Executar

1. Compile o programa usando o compilador GCC:
   ```sh
   gcc cadastro_clientes.c -o cadastro_clientes
   ```
2. Execute o programa:
   ```sh
   ./cadastro_clientes
   ```

## Exemplo de Uso

1. Escolha a opção **1** para cadastrar um novo cliente.
2. Informe os dados solicitados, como código, nome, idade, CPF, endereço e telefone.
3. Escolha a opção **2** para visualizar a lista de clientes.
4. Utilize as opções **3, 4 ou 5** para consultar, alterar ou remover clientes.
5. Para sair, escolha a opção **6**.

## Requisitos

- Compilador C (GCC, Clang, etc.)
- Sistema operacional compatível com C (Windows, Linux, macOS)

## Melhorias Futuras

- Adicionar suporte para armazenamento em banco de dados.
- Implementar interface gráfica para facilitar o uso.
- Melhorar a segurança no armazenamento dos dados.

---
**Autor:** Lucas Simões

