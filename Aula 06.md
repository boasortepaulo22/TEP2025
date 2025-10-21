**

1. Crie um prompt simples pedindo ao modelo para escrever uma carta de recomendação sem fornecer nenhum contexto adicional. Depois, revise o prompt adicionando detalhes sobre o destinatário e o propósito da carta. Como o contexto influenciou a qualidade da resposta?  
  
**Modelo: llama-3.3-70b-versatile  
Prompt inicial:

Escreva uma carta de recomendação.

**Resposta inicial (curta / genérica):

Prezados, venho por meio desta recomendar fulano de tal. Ele é dedicado, pontual e desempenha bem suas funções. Atenciosamente.

**Prompt final (refinado):

Escreva uma carta de recomendação para Maria da Silva, candidata a vaga de analista de suporte técnico em uma empresa de TI. Contexto: Maria trabalhou durante 2 anos na empresa Meta como técnico de suporte, atendendo chamados de nível 1 e 2, implantando atualizações e realizando treinamentos para usuários. Destaque: habilidades técnicas (Linux, Windows, ticketing), boa comunicação com usuários não técnicos, capacidade de documentação e trabalho em equipe. A carta deve ter tom profissional, cerca de 3 parágrafos, e incluir um contato (email) para referência.

**Resposta final (refinada):

À Gerência de Recursos Humanos,

É com prazer que recomendo Maria da Silva para a posição de Analista de Suporte Técnico. Durante dois anos na Empresa X, Maria atuou no atendimento de chamados de níveis 1 e 2, demonstrando amplo domínio de ambientes Windows e Linux, além de experiência com sistemas de ticketing. Realizou com sucesso atualizações, implantações e documentou procedimentos essenciais para o time.

Maria se comunica de forma clara com usuários sem conhecimentos técnicos, traduzindo termos técnicos em instruções práticas e fáceis de seguir. Também contribuiu para treinamentos internos e melhorou a base de conhecimento da equipe. É colaborativa, organizada e cumpre prazos.

Em caso de dúvida, estou à disposição pelo email: referencia@example.com.

Atenciosamente,  
João Souza — Coordenador de TI

Observação (como o contexto ajudou): ao adicionar nome, cargo, responsabilidades e tom desejado, a carta ficou muito mais específica, útil e convincente — evita generalidades e mostra evidências concretas.

2. Defina uma persona para um assistente virtual que auxilia clientes de uma livraria. Crie um prompt que utilize essa persona para responder clientes e indicar livros. Avalie como a definição de persona impacta a resposta do modelo.

**Modelo: llama-3.3-70b-versatile  
Prompt inicial (sem persona):

Recomende livros sobre ficção científica.

**Resposta inicial (genérica):

Recomendo "Duna", "Neuromancer" e "Fundação".

**Prompt final (com persona):

Você é Clara, uma assistente virtual amigável e especializada em uma livraria independente chamada “Livros & Café”. Como Clara, responda a um cliente que procura livros de ficção científica para alguém que gosta de histórias com worldbuilding detalhado, personagens complexos e temas sociais. Ofereça 3 recomendações com 2 linhas justificando cada uma, e sugira um livro alternativo para leitura mais leve. Mantenha tom acolhedor e profissional.

**Resposta (como persona):

Oi! Aqui é a Clara da Livros & Café — que delícia escolher ficção científica! Pelas suas preferências, recomendo:

1. Duna (Frank Herbert) — worldbuilding épico e política interplanetária que prende pela profundidade do universo.  
      
    
2. A Mão Esquerda da Escuridão (Ursula K. Le Guin) — personagens complexos e reflexão social sobre gênero e cultura.  
      
    
3. Fundação (Isaac Asimov) — grande escala histórica e ideias sobre o futuro da civilização.  
    Como alternativa mais leve, experimente The Long Way to a Small, Angry Planet (Becky Chambers) — foco em personagens e tom acolhedor. Quer que eu reserve algum deles pra você?  
      
    

Impacto da persona: define tom, estilo e recomendações mais alinhadas ao cliente; torna a resposta mais útil e comercialmente aplicável.

  
  

3. Escreva um prompt vago pedindo ao modelo para descrever um cenário futurista, sem dar detalhes. Depois, reescreva o prompt com instruções claras e específicas sobre o tipo de cenário e detalhes a serem incluídos. Avalie a importância da clareza nas instruções.

**Modelo: llama-3.3-70b-versatile  
Prompt inicial (vago):

Descreva um cenário futurista.

**Resposta inicial:

**Cenário Futurista: Uma Visão de 2154**

