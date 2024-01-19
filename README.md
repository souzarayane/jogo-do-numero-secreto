# Jogo do Número Secreto em JavaScript

Este é um simples jogo do número secreto desenvolvido em JavaScript para ser executado em um ambiente web. O jogo tem como objetivo adivinhar um número aleatório gerado pelo computador dentro de um intervalo específico.

## Funcionalidades Principais

1. **Geração do Número Secreto:**
   - A função `gerarNumeroAleatorio` é responsável por gerar um número aleatório dentro de um intervalo predefinido e garantir que o mesmo não seja repetido nas últimas 3 jogadas.

2. **Verificação do Chute do Usuário:**
   - A função `verificarChute` compara o número digitado pelo usuário com o número secreto, fornecendo dicas sobre se o número secreto é maior ou menor. Ao acertar o número, uma mensagem de vitória é exibida.

3. **Exibição de Mensagens na Tela:**
   - A função `exibirTextoNaTela` é responsável por exibir mensagens na tela do usuário, utilizando a biblioteca `responsiveVoice` para fornecer uma experiência auditiva.

4. **Reinício do Jogo:**
   - A função `reiniciarJogo` reinicia o jogo, gerando um novo número secreto, limpando o campo de entrada e resetando as tentativas.

## Instruções de Uso

1. Abra o arquivo HTML em um navegador web.
2. Digite um número no campo de entrada.
3. Clique no botão "Verificar".
4. Receba dicas sobre se o número secreto é maior ou menor.
5. Repita até acertar o número ou reinicie o jogo.

## Requisitos

- Um navegador web atualizado.
- Conexão com a internet para carregar a biblioteca `responsiveVoice`.

## Créditos

- Este jogo utiliza a biblioteca `responsiveVoice` para a funcionalidade de texto para voz. Para mais informações, consulte [responsivevoice.org](https://responsivevoice.org/).

**Divirta-se jogando o Jogo do Número Secreto!**
