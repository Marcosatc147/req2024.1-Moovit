# Cenário

Cenários são descrições detalhadas de situações específicas que ocorrem durante a interação de um usuário com um sistema. Eles ilustram uma sequência de eventos e decisões que levam à realização de uma tarefa ou objetivo dentro do sistema, como se o sistema estivesse sendo usado na vida real.

## Modelo de Cenário

| Elemento | Descrição     |
|----------|---------------------|
| Titulo  | O titulo do cenário |
| Objetivo  | O que deve ser alcançado com a realização de uma certa tarefa |
| Contexto  | Descreve o estado inicial da tarefa |
| Recursos  | Ferramentas que devem estar disponíveis para ocorrência do cenário |
| Atores  | O responsavel pela realização da tarefa |
| Episódios | Descrição em etapas de como os cenários se desenrolam |
| Restrição  | Características que o cenário precisa atender |
| Exceção  | Situações que podem interromper o cenário |

## Cenários Produzidos

| ID | Título |
|----------|---------------------|
| CN1  | Consulta de Rotas de Transporte Público |
| CN2  | Utilização de Serviço de Bicicletas Compartilhadas |
| CN3  | Uso de Benefícios Premium no Moovit |
| CN4  | Integração com Serviços de Carona Paga |
| CN5  | Procura por uma Linha de Ônibus Específica |
| CN6  | Usuário Favorita Linhas de Transporte para Acesso Rápido |
| CN7  | Verificação da Proximidade de um Ônibus |
| CN8  | Planejamento de Viagem com Múltiplos Modos de Transporte |
| CN9  | Usuário Reporta um Problema no Transporte Público |
| CN10  | Acesso a Notícias Relacionadas ao Transporte Público |
| CN11  | Atualização de Informações de Transporte Público por um Mooviter |

