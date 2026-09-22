## Weslley Soares

Estudante de Bacharelado em Tecnologia da Informação na **UFERSA**.

Construo aplicações web e mobile, do banco de dados à tela. O que me interessa
num projeto é a regra de negócio: a parte em que errar custa alguma coisa de
verdade.

---

### Projetos

#### [museu-de-interfaces-mortas](https://github.com/WeslleySoaress/museu-de-interfaces-mortas)

Um museu onde as peças funcionam. 21 interfaces mortas recriadas em HTML, de 1970
a 2006 — do cartão perfurado e do telex ao Orkut, à lan house e ao primeiro
YouTube. Você não olha a captura de tela: clica, digita, ouve.

Cada sala tem uma plaquinha que explica não só o que era, mas **por que era
daquele jeito** e **o que sobrou disso hoje**.

- As codificações são reais, não imitação: a fita K7 é Kansas City Standard, o
  cartão perfurado é Hollerith, o telex é ITA2 — e cada uma tem teste que
  codifica e decodifica de volta para provar
- Todo som é sintetizado na hora, sem um único arquivo de áudio
- Nenhuma sala pede senha: uma tela de login recriada tem a forma de uma página
  de phishing, mesmo sendo museu
- A política de segurança da página proíbe qualquer requisição de rede depois de
  carregada — o que o visitante digita morre na aba dele

[Visitar o museu](https://weslleysoaress.github.io/museu-de-interfaces-mortas/)

`TypeScript` · `React` · `Vite` · `Web Audio API`

#### [motriz](https://github.com/WeslleySoaress/motriz)

Marketplace de veículos, do anúncio com foto ao comprador que encontra pela
busca. Quem vende monta o anúncio, escolhe a capa e acompanha as visitas; quem
compra filtra, favorita e fala com o anunciante. No meio dos dois, uma moderação
que aprova ou recusa com motivo.

- Autorização conferida no servidor a cada operação, nunca só na tela
- Upload validado pelo cabeçalho real do arquivo, não pela extensão
- 126 testes de unidade e integração, 52 de ponta a ponta, tudo em integração
  contínua

`TypeScript` · `Next.js` · `React` · `Prisma` · `Tailwind` · `Vitest` · `Playwright`

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
