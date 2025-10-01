# MonkeyScript

MonkeyScript é uma linguagem de programação protótipo desenvolvida para estudo de compiladores.  
O projeto implementa um **analisador léxico** e um **analisador sintático** utilizando [ANTLR 4](https://www.antlr.org/), com suporte a variáveis, expressões, condicionais, laços (`for`, `while`, `do/while`) e funções com `return`.

---

## Como Usar no ANTLR Lab

Você pode testar o MonkeyScript diretamente no **ANTLR Lab**, sem instalar nada, acessando o link:

👉 [http://lab.antlr.org/](http://lab.antlr.org/)

### Passos:

1. Copie o conteúdo de `lexer_monkey.txt` e cole na aba **Lexer**.  
2. Copie o conteúdo de `parser_monkey.txt` e cole na aba **Parser**.  
3. Escreva seu código MonkeyScript na aba **Input** (ou utilize o código em `codigo_soma_monkey.txt`).  
4. Clique em **Run** para visualizar os tokens e a árvore sintática.  

---

## Exemplo de Código MonkeyScript

```monkey
func soma(int a, int b) {
    return a + b;
}

main {
    int x = 2;
    int y = 3;
    int r = soma(x, y);
}
