# Sistema de Controle de Clientes   <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" width="50" height="50">


Este projeto é um sistema de controle de clientes implementado em C#. Ele permite a criação e gerenciamento de clientes que podem ser pessoas físicas ou jurídicas.

## Classes

O sistema é composto por três classes principais:

1. **Clientes**: Esta é a classe base para todos os clientes. Ela contém propriedades comuns a todos os clientes, como nome, endereço e valores relacionados ao pagamento de impostos.

2. **Pessoa_Fisica**: Esta classe herda de Clientes e adiciona propriedades específicas para pessoas físicas, como CPF e RG.

3. **Pessoa_Juridica**: Esta classe também herda de Clientes e adiciona propriedades específicas para pessoas jurídicas, como CNPJ e IE.

## Funcionalidades

O sistema permite a entrada de dados do cliente, como nome, endereço e tipo (pessoa física ou jurídica). Dependendo do tipo de cliente, o sistema solicitará informações adicionais, como CPF e RG para pessoas físicas ou CNPJ e IE para pessoas jurídicas.

O sistema também calcula o valor do imposto a ser pago com base no valor da compra informado. O cálculo do imposto é diferente para pessoas físicas e jurídicas, demonstrando o conceito de polimorfismo.

## Como executar

Para executar o sistema, você precisa ter o .NET Core instalado em seu computador. Depois de instalado, você pode executar o sistema usando o comando `dotnet run` no terminal.
