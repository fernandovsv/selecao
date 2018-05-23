# An�lise de problemas em pontos de venda

Um software simples que atrav�s do processamento de dados coletados em pontos de venda gera informa��es estrat�gicas para empresas de trade-marketing.

## Como funciona

Esse projeto busca dados dos pontos de venda atrav�s do endere�o `http://selecao-involves.agilepromoter.com/pesquisas` e transforma os mesmos em informa��es estrat�gicas. Essas informa��es s�o salvas em um banco de dados para posterior an�lise.

**Aten��o: Voc� precisa do Mongo DB instalado e rodando para prosseguir**
```
1. Rode o sistema
``` 
gradlew bootRun
```
3. Abra o navegador em `http://localhost:8080/alertas/pesquisas` para que o dados das lojas sejam processados. 