Imagine uma cidade chamada Nova Terra, localizada em uma costa litorânea, onde a tecnologia e a natureza se entrelaçam em perfeita harmonia. O ano é 2154, e a humanidade alcançou um nível de avanço tecnológico sem precedentes, transformando a forma como vivemos, trabalhamos e interagimos.

**Arquitetura e Infraestrutura**

A cidade de Nova Terra é uma maravilha de engenharia, com arranha-céus que se estendem até o céu e são cobertos por uma camada de painéis solares que geram energia limpa e renovável. As ruas estão pavimentadas com um material especial que pode absorver e armazenar energia solar durante o dia, iluminando a cidade à noite.

Os edifícios são projetados para serem autossuficientes, com sistemas de reciclagem de água e resíduos, e são construídos com materiais sustentáveis e reciclados. A cidade é conectada por uma rede de tubos de transporte de alta velocidade, que permitem que as pessoas e os produtos sejam transportados rapidamente e de forma eficiente.

**Tecnologia e Inovação**

A tecnologia é uma parte integral da vida cotidiana em Nova Terra. A inteligência artificial (IA) é onipresente, controlando todos os aspectos da cidade, desde a gestão de recursos até a segurança pública. A IA também é usada para melhorar a saúde e o bem-estar dos cidadãos, com robôs e drones que fornecem assistência médica e realizam tarefas domésticas.

A realidade virtual e aumentada são partes fundamentais da vida em Nova Terra, permitindo que as pessoas vivam experiências imersivas e interativas em casa, no trabalho ou em espaços públicos. A comunicação é feita por meio de implantes cerebrais ou óculos de realidade aumentada, que permitem que as pessoas se conectem com outras pessoas e com a cidade de forma instantânea.

**Meio Ambiente e Sustentabilidade**

Nova Terra é uma cidade que prioriza a sustentabilidade e a proteção do meio ambiente. A cidade é alimentada por fontes de energia renovável, como a energia solar, eólica e hidrelétrica. A água é reciclada e reutilizada, e os resíduos são minimizados e convertidos em recursos.

A cidade também é lar de um vasto parque e jardim, que fornece oxigênio e absorve dióxido de carbono. A vegetação é mantida por robôs e drones, que monitoram e cuidam das plantas de forma constante.

**Conclusão**

Nova Terra é um exemplo de como a tecnologia e a inovação podem ser usadas para criar uma cidade sustentável e habitável. A cidade é um lugar onde a humanidade pode viver em harmonia com o meio ambiente, aproveitando ao máximo as oportunidades oferecidas pela tecnologia para melhorar a vida cotidiana. É um futuro promissor, onde a humanidade pode crescer e evoluir de forma sustentável e responsável.
  

**Prompt final (específico):

Descreva um cenário futurista ambientado em 2085, em uma cidade costeira que sofreu elevação do nível do mar. Inclua: arquitetura adaptativa (edifícios flutuantes), transporte público (barcos-autônomos e trilhos magnéticos), economia local (pesca integrada com biotecnologia), vida social (mercados flutuantes e cooperativas) e um conflito social ligado à distribuição de água potável. Use 4 parágrafos, linguagem descritiva, sem exageros fantásticos.

**Resposta final (detalhada):

Em 2085 a antiga orla transformou-se em um mosaico de ilhas urbanas interligadas por passarelas transparentes e edificações de base flutuante. Os prédios têm cascos modulares que regulam flutuação e são revestidos por jardins biofiltrantes que purificam a água do entorno. Alguns setores mantêm estruturas elevadas — pontes-cais servem tanto de comércio quanto de refúgio em marés altas.

O transporte público é um sistema híbrido: barcos-autônomos elétricos navegam rotas predefinidas entre ilhas enquanto uma linha de trilhos magnéticos subaquáticos liga os principais centros a alta velocidade. Bicicletas elétricas dobráveis e passarelas rolantes integram os percursos de curta distância. A logística é orquestrada por um núcleo de IA urbano que prioriza rotas sustentáveis.

A economia é centrada em pesca regenerativa e biotecnologias marinhas: fazendas verticais de algas produzem matérias-primas para alimentos e bioplásticos, e cooperativas locais reutilizam excedentes para manufatura leve. Mercados flutuantes funcionam como centros culturais onde chefs, cientistas marinhos e artesãos trocam produtos e saberes.

Entretanto, há tensões: o controle das poucas fontes de água potável e das estações de dessalinização concentra poder em conglomerados privados, gerando protestos e demandas por gestão comunitária. Movimentos cooperativos pressionam por modelos públicos de acesso, transformando a gestão hídrica no principal debate político local.

Avaliação: especificação aumentou riqueza de detalhes, coerência e utilidade do cenário.**