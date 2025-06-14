# O Insight Quinze

<p align="center">
  <img src="imagens/unnamed.png" alt="Capa do Podcast O Insight Quinze" width="350"/>
</p>

**Subtítulo:** Dados, carreira e as novas diretrizes do mercado

---

## Sobre o Nome do Podcast

> Uma homenagem profunda e nerd à obra-prima "O Quinze", de Rachel de Queiroz. O livro trata de uma seca histórica (1915) e da capacidade de superação. Ao trocar "O Quinze" por "O Insight Quinze", você posiciona seu podcast como uma fonte de clareza ("insight") que ajuda as pessoas a navegarem pelas "secas" e desafios do mercado de trabalho. O subtítulo "novas profecias" é uma jogada visionária, sugerindo que a análise de dados é a nova forma de prever tendências e garantir o futuro.

---

## Estrutura do Repositório

```
Projeto Podcast/
├── audio/        # Áudios do episódio, aberturas, trilhas e narração
├── imagens/      # Capas e imagens do podcast
├── roteiros/     # Roteiros e documentos em PDF
├── video/        # Episódios em vídeo
```

---

## Passo a Passo da Criação

### 1. Definição da Ideia e Nome do Podcast
Utilizei o Gemini para gerar sugestões de nomes criativos, com base no prompt abaixo:

```text
Você é um roteirista do flow podcast, e vamos criar um podcast de tecnologia, focado em data Analytics que estão começando a carreira ou queira conhecer e eu gostaria de uma ajuda sua para criar 5 sugestões de nomes criativos para um podcast focado em data Analytics feito por um nerds, analista de dados e cearense e que tenha algum trocadilho nerd no nome.

O podcast vai falar sobre dicas e novidades sobre o mundo da data Analytics e o que está acontecendo no mercado, além de cases de sucesso de pessoas de sucesso no ramo e empresas que mudaram a forma de pensar em se tornar uma empresa data driver.

{REGRAS}
O nome deve ser enxuto, um nome e um subtítulo
O nome tenha algum trocadilho nerd com nomes de grandes escritórios e cientista nordestinos
O nome deve conter alguma palavra forte que remeta a data Analytics
{REGRAS NEGATIVAS}
Não quero que o título contenha palavras em complexas
```
As sugestões geradas foram analisadas e o nome "O Insight Quinze" foi escolhido por sua relevância e impacto.

### 2. Criação da Capa/Imagem
Utilizei o Gemini para gerar a arte da capa do podcast, com o seguinte prompt:

```text
Agora vamos gerar uma imagem para esse podcast. Siga essa características substituindo os principais campos e sempre remeter ao Ceará, em formato de cordel: O Personagem: Um jovem analista cearense, cabelo com corte social de característica cacheado bem baixo e sorridente.
A Ação: Ele estará com um microfone, no papel de podcaster, o mestre de cerimônias do "O Insight Quinze".
O Cenário: Um fundo que mistura a tradição e a modernidade: elementos icônicos do sertão, como o cacto e o sol forte, se fundem a padrões digitais, como códigos binários e códigos e gráficos, representando o universo de Data Analytics.
A Estética: Tudo no estilo inconfundível da xilogravura de cordel, com traços fortes e o clássico preto e branco.
```
O arquivo gerado foi salvo como `imagens/unnamed.png`.

### 3. Roteiro do Episódio Piloto
O roteiro do episódio foi criado com o Gemini, usando o prompt:

```text
Episódio de Podcast
Você é um roteirista do flow podcast, e vamos criar um roteiro de um podcast de tecnologia, focado em data Analytics, com o público alvo de iniciantes em na profissão ou queiram conhecer esse mundo. o nome do podcast é "O Insight Quinze - Dados, carreira e as novas diretrizes do mercado". 
o formato do roteiro deve ser [INTRODUÇÃO] [CURIOSIDADE 1] [CURIOSIDADE 2] [FINALIZAÇÃO]
{REGRAS}
no bloco [INTRODUÇÃO] substitua por uma introdução iguais as introduções dos vídeos do canal 'ei nerd', como se fossem escritos pelo Peter Jordan
no bloco [CURIOSIDADE 1] substitua por uma curiosidade de data Analytics
no bloco [CURIOSIDADE 2] sobre uma ferramenta para data Analytics
no bloco [FINALIZAÇÃO] substitua por uma despedida cool com o final 'Eu sou Henrique e esse foi o CodeQuest dessa semana'
use termos de fácil explicação
O podcast vai ser apresentado somente por uma pessoa, chamada Henrique
O podcast deve ser curto
{REGRAS NEGATIVAS}
Não use muitos termos técnicos
```
O roteiro final está disponível em `roteiros/`.

### 4. Narração e Edição
Utilizei o ElevenLabs para gerar a narração do roteiro.
Editei todo o material de áudio e vídeo no CapCut, incluindo trilhas, cortes e montagem final.

### 5. Organização dos Arquivos
Todos os arquivos foram organizados nas pastas temáticas:
- Áudios em `/audio`
- Imagens em `/imagens`
- Roteiros em `/roteiros`
- Vídeos em `/video`

---

## Como Ouvir/Assistir
- Os arquivos de áudio estão na pasta `/audio`.
- O vídeo do episódio está em `/video`.
- O roteiro em PDF está em `/roteiros`.
- A capa e imagens estão em `/imagens`.

---

## Ferramentas Utilizadas
- **Gemini**: Geração do roteiro do episódio e criação da capa/imagem do podcast.
- **ElevenLabs**: Geração da voz e narração do roteiro.
- **CapCut**: Edição completa do episódio em áudio e vídeo.

---

## Observações
Este repositório foi criado como parte de uma atividade avaliativa, demonstrando o uso de IA generativa e ferramentas de edição para produção de conteúdo multimídia.

---

Sinta-se à vontade para explorar os arquivos e utilizar como referência para projetos semelhantes!