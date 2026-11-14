
<img width="1267" height="753" alt="image" src="https://github.com/user-attachments/assets/2671be23-3aaf-4ca3-befd-abc2350b5946" />

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

# 5. Inventário de Conteúdo

| Página | Objetivo | Conteúdo necessário |
|---|---|---|
| Início (`index.html`) | Apresentar a plataforma e destacar seus principais conteúdos. | Apresentação da PixelVault, catálogos, jogos, promoções, avaliações, notícias relacionadas e produtos em alta. |
| Catálogo (`catalogo.html`) | Apresentar os jogos disponíveis na plataforma. | Imagem dos jogos, preços, promoções, gênero dos jogos e barra de pesquisa. |
| Categorias (`categorias.html`) | Organizar os jogos conforme seus respectivos gêneros. | Catálogos divididos por gêneros, capa dos jogos, barra de pesquisa e descrição dos jogos. |
| Contato (`contato.html`) | Disponibilizar canais de comunicação entre usuários e a plataforma. | Opção de cadastro de e-mail/número de WhatsApp, acesso ao e-mail/WhatsApp da PixelVault. |
| Detalhes do jogo (`jogo.html`) | Apresentar informações específicas sobre um jogo selecionado. | Nome do jogo, capa do jogo, gênero, breve descrição da história, avaliações, preço, promoções/descontos, opção de baixar uma demo e botão de compra. |
| Lançamentos (`lancamentos.html`) | Divulgar jogos recém-lançados e futuros lançamentos. | Uma aba específica que mostre todos os jogos que foram lançados dentro de um período de um mês e jogos que irão ser lançados em breve. |
| Login (`login.html`) | Permitir que os usuários acessem ou criem uma conta. | Formulário de cadastro que peça o e-mail, senha, nome do jogador e um aceite de termos e condições. |
| Notícias (`noticias.html`) | Informar os usuários sobre novidades do mercado de games. | Lançamentos de jogos, avisos sobre inscrições de campeonatos, atualizações de campeões referente a certos campeonatos/competições e atualizações nos softwares dos games. |
| Orçamento (`orcamento.html`) | Registrar a pesquisa comparativa de domínio e hospedagem e receber pedidos de orçamento. | Tabelas de domínio e hospedagem, estimativa de custo, recomendação e formulário de orçamento. |
| Ranking (`ranking.html`) | Exibir os jogos mais bem avaliados pela comunidade. | Lista de todos os jogos, do mais avaliado ao menos avaliado, comentários dos gamers referente aos jogos, capa dos jogos, breve descrição e opção de compra. |
| Sobre nós (`sobre.html`) | Apresentar a identidade e os objetivos da PixelVault. | Missão, visão e valores da PixelVault, história e equipe. |

# 6. Wireframe de Baixa Fidelidade

## 6.1 Wireframe da página inicial (Home)

**Objetivo:** apresentar a plataforma, destacar jogos disponíveis e direcionar os visitantes para as principais funcionalidades.

```text
+--------------------------------------------------+
|                  PIXEL VAULT                     |
|                                                  |
| Início | Catálogo | Categorias | Lançamentos     |
| Ranking | Notícias | Sobre | Contato | Entrar    |
+--------------------------------------------------+
|                                                  |
|                 JOGUE SEM LIMITES                |
|                                                  |
|    Milhares de jogos, ofertas toda semana e      |
|             os maiores lançamentos.              |
|                                                  |
|       [ EXPLORAR CATÁLOGO ] [ LANÇAMENTOS ]      |
|                                                  |
+--------------------------------------------------+
|                  JOGOS EM DESTAQUE               |
|                                                  |
|   +-------------+ +-------------+                |
|   |  Dragon     | |  Skyward    |                |
|   |  Ashes      | |  Isles      |                |
|   |  Imagem     | |  Imagem     |                |
|   |  Avaliação  | |  Avaliação  |                |
|   |  Preço      | |  Preço      |                |
|   +-------------+ +-------------+                |
|                                                  |
|   +-------------+ +-------------+                |
|   | Shadow Blade| | Neon Drift  |                |
|   | Imagem      | | Imagem      |                |
|   | Avaliação   | | Avaliação   |                |
|   | Preço       | | Preço       |                |
|   +-------------+ +-------------+                |
|                                                  |
+--------------------------------------------------+
|                     NOVIDADES                    |
|                                                  |
|  [Notícia 1]    [Notícia 2]    [Notícia 3]       |
|                                                  |
+--------------------------------------------------+
|                     RODAPÉ                       |
|  Navegação | Institucional | Redes sociais       |
+--------------------------------------------------+
```

