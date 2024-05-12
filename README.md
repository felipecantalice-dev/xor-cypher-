# Cifra XOR
É um método de criptografia que utiliza a operação lógica "ou exclusivo" (XOR) para cifrar e decifrar mensagens. É uma técnica simples, mas eficaz, quando usada corretamente.

## Como Funciona
- **Operação XOR**: A operação XOR compara dois bits e retorna `1` se eles forem diferentes e `0` se forem iguais.
- **Conversão para Binário**: Os caracteres da mensagem e da chave são convertidos para sua representação binária.
- **Cifragem**: Cada bit da mensagem é comparado com um bit da chave usando a operação XOR. O resultado é o texto cifrado.
- **Decifragem**: Para decifrar, o texto cifrado é novamente submetido à operação XOR com a mesma chave.

## Exemplo
Texto 1 = "A"
Texto 2 - "B"

Convertemos para o formato binario
Texto 1 = 65
Texto 2 = 66

Depois aplicamos o xor exclusivo
Resultado 3

## Exemplo

Texto 1 = "A"
Texto 2 - "B"

Convertemos para o formato binario
Texto 1 = 01000001 
Texto 2 = 01000010

Depois aplicamos o xor exclusivo
0100 0001
0100 0010
--------
00000011
Resultado 03
