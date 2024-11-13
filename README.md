📋 Cadastro de Pessoas e Análise de Pesos
Este é um programa em Python que permite ao usuário cadastrar pessoas com seus respectivos nomes e pesos. O programa exibe o total de pessoas cadastradas, o maior e o menor peso registrado, junto com o nome das pessoas correspondentes.


✨ Funcionalidades

👤 Permite o cadastro de várias pessoas com nome e peso.

📈 Identifica e exibe o maior peso entre as pessoas cadastradas.

📉 Identifica e exibe o menor peso entre as pessoas cadastradas.

📊 Exibe o total de pessoas cadastradas.

🏅 Informa quais pessoas possuem o maior e o menor peso.

🧩 Estrutura do Código

Inicialização das Listas e Variáveis:

pessoas: Lista principal que armazena os dados de cada pessoa cadastrada (nome e peso).
dados: Lista temporária usada para coletar nome e peso antes de adicionar a pessoas.
mai e men: Variáveis para armazenar o maior e o menor peso registrados.

Loop de Cadastro:


O programa usa um loop while que continua até o usuário optar por sair (N ou n).
Em cada iteração, o nome e o peso da pessoa são inseridos na lista dados, que é então copiada para a lista pessoas.
Os valores de mai e men são atualizados conforme necessário, para identificar o maior e o menor peso.

Exibição dos Resultados:


Após o cadastro, o programa exibe:

👥 Total de pessoas cadastradas.
🏋️‍♂️ O maior peso registrado, com os nomes das pessoas que possuem esse peso.
🏃 O menor peso registrado, com os nomes das pessoas que possuem esse peso.
📝 Exemplo de Uso

```
Copiar código
Digite o Nome: João
Digite o Peso em Kilos: 85
Deseja Continuar? [S/N]: s
Digite o Nome: Maria
Digite o Peso em Kilos: 95
Deseja Continuar? [S/N]: s
Digite o Nome: Ana
Digite o Peso em Kilos: 70
Deseja Continuar? [S/N]: n

Total de Pessoas Cadastradas: 3
O Maior peso foi de 95Kg. Peso de [Maria]
O Menor peso foi de 70Kg. Peso de [Ana]

```
💻 Requisitos
🐍 Python 3.x

🚀 Como Executar
Copie o código para um editor Python ou IDE de sua preferência.
Execute o código.
Insira o nome e o peso das pessoas conforme solicitado.
Digite N ou n quando desejar encerrar o cadastro e visualizar os resultados.
