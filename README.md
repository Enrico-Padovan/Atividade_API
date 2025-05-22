# Atividade_API
Atividade Realizada em sala, nas aulas do professor Wilson

## Objetivo
Explorar APIs públicas gratuitas, analisar suas funcionalidades, identificar os principais pontos da documentação e testar endpoints para entender na prática como consumir dados via requisições HTTP.

---

## 🔹 API 1: **PokeAPI**

- **Propósito da API:**  
  A PokeAPI fornece dados completos sobre o universo Pokémon, como Pokémon, evoluções, habilidades, tipos, itens, locais e espécies. É muito útil para desenvolvedores que querem criar jogos, sistemas ou estudos relacionados a Pokémon.

- **Formato de resposta:**  
  JSON (estrutura organizada, ideal para consumo em front-ends ou scripts)

- **Chave de API:**  
  Não é necessário utilizar chave. A API é pública e de livre acesso.

- **Exemplo de Endpoint:**  
  [https://pokeapi.co/api/v2/pokemon/pikachu](https://pokeapi.co/api/v2/pokemon/pikachu)

- **Teste prático:**  
  Acessei esse link diretamente no navegador e recebi um JSON com todos os dados do Pikachu, como altura, peso, tipo e ID.

- **Documentação:**  
  [https://pokeapi.co/docs/v2](https://pokeapi.co/docs/v2)

---

## 🔹 API 2: **Agify.io**

- **Propósito da API:**  
  A Agify.io estima a idade média de uma pessoa com base no nome fornecido. Usa uma base de dados estatística global. É interessante para sistemas que precisam fazer previsões ou demonstrações com dados populacionais.

- **Formato de resposta:**  
  JSON

- **Chave de API:**  
  Não precisa de chave para até 1.000 requisições por dia. Para mais requisições, pode-se usar o RapidAPI.

- **Exemplo de Endpoint:**  
  [https://api.agify.io/?name=lucas](https://api.agify.io/?name=lucas)

- **Teste prático:**  
  Acessei o link no navegador e o retorno foi um JSON indicando a idade média de uma pessoa chamada “Lucas”, junto com o número de registros analisados.

- **Documentação:**  
  [https://agify.io/documentation](https://agify.io/documentation)

---

## 🔹 API 3: **Dog CEO API**

- **Propósito da API:**  
  Essa API fornece imagens de cachorros aleatórias e por raça. Serve tanto para uso educativo quanto para projetos divertidos ou informativos.

- **Formato de resposta:**  
  JSON

- **Chave de API:**  
  Não precisa de autenticação. É aberta e gratuita.

- **Exemplo de Endpoint:**  
  [https://dog.ceo/api/breeds/image/random](https://dog.ceo/api/breeds/image/random)

- **Teste prático:**  
  Acessei o link no navegador e a resposta foi um JSON com a URL de uma imagem aleatória de cachorro, que abri normalmente.

- **Documentação:**  
  [https://dog.ceo/dog-api/documentation/](https://dog.ceo/dog-api/documentation/)

---

## ✅ Conclusão

Com essa atividade, eu aprendi a:
- Analisar a estrutura de uma API real.
- Ler e interpretar a documentação.
- Acessar endpoints de forma prática usando o navegador.
- Entender o uso de parâmetros e autenticação.
- Ver como os dados retornam no formato JSON, prontos para serem usados em aplicações.

Essa prática foi essencial para compreender como as APIs funcionam no mundo real e como elas são úteis no desenvolvimento de sistemas modernos.