**Descrição:** a página inicial possui um cabeçalho com a identificação da PixelVault e um menu de navegação. Na área principal, apresenta uma chamada de destaque com botões de acesso ao catálogo e aos lançamentos. Em seguida, são exibidos cards de jogos com imagens, avaliações e preços, além de uma seção de notícias. O rodapé disponibiliza links institucionais e redes sociais.

## 6.2 Wireframe de página interna — Catálogo

**Objetivo:** organizar e apresentar os jogos disponíveis, permitindo que os visitantes visualizem as opções existentes.

```text
+--------------------------------------------------+
|                  PIXEL VAULT                     |
|                                                  |
| Início | Catálogo | Categorias | Lançamentos     |
| Ranking | Notícias | Sobre | Contato | Entrar    |
+--------------------------------------------------+
|                                                  |
|                  CATÁLOGO DE JOGOS               |
|                                                  |
|       [ Todos ] [ Ação ] [ RPG ] [ FPS ]         |
|                  [ Corrida ]                     |
|                                                  |
+--------------------------------------------------+
|                                                  |
|   +----------------+  +----------------+         |
|   |   NEON DRIFT   |  |  DRAGON ASHES  |         |
|   |                |  |                |         |
|   |     IMAGEM     |  |     IMAGEM     |         |
|   |                |  |                |         |
|   |  Corrida       |  |  RPG           |         |
|   |  Avaliação     |  |  Avaliação     |         |
|   |  Preço         |  |  Preço         |         |
|   +----------------+  +----------------+         |
|                                                  |
|   +----------------+  +----------------+         |
|   |  LAST SIGNAL   |  |  SHADOW BLADE  |         |
|   |                |  |                |         |
|   |     IMAGEM     |  |     IMAGEM     |         |
|   |                |  |                |         |
|   |  FPS           |  |  Ação          |         |
|   |  Avaliação     |  |  Avaliação     |         |
|   |  Preço         |  |  Preço         |         |
|   +----------------+  +----------------+         |
|                                                  |
+--------------------------------------------------+
|                     RODAPÉ                       |
|  Navegação | Institucional | Redes sociais       |
+--------------------------------------------------+
```

**Descrição:** a página de catálogo apresenta os jogos em cards organizados em uma grade. Na parte superior, são disponibilizados filtros por gênero, como ação, RPG, FPS e corrida. Cada card apresenta informações importantes para auxiliar o usuário na escolha do jogo.

## 6.3 Wireframe da página de contato

**Objetivo:** disponibilizar informações de atendimento e permitir que os usuários enviem mensagens à equipe da PixelVault.

```text
+--------------------------------------------------+
|                  PIXEL VAULT                     |
|                                                  |
| Início | Catálogo | Categorias | Lançamentos     |
| Ranking | Notícias | Sobre | Contato | Entrar    |
+--------------------------------------------------+
|                                                  |
|                      CONTATO                     |
|                  Fale com a gente                |
|                                                  |
|  E-mail: contato@pixelvault.com                  |
|  Telefone: (11) 4000-0000                        |
|  Localização: São Paulo, SP                      |
|  Atendimento: Segunda a sexta, 9h às 18h         |
|                                                  |
+--------------------------------------------------+
|                                                  |
|                 ENVIE SUA MENSAGEM               |
|                                                  |
|  Nome:                                           |
|  [________________________________________]      |
|                                                  |
|  E-mail:                                         |
|  [________________________________________]      |
|                                                  |
|  Mensagem:                                       |
|  [________________________________________]      |
|  [________________________________________]      |
|  [________________________________________]      |
|                                                  |
|             [ ENVIAR MENSAGEM ]                  |
|                                                  |
+--------------------------------------------------+
|                     RODAPÉ                       |
|  Navegação | Institucional | Redes sociais       |
+--------------------------------------------------+
```

**Descrição:** a página de contato apresenta os principais canais de atendimento da plataforma, incluindo e-mail, telefone, localização e horário de funcionamento. Também possui um formulário com campos para nome, e-mail e mensagem, permitindo que os visitantes encaminhem dúvidas, sugestões ou solicitações.

## 6.4 Considerações sobre os wireframes

Os wireframes estabelecem uma estrutura visual para as principais páginas do PixelVault, facilitando a organização dos elementos e o desenvolvimento da interface. A utilização de um padrão compartilhado de cabeçalho, navegação e rodapé contribui para a consistência visual e para uma experiência de utilização mais intuitiva.

As estruturas apresentadas servem como referência para a organização dos elementos HTML e sua posterior estilização com CSS.