|Autor  | Versão          |Data|
|-------|-----------------|----|
|[Diego Carlito](https://github.com/DiegoCarlito)|1ª   |19/08/2024|

---

## CN1

| Elemento | Descrição     |
|----------|---------------------|
| Titulo  | Consulta de **Rotas** de **Transporte Público** |
| Objetivo  | Permitir que o **usuário** encontre a **rota** mais eficiente usando **transporte público** |
| Contexto  | O **usuário** deseja se deslocar para um local específico utilizando **transporte público**|
| Recursos  | Conexão à internet, localização ativada no dispositivo, **aplicativo Moovit** instalado |
| Atores  | **Usuário** |
| Episódios | O **usuário** abre o **aplicativo Moovit**. <br> O **usuário** insere o destino desejado no campo de **definir destino**. <br> O **sistema** solicita a localização atual do **usuário**. <br> O **sistema** apresenta as opções de **rotas** de **transporte público** disponíveis. <br> O **usuário** escolhe a **rota** que considera mais adequada. <br> O **sistema** apresenta as instruções de navegação e informações sobre horários dos veículos. <br> O **usuário** segue as instruções para completar sua viagem. |
| Restrição  | O **sistema** deve fornecer informações precisas e em tempo real sobre as **rotas** e horários |
| Exceção  | Se a conexão com a internet falhar, o **sistema** deve fornecer **rotas** baseadas em informações pré-carregadas (modo offline) |

|Autor  | Versão          |Data|
|-------|-----------------|----|
|Marcos Antonio| 1ª   |29/07/2024|
|[Diego Carlito](https://github.com/DiegoCarlito)|2ª   |19/08/2024|

---

## CN2

| Elemento | Descrição     |
|----------|---------------------|
| Titulo  | Utilização de Serviço de **Bicicletas Compartilhadas** |
| Objetivo  | Auxiliar o **usuário** a encontrar e utilizar uma **bicicleta compartilhada** |
| Contexto  | O **usuário** está próximo a um **ponto de bicicletas compartilhadas** e deseja saber se há bicicletas disponíveis |
| Recursos  | Conexão à internet, **Moovit** instalado, localização ativada |
| Atores  | **Usuário**, empresa de **bicicletas compartilhadas** |
| Episódios | O **usuário** abre o **Moovit** e busca a opção de **bicicletas compartilhadas**. <br> O **sistema** mostra no **mapa** as **estações de bicicletas compartilhadas** mais próximas e a quantidade de bicicletas disponíveis. <br> O **usuário** seleciona a estação desejada. <br> O **sistema** exibe as instruções para chegar até a estação. <br> O **usuário** vai até a estação e desbloqueia a bicicleta através de um aplicativo parceiro. <br> O **usuário** utiliza a bicicleta para continuar o **trajeto** planejado. |
| Restrição  | As informações sobre disponibilidade de bicicletas devem estar sempre atualizadas |
| Exceção  | Se todas as bicicletas estiverem ocupadas, o **sistema** deve sugerir alternativas (outra estação ou outro meio de transporte) |

|Autor  | Versão          |Data|
|-------|-----------------|----|
|[Diego Carlito](https://github.com/DiegoCarlito)|1ª   |19/08/2024|

---

## CN3

| Elemento | Descrição     |
|----------|---------------------|
| Titulo  | Uso de **Benefícios Premium** no **Moovit** |
| Objetivo  | Oferecer ao **usuário** uma experiência premium com funcionalidades adicionais no **Moovit** |
| Contexto  | O **usuário** deseja saber se vale a pena assinar o pacote de **benefícios premium **|
| Recursos  | Conexão à internet, **aplicativo Moovit** instalado |
| Atores  | **Usuário** |
| Episódios | O **usuário** acessa a área de benefícios no **aplicativo Moovit**. <br> O **sistema** apresenta as opções de pacotes de benefícios disponíveis. <br> O **usuário** visualiza os detalhes de cada pacote, incluindo as funcionalidades adicionais. <br> O **usuário** decide **assinar o pacote premium**. <br> O **sistema** processa o pagamento e habilita o **Moovit+** no **aplicativo**. <br> O **usuário** começa a utilizar os novos benefícios, como **alertas** personalizados e **rotas** otimizadas. |
| Restrição  | O **sistema** deve ser capaz de processar pagamentos de forma segura |
| Exceção  | Se o pagamento não for aprovado, o sistema deve notificar o **usuário** e oferecer opções para tentar novamente |

|Autor  | Versão          |Data|
|-------|-----------------|----|
|[Diego Carlito](https://github.com/DiegoCarlito)|1ª   |19/08/2024|

---

## CN4

| Elemento | Descrição     |
|----------|---------------------|
| Titulo  | Integração com Serviços de **Carona Paga** |
| Objetivo  | Oferecer ao **usuário** a opção de usar um serviço de **carona paga** para complementar seu **trajeto** |
| Contexto  | O **usuário** deseja combinar o uso de **transporte público** com **carona paga** para chegar mais rápido ao destino |
| Recursos  | Conexão à internet, **aplicativo Moovit** instalado, aplicativos de **carona paga** integrados |
| Atores  | **Usuário**, serviço de **carona paga** (ex: Uber) |
| Episódios | O **usuário** insere seu destino no **aplicativo Moovit**. <br> O **sistema** apresenta **rotas** que combinam **transporte** público e **caronas pagas**. <br> O **usuário** seleciona a **rota** que inclui o uso de um serviço de **carona paga**. <br> O **sistema** redireciona o **usuário** para o aplicativo de **carona paga** para agendar o carro. <br> O **usuário** conclui a viagem utilizando ambos os meios de transporte. |
| Restrição  | A integração deve ser fluida e as **rotas** combinadas devem considerar o tempo estimado de chegada dos carros de carona |
| Exceção  | Se não houver carros disponíveis, o **sistema** deve recalcular a **rota** usando apenas **transporte público** |

|Autor  | Versão          |Data|
|-------|-----------------|----|
|[Diego Carlito](https://github.com/DiegoCarlito)|1ª   |19/08/2024|

---

## CN5

| Elemento | Descrição     |
|----------|---------------------|
| Titulo  | Procura por uma **Linha de Ônibus Específica** |
| Objetivo  | Permitir que o **usuário** encontre uma **linha de ônibus** específica e visualize suas rotas e horários |
| Contexto  | O **usuário** deseja verificar os horários e **paradas** de uma **linha de ônibus** específica antes de sair de casa |
| Recursos  | Conexão à internet, **aplicativo Moovit** instalado |
| Atores  | **Usuário** |
| Episódios | O **usuário** abre o **aplicativo Moovit**. <br> O **usuário** acessa a opção de busca por **linhas de ônibus** no **aplicativo**. <br> O **usuário** utiliza a função **pesquisar por linha** na barra de pesquisa. <br> O **sistema** exibe os resultados da busca, mostrando a **linha de ônibus** correspondente. <br> O **usuário** seleciona a **linha de ônibus** desejada. <br> O **sistema** apresenta a **rota** completa da linha, incluindo as **paradas** e horários de chegada. <br> O **usuário** verifica as informações e planeja seu deslocamento de acordo com os horários disponíveis. |
| Restrição  | As informações sobre os horários e **paradas** devem estar atualizadas e refletir as condições em tempo real |
| Exceção  | Se a **linha de ônibus** estiver fora de operação ou os horários não estiverem disponíveis, o **sistema** deve notificar o **usuário** e sugerir **rotas** alternativas |

|Autor  | Versão          |Data|
|-------|-----------------|----|
|Márcio Henrique| 1ª   |31/07/2024|
|[Diego Carlito](https://github.com/DiegoCarlito)|2ª   |19/08/2024|

---

## CN6

| Elemento | Descrição     |
|----------|---------------------|
| Titulo  | **Usuário** Favorita Linhas de Transporte para Acesso Rápido |
| Objetivo  | Permitir que o **usuário** salve suas linhas de ônibus ou metrô favoritas para acessá-las rapidamente no futuro |
| Contexto  | O **usuário** frequentemente utiliza as mesmas linhas de transporte e deseja acessá-las mais rapidamente |
| Recursos  | Conexão à internet, **aplicativo Moovit** instalado, funcionalidade de favoritos habilitada |
| Atores  | **Usuário** |
| Episódios | O **usuário** abre o **aplicativo Moovit**. <br> O **usuário** busca por uma linha de ônibus ou metrô que utiliza frequentemente. <br> O **sistema** exibe os detalhes da linha selecionada. <br> O **usuário** seleciona a opção de **favoritar** a linha. <br> O **sistema** adiciona a linha à lista de favoritos do **usuário**, acessível a partir da tela principal ou de um menu dedicado. <br> O **usuário**, em futuras consultas, acessa rapidamente suas linhas favoritas diretamente da lista de favoritos. |
| Restrição  | As linhas favoritas devem ser acessíveis rapidamente e as informações devem ser atualizadas em tempo real |
| Exceção  | Se a linha favorita não estiver operando ou houver uma mudança significativa, o sistema deve notificar o usuário e sugerir alternativas |

|Autor  | Versão          |Data|
|-------|-----------------|----|
|[Diego Carlito](https://github.com/DiegoCarlito)|1ª   |19/08/2024|

---

## CN7

| Elemento | Descrição     |
|----------|---------------------|
| Titulo  | Verificação da Proximidade de um Ônibus |
| Objetivo  | Permitir que o **usuário** verifique a localização atual do ônibus e estime o tempo de chegada à sua parada |
| Contexto  | O **usuário** está na **parada** de ônibus e deseja saber se o ônibus que ele precisa está se aproximando |
| Recursos  | Conexão à internet, **aplicativo Moovit** instalado, sistema de rastreamento de **transporte público** habilitado |
| Atores  | **Usuário** |
| Episódios | O **usuário** abre o **aplicativo Moovit**. <br> O **usuário** acessa a função **localizar**. <br> O **usuário** seleciona a **parada** de ônibus onde ele está esperando. <br> O **sistema** exibe uma lista de ônibus que estão se aproximando dessa **parada**. <br> O **usuário** localiza a **linha de ônibus** desejada na lista. <br> O **sistema** exibe a localização atual do ônibus no **mapa** e uma estimativa do tempo de chegada à **parada**. <br> O **usuário** decide se vai esperar pelo ônibus ou se procura uma **rota** alternativa. |
| Restrição  | As informações de localização e tempo de chegada devem estar precisas e em tempo real |
| Exceção  | Se o **sistema** não conseguir obter a localização do ônibus ou houver um atraso significativo, deve notificar o usuário e sugerir opções alternativas |

|Autor  | Versão          |Data|
|-------|-----------------|----|
|[Diego Carlito](https://github.com/DiegoCarlito)|1ª   |19/08/2024|

---

## CN8

| Elemento | Descrição     |
|----------|---------------------|
| Titulo  | Planejamento de Viagem com Múltiplos Modos de Transporte |
| Objetivo  | Permitir que o **usuário** planeje uma **rota** que envolva diferentes modos de transporte, como ônibus, metrô e caminhada |
| Contexto  | O **usuário** precisa se deslocar de um ponto A a um ponto B utilizando uma combinação de **transporte público** e caminhada |
| Recursos  | Conexão à internet, **aplicativo Moovit** instalado, sistema de planejamento multimodal habilitado |
| Atores  | **Usuário** |
| Episódios | O **usuário** abre o **aplicativo Moovit** e acessa a opção de planejamento de viagem. <br> O **usuário** insere o local de partida e destino. <br> O **usuário** utiliza a função de **filtrar rotas**. <br> O **sistema** exibe as opções de **rota**, combinando diferentes modos de transporte, incluindo ônibus, metrô e caminhada. <br> O **usuário** seleciona a **rota** mais conveniente. <br> O **sistema** exibe as instruções detalhadas para cada etapa da viagem, incluindo horários e pontos de transferência. <br> O **usuário** confirma a **rota** e inicia a viagem. |
| Restrição  | As informações sobre horários, conexões e **rotas** devem ser precisas e atualizadas em tempo real |
| Exceção  | Se um dos modos de transporte não estiver disponível (ex.: interrupção do metrô), o sistema deve sugerir uma rota alternativa |

|Autor  | Versão          |Data|
|-------|-----------------|----|
|[Diego Carlito](https://github.com/DiegoCarlito)|1ª   |19/08/2024|

---

## CN9

| Elemento | Descrição     |
|----------|---------------------|
| Titulo  | **Usuário** Reporta um Problema no **Transporte Público** |
| Objetivo  | Permitir que o **usuário** reporte problemas, como atrasos, superlotação ou mudanças de **rota** |
| Contexto  | O **usuário** encontra um problema durante o uso do **transporte público** e deseja reportá-lo para ajudar outros usuários |
| Recursos  | Conexão à internet, **aplicativo Moovit** instalado, funcionalidade de **reportar** habilitada |
| Atores  | **Usuário** |
| Episódios | O **usuário** abre o **aplicativo Moovit** durante ou após a viagem. <br >O **usuário** acessa a opção de **reportar** um problema. <br> O **usuário** seleciona o tipo de problema (ex.: atraso, superlotação, alteração de rota). <br> O **usuário** insere detalhes adicionais e, se possível, anexa uma foto. <br> O **sistema** recebe o reporte e encaminha para os responsáveis, ao mesmo tempo em que notifica outros usuários do mesmo serviço. |
| Restrição  | O **sistema** deve ser capaz de processar e encaminhar os problemas relatados de forma rápida e eficiente |
| Exceção  | Se o **sistema** não puder processar o reporte devido a uma falha ou falta de dados, deve informar o **usuário** e sugerir tentar novamente mais tarde |

|Autor  | Versão          |Data|
|-------|-----------------|----|
|[Diego Carlito](https://github.com/DiegoCarlito)|1ª   |19/08/2024|

---

## CN10

| Elemento | Descrição     |
|----------|---------------------|
| Titulo  | Acesso a **Notícias** Relacionadas ao **Transporte Público** |
| Objetivo  | Permitir que o **usuário** se mantenha informado sobre **notícias**, atualizações e alertas relacionados ao **transporte público** |
| Contexto  | O **usuário** deseja se atualizar sobre mudanças, interrupções ou eventos que afetam o **transporte público** na sua cidade |
| Recursos  | Conexão à internet, **aplicativo Moovit** instalado, funcionalidade de **notícias** e **alertas** habilitada |
| Atores  | **Usuário** |
| Episódios | O **usuário** abre o **aplicativo Moovit**. <br> O **usuário** acessa a seção de **notícias** ou **alertas** sobre o **transporte público**. <br> O **sistema** exibe as notícias mais recentes relacionadas ao metrô, ônibus e outros modos de **transporte público**. <br> O **usuário** seleciona uma **notícia** para ler mais detalhes. <br> O **sistema** exibe a **notícia** completa, incluindo informações relevantes, como mudanças de horários, novas **rotas**, ou eventos que possam afetar o **transporte público**. <br> O **usuário** avalia as informações e, se necessário, ajusta seus planos de viagem conforme as novidades. |
| Restrição  | As **notícias** devem ser precisas, atualizadas e diretamente relevantes para o **transporte público** na área do **usuário** |
| Exceção  | Se não houver **notícias** recentes ou se houver uma falha na atualização das informações, o sistema deve informar o **usuário** e sugerir fontes alternativas para buscar informações |

|Autor  | Versão          |Data|
|-------|-----------------|----|
|[Diego Carlito](https://github.com/DiegoCarlito)|1ª   |19/08/2024|

---

## CN11

| Elemento | Descrição     |
|----------|---------------------|
| Titulo  | Atualização de Informações de **Transporte Público** por um **Mooviter** |
| Objetivo  | Manter as informações das **linhas de ônibus** atualizadas no **Moovit** para garantir precisão e confiabilidade aos **usuários** |
| Contexto  | Um **Mooviter** acessa o **Moovit** para revisar e atualizar informações sobre as **linhas de transporte** público em uma determinada cidade. As informações estão desatualizadas devido a mudanças recentes nos horários ou **rotas** |
| Recursos  | Acesso ao **aplicativo Moovit**, conexão à internet, informações recentes sobre alterações nas **linhas de transporte** ou horários obtidas de fontes confiáveis |
| Atores  | **Mooviter** |
| Episódios | O **Mooviter** entra no **aplicativo Moovit** e acessa a seção de edição de dados. <br> Ele identifica uma **linha de ônibus** cujas informações estão desatualizadas. <br> O **Mooviter** verifica as informações atualizadas junto às fontes disponíveis, como sites oficiais de **transporte público**. <br> Ele atualiza os dados no **Moovit**, incluindo novos horários e possíveis mudanças nas **rotas**. <br> O **sistema** salva as alterações e sincroniza as novas informações com a base de dados global do **Moovit**. <br> As informações atualizadas tornam-se visíveis para todos os **usuários** do **Moovit**. |
| Restrição  | As atualizações só podem ser feitas por **Mooviters** autorizados; as informações devem ser verificadas antes de serem publicadas |
| Exceção  | Se o **Mooviter** não conseguir verificar as informações, ele deve deixar um aviso para que outro **Mooviter** ou administrador possa revisar a situação. |

---

# Léxico
Léxico é um artefato utilizado na engenharia de requisitos para definir e padronizar os termos e expressões usados dentro do contexto de um sistema de software. Ele consiste em uma lista estruturada de palavras, frases ou conceitos relevantes, cada um acompanhado de uma descrição clara e concisa, explicando seu significado no contexto do projeto.

- Símbolo: Representa o termo ou expressão que será definido no léxico. É o nome do conceito, ação ou estado relevante para o sistema, e serve como ponto central para a definição.
- Classificação: Identifica a natureza do símbolo, categorizando-o em uma das seguintes classes:
    - Verbo: Ações ou operações realizadas no sistema.
    - Objeto: Entidades ou elementos tangíveis ou intangíveis presentes no sistema ou em seu ambiente.
    - Estado: Condições ou situações em que os objetos ou ações podem se encontrar.
- Sinônimo: Inclui outras palavras ou termos que podem ser usados como alternativas para o símbolo principal, ajudando a identificar variações ou termos equivalentes usados em diferentes contextos.
- Noção: Fornece uma definição clara e objetiva do que o símbolo significa dentro do contexto do sistema. Explica o conceito, a ação ou o estado de forma concisa e fácil de entender.
- Impacto: Descreve como o símbolo afeta ou é afetado pelo sistema. Isso inclui seu papel na operação do sistema, suas interações com outros elementos, e como ele contribui para o funcionamento geral do software.

| Símbolo | Classificação | Sinônimo | Noção | Impacto |
|----|-----|----|-----|-----|
| Moovit | Objeto | Aplicativo, Sistema | Software móvel instalado em dispositivos dos usuários para acessar serviços de transporte urbano | O aplicativo Moovit é a plataforma principal de interação, onde o usuário acessa todas as funcionalidades e informações do sistema |
| Linha de Transporte | Objeto | Itinerário, Linha de Ônibus | Representa uma rota específica de um transporte público  | Permite ao usuário encontrar as rotas disponíveis para planejar suas viagens e acessar horários em tempo real |
| Parada | Objeto | Ponto de Ônibus, Estação | Local designado onde os veículos de transporte público param para embarque e desembarque de passageiros | As paradas são essenciais para fornecer informações sobre onde o usuário pode pegar o transporte |
| Usuário | Objeto | Passageiro | Pessoa que utiliza o sistema Moovit para planejar suas viagens e acessar informações sobre o transporte público | O usuário interage com todas as funcionalidades do sistema, desde a busca por rotas até o pagamento de tarifas |
| Favoritar | Verbo | Salvar, Adicionar | Ação de marcar uma linha de transporte ou parada como favorita para acesso rápido | Facilita o acesso do usuário às suas linhas de transporte preferidas, melhorando a experiência de uso do sistema |
| Transporte Público | Objeto | Transporte Coletivo | Sistema de transporte disponível para o público em geral, incluindo ônibus e metrô | Principal foco do Moovit, é base sobre o qual o aplicativo opera para fornecer informações e serviços aos usuários |
| Localizar | Verbo | Encontrar, Identificar | Ação de determinar a posição de um transporte público, estações de ônibus, a localização atual do usuário e estações de bicicletas compartilhadas | Essencial para a experiência do usuário no Moovit, permitindo que ele saiba onde está e onde precisa ir para acessar o transporte público |
| Definir Destino | Verbo | Inserir Destino | Ação de o usuário informar o local de destino desejado no Moovit para obter rotas, horários, e opções de transporte | Inserir Destino é um passo crucial para que o sistema possa calcular as melhores rotas e opções de transporte disponíveis. Afeta diretamente a experiência do usuário ao proporcionar informações personalizadas e precisas para o trajeto |
| Alertas | Objeto | Notícias | Atualizações sobre o funcionamento do transporte público | Ajuda o usuário a estar informado sobre mudanças, interrupções e eventos que afetam o transporte público |
| Reportar |  Verbo | Informar, Notificar | Ação de comunicar as condições de uma linha de transporte ou de uma estação, como atrasos, superlotação, ou problemas estruturais, diretamente através do Moovit | A função de Reportar permite que os usuários contribuam com a atualização em tempo real das condições do transporte público, melhorando a experiência de todos os usuários. Também ajuda a manter as informações do sistema precisas e a fornecer dados úteis para gestores de transporte e para outros usuários |
| Assinar Pacote Premium | Verbo | Efetuar Pagamento | Ação de pagar por benefícios extras dentro do Moovit | O usuário pode usar o sistema para efetuar pagamento de assinatura, recebendo benefícios |
| Moovit+ | Objeto | Benefícios Premium | Serviço de assinatura premium do Moovit que oferece funcionalidades adicionais e exclusivas aos usuários, como informações em tempo real mais detalhadas, alertas personalizados, e ausência de anúncios | O Moovit+ melhora a experiência de uso ao proporcionar recursos avançados, incentivando a adesão a serviços pagos e gerando receita para a plataforma. Ele também aumenta a fidelidade dos usuários ao oferecer vantagens exclusivas e personalizadas |
| Mooviter | Objeto | Editor | Usuário dedicado que ajuda a manter o mapa e as informações do Moovit atualizadas em diversas cidades | Garante que dados sobre rotas, paradas e horários estejam sempre atualizados e precisos para todos os usuários |
| Rota | Objeto | Trajeto, Caminho | Caminho a partir da posição atual até o ponto de destino | Fundamental para o planejamento de viagens dos usuários, as rotas determinam quais trajetos estão disponíveis e como os passageiros podem chegar ao seu destino. O Moovit usa essa informação para fornecer recomendações de viagem e otimizar o tempo de deslocamento |
| Filtrar Rotas | Verbo | Selecionar Rotas | Ação de aplicar critérios específicos para reduzir ou ajustar a lista de rotas disponíveis, mostrando apenas as que melhor atendem às necessidades do usuário | Crucial para melhorar a eficiência e experiência do usuário no Moovit, permitindo que ele encontre rapidamente a rota mais conveniente com base em preferências, como menor tempo de viagem, menos conexões, caminhar menos e preferência de modos de transporte |
| Mapa | Objeto | Plano | Representação gráfica que exibe rotas, paradas, locais de transporte público e privado dentro de uma área geográfica, utilizada para orientar o usuário em suas jornadas | Essencial para a navegação e planejamento de viagens, o Mapa oferece uma visão geral e detalhada das opções de transporte, permitindo ao usuário visualizar e escolher a melhor rota ou serviço disponível. Ele é central na interface do Moovit, facilitando a interação com o sistema |
| Pesquisar por Linha | Verbo | Buscar Linha | Ação de procurar uma linha de ônibus ou metrô | Essencial para a navegação no aplicativo, permitindo que o usuário encontre informações detalhadas sobre uma linha específica, como horários, paradas, e rota completa. Isso melhora a usabilidade e a precisão da informação fornecida pelo Moovit |
| Carona Paga | Objeto | Transporte por Aplicativo | Serviço de transporte privado oferecido por motoristas que utilizam aplicativos como Uber ou 99, onde o passageiro paga pela carona | A Carona Paga é integrada ao Moovit para fornecer aos usuários mais uma opção de transporte, especialmente em áreas com pouca oferta de transporte público. Essa função amplia as possibilidades de deslocamento e melhora a conveniência para o usuário |
| Bicicleta Compartilhada | Objeto | Bike Compartilhada | Bicicletas disponíveis em estações específicas para serem alugadas por um tempo determinado, permitindo ao usuário devolver em qualquer estação do sistema | A Bicicleta Compartilhada contribui para a mobilidade sustentável e está integrada no Moovit como uma opção alternativa de transporte, especialmente útil para curtas distâncias. Ela é uma parte importante da oferta multimodal do aplicativo, complementando o transporte público |
| Estação de Bicicletas Compartilhadas | Objeto | Ponto de Bicicletas Compartilhadas | Locais físicos onde bicicletas compartilhadas estão disponíveis para retirada e devolução por parte dos usuários | Importante para a integração de múltiplos modos de transporte no Moovit, oferecendo aos usuários uma alternativa ecológica e flexível para deslocamentos curtos. As informações sobre estas estações ajudam no planejamento de rotas multimodais e na escolha do transporte mais eficiente |


| Autores | Versão | Data |
|----|-----|----|
|Márcio Henrique e Marcos Antonio|1ª   | 31/07/2024|
|[Diego Carlito](https://github.com/DiegoCarlito)|2ª   |19/08/2024|
