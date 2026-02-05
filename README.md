Projetos de Gestão de Concessionária
Este repositório apresenta duas etapas de desenvolvimento de um sistema de gestão automotiva em Python.

Versão 1: Sistema de Experiência do Cliente
Esta versão é focada exclusivamente no uso do cliente.

Origem: Este código foi desenvolvido como parte de um trabalho para o curso técnico do SENAI.

Funcionalidade: Permite que o usuário realize o cadastro de perfil com nome, telefone e saldo inicial.

Operações: O cliente pode visualizar o catálogo de veículos disponíveis, simular a compra ou o aluguel de carros, com validações de saldo em tempo real.

Versão 2: Sistema de Gestão Integrada (Vendedor e Cliente)
Esta versão é um projeto pessoal desenvolvido como uma evolução do trabalho original do SENAI.

Evolução: Foram adicionadas ferramentas administrativas para que o modo vendedor também possa ser utilizado no gerenciamento da loja.

Funcionalidade do Vendedor: Permite ao colaborador avaliar veículos de clientes para compra (aplicando margens de lucro), cadastrar novos carros no estoque e consultar o saldo em caixa da empresa.

Robustez: Esta versão introduz tratamentos de erros mais complexos (try-except) para impedir que o programa feche caso o usuário digite dados inválidos.

Lógica de Negócios: Inclui a integração de saldos, onde o dinheiro sai do caixa da empresa e entra no saldo do cliente de forma automática durante as negociações.
