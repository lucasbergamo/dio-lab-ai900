# Conceitos Fundamentais de IA

## Objetivos

- Explicar o que é IA e compreender a importância da IA responsável.
- Compreender os diferentes tipos de modelos de aprendizado de máquina.
- Identificar os serviços de IA disponíveis no Azure e para que são utilizados. 


## Cargas de trabalho comuns de IA 


### O que é a inteligência artificial?

- Prever resultados e reconhecer padrões com base em dados históricos.
- Extrair informações de fontes para obter conhecimento.
- Compreender a linguagem e participar de conversas.
- Reconhecer eventos anormais e tomar decisões.
- Interpretar informações visuais.

### Machine Learning

- Modelos preditivos baseados em dados e estatísticas

### Visão Computacional

- Capacidade da IA para interpretar o mundo visualmente por meio de câmeras, vídeos e imagens.

### Processamento de linguagem natural

- Capacidades da IA para que um computador interprete a linguagem escrita ou falada e responda adequadamente.

### Inteligência de Documentos

- Capacidades de IA que lidam com o gerenciamento, processamento e uso de grandes volumes de dados encontrados em formulários e documentos.

### Mineração de conhecimento

- Capacidades da IA para extrair informações de grandes volumes de dados muitas vezes não estruturados para criar um armazenamento de conhecimento pesquisável.
- Ingerir > Enriquecer > Explorar

### IA generativa

- Recursos de IA que criam conteúdo original em vários formatos, incluindo linguagem natural, imagem, código e muito mais.

### Princípios de IA responsável: Imparcialidade

- __Desafio ou risco__: O preconceito pode afetar os resultados.

- _Exemplo_: Um modelo de aprovação de empréstimos que discrimina por gênero devido ao preconceito nos dados com os quais foi treinado.

### Confiabilidade e Segurança

- __Desafio ou risco__: Erros podem causar danos.
- _Exemplo_: Um veículo autônome sofre uma falha no sistema e causa uma colisão.

### Privacidade e Segurança

- __Desafio ou Risco__: Dados privados podem ser expostos.
- __Exemplo__: Um bot de diagnóstico médico é treinado usando dados confidenciais de pacientes, que são armazenados de forma insegura.

### Inclusão e transparência

- __Desafio ou Risco__: As soluções podem não funcionar para todos.
- __Exemplo__: Um aplicativo preditivo não fornece saída de áudio para usuários com deficiência visual.

- __Desafio ou Risco__: Os usuários devem confiar em um sistema complexo.
- __Exemplo__: Uma ferramenta financeira baseada em IA faz recomendações de investimento, em que se baseiam?

### Responsabilidade

- __Desafio ou Risco__: Quem é responsável pelas decisões baseadas na IA?
- __Exemplo__: Uma pessoa inocente é condenada por um crime com base em provas de reconhecimento facial, quem é o responsável?

## Fundamentos do Aprendizado de máquina


### O que é aprendizado de máquina?

1. __Dados de Treinamento__ (observações anteriores)
2. __Algoritmo__ (Generaliza a relação entre x e y como uma função)
3. __Modelo__ (encapsula a função)
4. __Inferência de dados__ (recursos não rotulados), __Predição__ (rótulo inteiro)

![alt text](image.png)

### Treinamento e avaliação de modelo

![alt text](image-1.png)

### Aprendizado Profundo

* Rede neural artificial
* Neurônios disparam em resposta a estímulos eletroquímicos
* Quando disparado, o sinal é passado para neurônios conectados

- Cada neurônio é uma função que opera com um valor de entrada (x) e um peso (w)
- A função é envolvida em uma função de ativação que determina se a saída deve ser transmitida

- Azure machine Learning é uma plataforma baseada em nuvem para aprendizado de máquina.

- Azure machine Learning Studio é uma interface de usuário para acessar recursos do azure machine learning

- Os modelos de aprendizagem automática treinados com Azure Machine Learning podem ser publicados como serviços.



## Noções básicas do azure

A plataforma de nuvem azure oferece escalabilidade e segurança

- Armazenamento de dados
- Computação
- Serviços

### Serviços de IA no microsoft Azure

- __Aprendizado de máquina azure__ : Uma plataforma para treinar, implantar e gerenciar modelos de aprendizado de máquina
- __Serviços de IA do azure__ : Um conjunto de serviços que abrange visão, fala, linguagem, decisão e IA generativa
- __Pesquisa Cognitiva do Azure__ : Extração, enriquecimento e indexação de dados para pesquisa inteligente e mineração de conhecimento.


Recursos de aplicação de IA numa subscrição do azure:

- Recursos autônomos para serviços específicos
- Recurso geral de serviços de IA no azure para vários serviços

Consumidos por aplicativos via:

- Um endpoint REST
- Uma chave de autenticação ou token de autorização


## Conceitos de visão computacional


Objetivos:

- Compreender as capacidades do azure ai vision
- identificar os diferentes serviços incluidos no azure ai vision
- descrever o serviço de detecção facial

