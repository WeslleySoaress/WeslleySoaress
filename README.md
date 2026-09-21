## Weslley Soares

Estudante de Bacharelado em Tecnologia da Informação na **UFERSA**.

Construo aplicações web e mobile, do banco de dados à tela. O que me interessa
num projeto é a regra de negócio: a parte em que errar custa alguma coisa de
verdade.

---

### Projetos

#### [sujeito-pizza](https://github.com/WeslleySoaress/sujeito-pizza)

Sistema completo para pizzaria, do pedido na mesa ao fechamento da conta. São três
aplicações: o garçom tira o pedido pelo celular, a cozinha vê a comanda chegar em
tempo real, e o caixa recebe o pagamento.

Algumas decisões que valem citar:

- Dinheiro é inteiro em centavos, nunca ponto flutuante — o erro de arredondamento
  aparece no fechamento do caixa
- A exclusividade da mesa é garantida por índice parcial no PostgreSQL, não por
  checagem em código: entre consultar e inserir cabia outro garçom
- 72 testes, com integração contínua rodando a cada push

`TypeScript` · `Node.js` · `Prisma` · `PostgreSQL` · `Socket.IO` · `Next.js` · `React Native`

#### [farol](https://github.com/WeslleySoaress/farol)

Alertas do bairro que funcionam sem internet. Quando a luz cai ou a rua alaga, o
aviso passa de celular em celular por Bluetooth e Wi-Fi Direct, sem operadora nem
servidor. Cada aparelho guarda e repassa o que recebeu.

Em construção.

`React Native` · `Expo`

#### [JogoB4se](https://github.com/WeslleySoaress/JogoB4se)

Jogo da velha contra uma IA com níveis de dificuldade, onde cada jogada exige
acertar uma pergunta de lógica. Projeto de 2024, feito para estudar interface
gráfica e algoritmo de decisão.

`Python` · `Tkinter`

---

<sub>Mais em <a href="https://github.com/WeslleySoaress?tab=repositories">repositórios</a>.</sub>
