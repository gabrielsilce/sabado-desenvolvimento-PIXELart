# sabado-desenvolvimento-PIXELart

<img width="1267" height="753" alt="image" src="https://github.com/user-attachments/assets/142dc06e-454a-474b-9a4a-ad6061f2e128" />

3 parte  — Inventário de conteúdo

<img width="749" height="339" alt="image" src="https://github.com/user-attachments/assets/1143aa16-eacc-4e00-aa0a-1713ef4bdd12" />

## 3º passo — Inventário de conteúdo

Defina o papel de cada página antes de criá-la.

| Página | Objetivo | Conteúdo necessário |
|---|---|---|
| **Home** | Apresentar o site e direcionar o usuário | Banner com chamada principal, jogos em destaque, novidades, botões para Catálogo e Lançamentos |
| **Catálogo** | Mostrar todos os jogos e facilitar a escolha | Cards (capa, nome, gênero, plataforma, preço, nota), filtros por gênero |
| **Detalhes do jogo** | Convencer o usuário e levar à compra | Imagem grande, descrição, screenshots, requisitos mínimos, preço, botão de compra |
| **Categorias** | Organizar os jogos por gênero | Cards de gêneros (Ação, RPG, FPS, Corrida, Estratégia, Aventura) com links para o catálogo |
| **Lançamentos** | Divulgar os jogos novos e os que vêm aí | Cards de jogos "em breve" e dos que acabaram de chegar |
| **Ranking** | Mostrar os mais bem avaliados | Lista numerada (1º, 2º, 3º...) com capa, nome, gênero, plataforma e nota |
| **Notícias** | Manter o público informado e engajado | Cards de matérias com imagem, título e resumo |
| **Sobre nós** | Apresentar o site e a equipe | Texto da missão e cards com os membros da equipe (nome e função) |
| **Contato** | Receber mensagens e dúvidas | Formulário (nome, e-mail, mensagem) e informações (e-mail, telefone, endereço, horário) |
| **Login / Cadastro** | Permitir o acesso à conta | Formulário de entrada, formulário de cadastro e alternância entre os dois |

## 4º passo — Wireframe

Um esboço simples de cada página, sem preocupação com "ficar bonito". Todas as páginas seguem o mesmo esqueleto: **header, nav, título + apresentação, cards e footer**.

### Home

```text
+--------------------------------------------------------+
|                         HEADER                         |
+--------------------------------------------------------+
|                          NAV                           |
|  Início | Catálogo | Lançamentos | Ranking | Contato   |
+--------------------------------------------------------+
|                 TÍTULO + APRESENTAÇÃO                  |
|               chamada principal + botões               |
+--------------------------------------------------------+
| +--------------+   +--------------+   +--------------+ |
| |    CARD 1    |   |    CARD 2    |   |    CARD 3    | |
| | capa, preço  |   | capa, preço  |   | capa, preço  | |
| +--------------+   +--------------+   +--------------+ |
+--------------------------------------------------------+
|                       NOVIDADES                        |
+--------------------------------------------------------+
|                         FOOTER                         |
+--------------------------------------------------------+
```

### Catálogo (página interna)

```text
+--------------------------------------------------------+
|                         HEADER                         |
+--------------------------------------------------------+
|                          NAV                           |
|  Início | Catálogo | Lançamentos | Ranking | Contato   |
+--------------------------------------------------------+
|                    TÍTULO + FILTROS                    |
|           Todos | Ação | RPG | FPS | Corrida           |
+--------------------------------------------------------+
| +--------------+   +--------------+   +--------------+ |
| |    CARD 1    |   |    CARD 2    |   |    CARD 3    | |
| | capa, preço  |   | capa, preço  |   | capa, preço  | |
| +--------------+   +--------------+   +--------------+ |
| +--------------+   +--------------+   +--------------+ |
| |    CARD 4    |   |    CARD 5    |   |    CARD 6    | |
| | capa, preço  |   | capa, preço  |   | capa, preço  | |
| +--------------+   +--------------+   +--------------+ |
+--------------------------------------------------------+
|                         FOOTER                         |
+--------------------------------------------------------+
```

### Contato