### imagens e processamento de imagens

- uma imagem é uma matiz de valores de pixels
- Filtros são aplicados para alterar as imagens

![alt text](image-2.png)

- Uma foto preta e branca de uma cidade
- Uma foto preta e branca de uma cidade grande
- Um grande edifício em uma cidade 

![alt text](image-3.png)


### Redes Neurais convolucionais

1. Imagens rotuladas são usadas para treinar o modelo (definir o modelo)
2. Camadas de filtro extraem mapas de recursos de cada imagem
3. Os mapas de recursos são reunidos
4. Os valores dos recursos são alimentados em uma rede neural totalmente conectada.
5. A camada de saída produz um valor de probabilidade para cada rótulo de classe possível

![alt text](image-4.png)


### Modelos Multimodais (AI vision)

Interpretação do que está acontecendo em um vídeo

- O modelo encapsula relações semânticas entre recursos extraídos das imagens e texto extraído de legendas relacionadas.
- Um modelo multimodal pode ser usado como modelo base para modelos adaptativos mais expecializados.

![alt text](image-5.png)


### Serviços de visão computacional no Azure

__Visão__

- Análise de imagem
- Marcação de imagens, legendas, personalização de modelos e muito mais.
- Reconhecimento Óptico de Caracteres (OCR)
- Análise espacial


__Face__

- Detecção de rosto
- Reconhecimento facial


## Conceitos de processamento de linguagem natural

- Reconheça quando o processamento de linguagem natural e a IA conversacional podem ser usados.
- identifique os serviços de IA do azure que incluem processamento de linguagem natural.
- Use a análise de texto para você mesmo.


### O que é processamento de linguagem natural?


![alt text](image-6.png)


### Processamento de Linguagem natural e IA conversacional no azure - Análise de sentimentos e respostas a perguntas

- NER (Reconhecimento de Entidade Nomeada)

![alt text](image-7.png)

- Detecção de PII e PHI

![alt text](image-8.png)

- Detecção de idioma

![alt text](image-9.png)

- Análise de sentimentos

![alt text](image-10.png)

- Respostas a perguntas

![alt text](image-11.png)

### Processamento de Linguagem natural e IA conversacional no azure - Fala

- Texto para fala
- Conversão de fala para texto
- Tradução de fala

### Processamento de Linguagem natural e IA conversacional no azure - Tradução

- Tradução do texto em tempo real para vários idiomas
- Tradução de documentos
- Tradução personalizada


## Inteligência de documentos de IA do Azure

- Entender o que o Azure IA document intelligence faz e por que as organizações o utilizam.
- Descrever a mineração de conhecimento e os problemas que ela resolve


* O problema:

![alt text](image-12.png)



- __Análise de documentos__:

- Retorna representações de dados estruturados
- Regiões de interesse e relacionamentos
- Configurar opções de análise para análise gratuita cobrada


* __Modelos pré-construidos__:

- Faturas
- Recibos
- Identificador
- Reconhece e extrai pares de valores-chave

* __Modelos Personalizados__:

- Treine modelos com pelo menos cinco dados de amostra.
- Identifique campos de interesse para sua organização.


### Analisando formulários com o serviço Document Intelligence

- Extraia informações de formulários digitalizados em formato de imagem ou PDF.
- Use os modelos pré-treinados para tipos de documentos comuns, como faturas, recibos, IDs, etc.
- Treine um modelo personalizado usando seus próprios formulários



Estúdio de inteligência de documentos

- Usando uma abordagem sem código, você pode explorar a funcionalidade usando exemplos e seus próprios documentos.

1. Primeiro - crie um recurso
2. Recurso de inteligência de documentos
3. Recurso de serviços de IA
4. Em seguida, habilite o recurso no document intelligence studio
5. Página de primeiros passos: selecione um modelo para experimentar


## Conceitos Básicos de IA Generativa




- __IA__: Imita o comportamento humano, usando aprendizado de máquina para interagir com o ambiente e executar tarefas sem instruções explícitas, sobre o que gerar.

* __IA Generativa__: Cria conteúdo original, como IA gerativa que foi incorporada a aplicativos de chat. Os aplicativos de IA gerativa usam entrada em linguagem natural e retornam respostas apropriadas em uma variedade de formatos:

1. Geração de linguagem natural
2. Geração de imagem
3. Geração de código

#### Copilotos

- Os copilotos são frequentemente integrados a outros aplicativos e fornecem uma maneira para os usuários obterem ajuda com tarefas comuns a partir de um modelo generativo de IA.
- Os desenvolvedores podem criar copilotos que enviam prompts para grandes modelos de linguagem e geram conteúdo para uso em aplicativos.
- Os usuários empresariais podem usar copilotos para aumentar sua produtividade e criatividade com conteúdo gerado por IA.
- Navegador Microsoft Edge, Microsoft Bing, GitHub Copilot = são exemplos de copilot


#### Engenharia de Prompts

O termo engenharia de prompt descreve o processo de aprimoramento de prompts.

