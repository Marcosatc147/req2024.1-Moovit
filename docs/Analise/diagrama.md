# Inspeção do Diagrama de Casos de Uso

-----

![imagem1](../assets/Diagrama%20de%20Caso%20de%20Uso/USECASE2.drawio.png)

Utilizando o método da inspeção para a análise dos Casos de Uso, prática comum na Engenharia de Requisitos, utilizada para garantir que os casos de uso sejam completos, corretos, consistentes e compreensíveis. Essa atividade faz parte de um processo de verificação e validação dos requisitos funcionais do sistema.

O processo de inspeção é essencial para garantir que os casos de uso possam ser usados como uma base confiável para o desenvolvimento, testes e outras atividades dentro do ciclo de vida do software

Neste caso em específico, será feita a análise somente do Diagrama dos Casos de Uso acima.

## Identificação dos Atores

 No diagrama, observamos os seguintes atores principais:
     - Usuário
     - Mooviter
     - Empresa de bicicletas compartilhadas
     - Governo
     - Prestador de Serviço
     - Carona Paga

Esses atores estão adequadamente representados e parecem estar corretamente vinculados aos casos de uso apropriados. No entanto, é importante verificar se há outros atores que podem estar faltando. Por exemplo, poderia haver algum intermediário entre "Prestador de Serviço" e "Carona paga" ou ja mencionar antes em forma de ator os diferentes tipos de usuários (usuário premium e não premium).


## Casos de Uso

Os casos de uso detalham as funcionalidades que o sistema Moovit oferece. Dentre os principais casos de uso, destacam-se:

Como usuário premium:
     - Remover anúncios
     - Contatos de segurança
     - Comparar rotas
     - Ver tráfego no mapa
     - Atualizar horário de chegada simultaneamente


Como usuário (usuário premium também possui acesso):
     - Utilizar serviços de bicicletas compartilhadas
     - Baixar apps de terceiros (bicicleta ou carona paga)
     - Consultar rotas de transporte público
     - Planejar viagens multimodais
     - Procura por uma linha de ônibus específica
     - Favoritar linhas de transporte para acesso rápido
     - Verificar proximidade de um ônibus
     - Acessar notícias relacionadas ao transporte público
     - Reportar um problema no transporte público


Os casos de uso cobrem uma variedade de funções, tanto básicas quanto avançadas. É importante avaliar se todos os requisitos do sistema foram mapeados. Por exemplo, faltam detalhes sobre os serviços de pagamento ou a forma de interação com esses serviços.

## Relacionamentos

Os relacionamentos entre casos de uso são expressos pelas setas tracejadas e sólidas, mostrando dependências ou relações de inclusão/extensão entre os casos.


Observa-se o relacionamento de inclusão (<<include>>) entre alguns casos de uso, como “Utilizar Serviço de Bicicletas Compartilhadas” e “Baixar App de bicicletas compartilhadas”.


A relação de inclusão parece bem aplicada, mas faltam relações mais explícitas entre outros casos de uso que podem ser dependentes. Por exemplo, "Verificar Proximidade de Ônibus" pode ser uma função incluída em "Planejar Viagem com Múltiplos Modos de Transporte". É importante garantir que todas as dependências sejam claramente mapeadas.


## Completude

O diagrama representa um sistema bastante complexo, envolvendo transporte público, bicicletas compartilhadas e serviços de carona paga

O caso de uso “Assinar” implica um modelo de assinatura, mas não há outros casos de uso que detalham como os benefícios premium serão acessados ou administrados, principalmente no caso dos Mooviters, é necessário fazer uma assinatura para ser premium, mas é para ser Mooviter?

Há uma boa variedade de casos de uso, mas algumas funcionalidades parecem sub representadas. Por exemplo, o caso de uso “Assinar” poderia ser complementado com casos de uso relacionados à gestão de assinaturas (como "Gerenciar Assinatura" ou "Cancelar Assinatura").



## Coerência e Consistência

O diagrama parece consistente em termos de representação de atores e suas interações com o sistema. No entanto, seria útil explorar mais as interações com o governo e como ele participa do sistema, uma vez que a sua função está pouco clara.