```text
+--------------------------------------------------------+
|                         HEADER                         |
+--------------------------------------------------------+
|                          NAV                           |
|  Início | Catálogo | Lançamentos | Ranking | Contato   |
+--------------------------------------------------------+
|                 TÍTULO + APRESENTAÇÃO                  |
|                    Fale com a gente                    |
+--------------------------------------------------------+
| +--------------------+  +----------------------------+ |
| |    INFORMAÇÕES     |  |         FORMULÁRIO         | |
| |                    |  | [Nome                    ] | |
| |       E-mail       |  | [E-mail                  ] | |
| |      Telefone      |  | [Mensagem                ] | |
| |      Endereço      |  | [                        ] | |
| |      Horário       |  | [         ENVIAR         ] | |
| +--------------------+  +----------------------------+ |
+--------------------------------------------------------+
|                         FOOTER                         |
+--------------------------------------------------------+
```

### Reaproveitamento dos padrões

| Página | Padrão reutilizado |
|---|---|
| Categorias, Lançamentos, Notícias | Catálogo (título + cards) |
| Ranking | Catálogo, com lista numerada no lugar dos cards |
| Sobre nós | Home (título + apresentação + cards da equipe) |
| Detalhes do jogo | Duas colunas: imagem e screenshots à esquerda, descrição e compra à direita |
| Login / Cadastro | Formulário do Contato, em uma coluna |

## 4º passo — Wireframe

Um esboço simples de cada página, sem preocupação com "ficar bonito". Todas as páginas seguem o mesmo esqueleto: **header, nav, título + apresentação, cards e footer**.

### Home

```text
+--------------------------------------------------------+
|                         HEADER                         |
+--------------------------------------------------------+
|                          NAV                           |
|  Início | Catálogo | Lançamentos | Ranking | Contato   |
+--------------------------------------------------------+
|                 TÍTULO + APRESENTAÇÃO                  |
|               chamada principal + botões               |
+--------------------------------------------------------+
| +--------------+   +--------------+   +--------------+ |
| |    CARD 1    |   |    CARD 2    |   |    CARD 3    | |
| | capa, preço  |   | capa, preço  |   | capa, preço  | |
| +--------------+   +--------------+   +--------------+ |
+--------------------------------------------------------+
|                       NOVIDADES                        |
+--------------------------------------------------------+
|                         FOOTER                         |
+--------------------------------------------------------+
```

### Catálogo (página interna)

```text
+--------------------------------------------------------+
|                         HEADER                         |
+--------------------------------------------------------+
|                          NAV                           |
|  Início | Catálogo | Lançamentos | Ranking | Contato   |
+--------------------------------------------------------+
|                    TÍTULO + FILTROS                    |
|           Todos | Ação | RPG | FPS | Corrida           |
+--------------------------------------------------------+
| +--------------+   +--------------+   +--------------+ |
| |    CARD 1    |   |    CARD 2    |   |    CARD 3    | |
| | capa, preço  |   | capa, preço  |   | capa, preço  | |
| +--------------+   +--------------+   +--------------+ |
| +--------------+   +--------------+   +--------------+ |
| |    CARD 4    |   |    CARD 5    |   |    CARD 6    | |
| | capa, preço  |   | capa, preço  |   | capa, preço  | |
| +--------------+   +--------------+   +--------------+ |
+--------------------------------------------------------+
|                         FOOTER                         |
+--------------------------------------------------------+
```

### Contato

```text
+--------------------------------------------------------+
|                         HEADER                         |
+--------------------------------------------------------+
|                          NAV                           |
|  Início | Catálogo | Lançamentos | Ranking | Contato   |
+--------------------------------------------------------+
|                 TÍTULO + APRESENTAÇÃO                  |
|                    Fale com a gente                    |
+--------------------------------------------------------+
| +--------------------+  +----------------------------+ |
| |    INFORMAÇÕES     |  |         FORMULÁRIO         | |
| |                    |  | [Nome                    ] | |
| |       E-mail       |  | [E-mail                  ] | |
| |      Telefone      |  | [Mensagem                ] | |
| |      Endereço      |  | [                        ] | |
| |      Horário       |  | [         ENVIAR         ] | |
| +--------------------+  +----------------------------+ |
+--------------------------------------------------------+
|                         FOOTER                         |
+--------------------------------------------------------+
```

### Reaproveitamento dos padrões

| Página | Padrão reutilizado |
|---|---|
| Categorias, Lançamentos, Notícias | Catálogo (título + cards) |
| Ranking | Catálogo, com lista numerada no lugar dos cards |
| Sobre nós | Home (título + apresentação + cards da equipe) |
| Detalhes do jogo | Duas colunas: imagem e screenshots à esquerda, descrição e compra à direita |
| Login / Cadastro | Formulário do Contato, em uma coluna |

       
