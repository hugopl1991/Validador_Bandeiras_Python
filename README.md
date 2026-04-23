📇 Validador de Bandeiras de Cartão de Crédito (Python)

Este projeto contém uma função em Python para identificar a bandeira (bandeira/brand) de um cartão de crédito a partir do número do cartão, baseada nos prefixos usados pelas principais bandeiras.

🧠 Sobre

O script foi gerado com o auxílio do GitHub Copilot e implementa uma função simples que verifica o prefixo do número do cartão para dizer se ele é um Visa, MasterCard, American Express, Discover ou outra.

📦 Conteúdo
copilote.py – Script com a função validar_bandeira que identifica a bandeira do cartão.
README.md – Este arquivo com explicação do projeto.
🛠 Requisitos
Python 3.x
🚀 Como usar
Clone este repositório:
git clone https://github.com/hugoplima/Validador_Bandeiras_Python.git
Entre na pasta do projeto:
cd Validador_Bandeiras_Python
Abra o arquivo copilote.py ou importe a função validar_bandeira no seu script Python.
🧩 Função de exemplo

O arquivo copilote.py contém uma função validar_bandeira que funciona assim:

from copilote import validar_bandeira

cartao_exemplo = "4111111111111111"
print(validar_bandeira(cartao_exemplo))  # Deve imprimir "Visa"

Ela verifica se o número do cartão começa com prefixos conhecidos para cada bandeira (como 4 para Visa, 34/37 para American Express etc.) e retorna a bandeira correspondente.

📌 Bandeiras suportadas

Atualmente o validador reconhece estas bandeiras:

Visa
MasterCard
American Express
Discover

Se o número não corresponder a nenhum prefixo conhecido, retorna “Bandeira não identificada”.