É importante garantir que todos os relacionamentos entre atores e casos de uso estejam devidamente justificados. Por exemplo, como o “Governo” participa diretamente nas ações? Quais dados ou informações são trocados entre o Moovit e o governo? Esse tipo de relacionamento precisa ser mais claro.


Embora esses atores estejam representados, o papel deles poderia ser mais detalhado. O governo, por exemplo, poderia estar envolvido no fornecimento de dados de transporte em tempo real ou na regulamentação de serviços. Seria útil adicionar casos de uso como "Fornecer Dados de Transporte em Tempo Real" ou "Atualizar Informações de Infraestrutura de Transporte" para o ator Governo.

## Detalhamento de Casos de Uso

O diagrama mostra muitos casos de uso em um nível mais superficial. Para uma inspeção mais detalhada, seria necessário ter uma descrição dos fluxos de cada caso de uso. Onde foi feito e encontramos na aba “Especificação dos Casos de Uso”, porém foram especificados somente alguns casos. Além disso, não há menção explícita a questões como segurança e autenticação, que são aspectos importantes em um sistema desse porte.


O diagrama, ao focar nas funcionalidades principais, não menciona aspectos importantes como autenticação do usuário, validação de pagamentos ou mecanismos de proteção de dados. É importante que esses requisitos sejam endereçados no diagrama ou em uma documentação adicional.


## Funcionalidades Subentendidas

Ao analisar o Moovit, algumas funcionalidades importantes parecem estar ausentes ou sub-representadas no diagrama:


Notificações em tempo real: Uma função importante do Moovit são os alertas e notificações para o usuário sobre mudanças nas linhas de transporte ou interrupções. Esse tipo de caso de uso não está explicitamente mencionado no diagrama.


Acessibilidade: Não há menção explícita de funcionalidades voltadas para usuários com necessidades especiais, como informações sobre acessibilidade de veículos e estações, algo que o Moovit considera em suas funcionalidades.


## Sugestões de Complementos

Adicionar atores secundários: Talvez seja relevante incluir outros perfis de usuários, como usuários administrativos ou de suporte.

Descrever mais detalhadamente o relacionamento com o governo: Expandir o papel do governo e como ele interage com o sistema.

Explorar mais a interação com os serviços de terceiros: Detalhar como é feita a integração com os serviços de carona paga e de bicicletas compartilhadas.

Segurança e autenticação: Considerar a adição de casos de uso que abordem segurança da informação, como "Autenticar usuário" e "Gerenciar credenciais", segue o texto:

O diagrama não menciona explicitamente nada relacionado a segurança, autenticação e privacidade de dados, que são questões cruciais em um aplicativo de mobilidade como o Moovit, que lida com informações pessoais e de localização dos usuários. Esses aspectos deveriam ser representados no diagrama. Casos de uso como "Autenticar Usuário", "Gerenciar Dados Pessoais", e "Proteção de Dados de Localização" seriam extremamente importantes para um aplicativo que depende tanto da interação com o usuário e serviços de terceiros.

Detalhar melhor o gerenciamento de assinatura premium e o papel do Mooviter.

Adicionar funcionalidades relacionadas à acessibilidade e personalização de linhas de transporte.

O diagrama de casos de uso apresenta uma visão geral sólida do sistema Moovit, cobrindo muitos dos principais requisitos funcionais. No entanto, existem áreas que podem ser mais detalhadas, especialmente no que diz respeito à segurança, integração com serviços de terceiros e a interação do sistema com o governo. Podemos pensar que por ser serviços terceiros, eles deixam de se assumir pelo aplicativo Moovit, e portanto ser mais breve nesses aspectos se for conveniente. Embora essa função seja mencionada, o fluxo de como o Moovit interage com esses serviços após o download do aplicativo não está claro. É importante explorar se o Moovit age como uma interface direta com esses serviços ou apenas redireciona o usuário. Uma abordagem mais detalhada seria adicionar casos de uso que explicam como o Moovit integra os dados desses serviços no próprio aplicativo.

Esses ajustes garantiriam uma representação mais completa e precisa do sistema Moovit, refletindo suas reais funcionalidades e atendendo a requisitos de software importantes.


