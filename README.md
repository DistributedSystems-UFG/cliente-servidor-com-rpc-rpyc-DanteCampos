# Calculadora distribuída com RPyC

Servidor:
Disponibiliza as operações add(a,b), mult(a,b) e pow(a,b) para adição, multiplicação e potenciação.
Conexões são feitas pela porta 12345.
É utilizada uma flag na instanciação do servidor para não precisar definir o nome das operações com exposed_ no começo.

Cliente:
Chama operações add, mult e pow conectando na porta 12345 do servidor.