- Os desenvolvedores que projetam aplicativos e consumidores que usam aplicativos podem aprimorar a qualidade das respostas da IA gerativa usando linguagem direta, mensagens do sistema, exemplos e/ou dados de fundamentação.


![alt text](image-15.png)


![alt text](image-16.png)


![alt text](image-17.png)


![alt text](image-18.png)


### Modelos de linguagem grandes LLM

Os aplicativos de IA gerativa são alimentados por LLMs, que são um tipo especializado de modelo de machine learning que você pode usar para executar tarefas de PLN  (processamento de linguagem natural), incluindo:

- Determinar sentimento ou classificar de outra forma o texto em idioma natural
- Resumir um texto
- Comparar várias fontes de texto quanto à similaridade semântica
- Geração de nova linguagem natural


####  Transformador

- A arquitetura do modelo do transformador consiste em dois componentes principais, ou blocos.

1. Um bloco codificador que cria representações semânticas do vocabulário de treinamento.
2. Um bloco decodificador que gera novas sequências de linguagem.

- O texto é tokenizado para que cada palavra ou frase seja representada por um token numérico exclusivo.
- Inserções (valores de vetor com várias dimensões) são atribuídas aos tokens

* As camadas de atenção examinam cada token por vez e determinam valores incorporados que refletem os relacionamentos semânticos entre os tokens.
* No decodificador, essas relações são usadas para prever a sequência mais provável de tokens.


![alt text](image-13.png)


#### Tokenização

1. A primeira etapa no treinamento de um modelo de transformador é decompor o texto de treinamento em tokens.


Frase de exemplo: Eu ouvi um cachorro latir alto para um gato.

"Eu" = 1
"ouvi" = 2
"um" = 3
"cachorro" = 4
"latir" = 5
"alto" = 6
"para" = 7
"gato" = 8

- A frase agora é representada com os tokens: [123456738].
- Observe que "um" é tokenizado como 3 apenas uma vez.
- Da mesma forma, a frase "Eu ouvi um gato" poderia ser representada com as fichas [1238].


#### Inserções

- As relaçõs entre tokens são capturadas como vetores, conhecidas como inserções.


![alt text](image-14.png)


#### Atenção

- Capture a força das relações entre tokens usando a técnica de atenção.

Exemplo:

1. Meta: prever o token após "cachorro".
2. Represente "Ouvi um cachorro" como vetores.
3. Atribua mais peso a "ouvi" e "cachorro".
4. Vários tokens possíveis podem vir depois de cachorro
5. O token mais provável é adicionado á sequência, nesse caso, "latir".


## Conceitos básicos do serviço OpenAI do azure


- O serviço OpenAI do Azure é a solução de nuvem da Microsoft para implantar, personalizar e hospedar modelos de linguagens grandes.


O serviço do OpenAI do Azure consiste em:

- Modelos de IA gerativa predefinidos.
- Funcionalidades de personalização


* Ferramentas integradas para detectar e mitigar casos de uso prejudiciais para que os usuários possam implementar a IA com responsabilidade.
* Segurança corporativa com RBAC (controle de acesso baseado em função) e redes privadas.


Você pode usar vários métodos para desenvolver soluções do Azure OpenAI:

- Estúdio de IA do azure
- API REST
- SDKs com suporte e CLI do Azure

A quais modelos o OpenAI do Azure dá suporte?

![GPT-4](image-19.png)

![GPT-3.5](image-20.png)

![Incorporações](image-21.png)

![DALL-E](image-22.png)


### Como usar o OpenAI do Azure

* Estúdio Azure OpenAI:
  - Criar e implantar modelos de IA para aplicativos de software
  - Alimentado por modelos generativos de IA otimizados para diversas tarefas
  - Incluem: GPT-4, GPT-3.5, Embeddings e DALL-E

* Playgrounds:
- Experimente modelos Azure OpenAI sem codificação
- Use a configuração do assistente para instruir o modelo sobre como ele deve se comportar


### Funcionalidades de linguagem natural do OpenAI do azure

Os modelos de GPT (transformadores pré-treinados generativos) são excelentes para entender e criar linguagem natural.


![alt text](image-23.png)

![alt text](image-24.png)

- Os modelos GPT traduzem linguagem natural ou trechos de código em código.
- A geração de código vai além de apenas escrever código a partir de prompts em linguagem natural.

![alt text](image-25.png)

![alt text](image-26.png)


### Funcionalidades de imagem da OpenAI do azure

Os modelos de IA gerativa podem editar e criar imagens. O modelo que funciona com imagens é chamado DALL-E, que dá suporte à criação de imagem, edição de imagem e criação de variações de imagem.

- Com o DALL-E você pode até solicitar uma imagem em um determinado estilo. Os estilos também podem ser usados para edições e variações
- DALL-E pode editar a imagem conformo solicitado, alterando seu estilo, adicionando ou removendo itens ou gerando novo conteúdo para adicionar.
- Variações de imagem podem ser criadas fornecendo uma imagem e especificando quantas variações da imagem você deseja.
