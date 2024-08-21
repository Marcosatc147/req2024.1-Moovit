# Ágil
A metodologia ágil é um conjunto de práticas e princípios de gerenciamento de projetos que enfatiza a flexibilidade, colaboração e entrega contínua.

## Backlog
Lista contendo todos as funcionalidades desejadas no produto.

### Epics

| N° | Epic                              |
| -- | --------------------------------- |
| 1  | Planejamento de Rota              |
| 2  | Informações em Tempo Real         |
| 3  | Navegação e Interface do Usuário  | 
| 4  | Integração com Outros Serviços    |
| 5  | Experiência do Usuário e Feedback |
| 6  | Suporte à Micromobilidade         |
| 7  | Segurança e Conforto do Usuário   |

### Features 

| Epic | N° | Feature                                             | 
|------|----|-----------------------------------------------------|
|  1   | 1  | Seleção de Rota                                     |
|  1   | 2  | Personalização de Rota                              |
|  2   | 1  | Monitoramento de Transporte                         |
|  2   | 2  | Alertas e Notificações                              |
|  2   | 3  | Monitoramento de Atrasos e Mudanças                 |
|  3   | 1  | Interface Intuitiva                                 |
|  3   | 2  | Modo Offline                                        |
|  3   | 3  | Interface Simples para Idosos                       |
|  4   | 1  | Integração com Serviços de Ride-Sharing             |
|  4   | 2  | Integração com Mapas                                |
|  4   | 3  | Integração com Pagamentos Digitais                  |
|  5   | 1  | Coleta de Feedback                                  |
|  5   | 2  | Comunidade e Colaboração                            |
|  5   | 3  | Expansão de Cobertura Geográfica                    |
|  5   | 4  | Suporte Multimodal para Grandes Eventos             |
|  5   | 5  | Suporte a Idiomas Adicionais                        |
|  6   | 1  | Implementação de Suporte à Micromobilidade          |
|  7   | 1  | Rotas Rápidas, Econômicas e Seguras                 |
|  7   | 2  | Opções de Transporte Acessível                      |
|  7   | 3  | Sugestões de Rotas Alternativas ou Troca de Ônibus  |
|  7   | 4  | Orientação Passo a Passo com Pontos Turísticos      |
|  7   | 5  | Aprimoramento da Experiência de Uso para Mooviters  |

### User Stories

| N°    | Tipo | User Story                                                                                                                                                                                                                     | Prioridade |
|-------|------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------|
| 1.1.1 | RF   | Como usuário, quero inserir meu destino para que o Moovit me sugira as melhores rotas disponíveis.                                                                                                                             | Alta       |
| 1.1.2 | RF   | Como usuário, quero selecionar entre diferentes opções de transporte (ônibus, metrô, trem, etc.) para personalizar minha rota.                                                                                                 | Alta       |
| 1.1.3 | RF   | Como usuário, quero ver o tempo estimado de viagem para cada rota sugerida para escolher a opção mais rápida.                                                                                                                  | Alta       |
| 1.2.1 | RF   | Como usuário, quero salvar rotas favoritas para acessá-las rapidamente no futuro.                                                                                                                                              | Média      |
| 1.2.2 | RF   | Como usuário, quero personalizar minhas preferências de transporte (ex.: evitar baldeações) para que as rotas sugeridas sejam mais adequadas para mim.                                                                         | Média      |
| 1.2.3 | RF   | Como usuário, quero poder definir horários de partida e chegada específicos para planejar minha viagem com antecedência.                                                                                                       | Alta       |
| 2.1.1 | RF   | Como usuário, quero visualizar a posição atual do meu ônibus/trem/metrô em tempo real para saber exatamente quando ele chegará.                                                                                                | Alta       |
| 2.1.2 | RF   | Como usuário, quero receber notificações sobre atrasos ou mudanças de rota para poder ajustar meu trajeto.                                                                                                                     | Alta       |
| 2.1.3 | RF   | Como usuário, quero acessar informações em tempo real sobre o status de linhas específicas (ex.: operação normal, atraso, interrupção).                                                                                        | Alta       |
| 2.2.1 | RF   | Como usuário, quero configurar alertas para receber notificações quando for hora de sair para o ponto de ônibus.                                                                                                               | Alta       |
| 2.2.2 | RF   | Como usuário, quero ser notificado automaticamente de interrupções no meu trajeto habitual para que eu possa buscar rotas alternativas.                                                                                        | Alta       |
| 2.2.3 | RF   | Como usuário, quero receber alertas de eventos especiais que possam impactar o transporte (ex.: maratonas, feiras) para planejar melhor minha viagem.                                                                          | Média      |
| 2.2.4 | RF   | Como usuário, quero receber notificações de superlotação para evitar pegar ônibus em horários de pico e conseguir um assento.                                                                                                  | Alta       |
| 2.3.1 | RF   | Como usuário, quero monitorar e ser notificado de atrasos e interrupções ou alterações em tempo real dos transportes públicos na minha rota para evitar confusão e garantir que meu trajeto seja cumprido.                     | Alta       |
| 3.1.1 | RF   | Como usuário, quero uma interface simples e intuitiva para inserir e visualizar minhas rotas sem dificuldade.                                                                                                                  | Alta       |
| 3.1.2 | RF   | Como usuário, quero que a interface seja personalizável (ex.: temas, tamanho da fonte) para melhor se adequar às minhas necessidades visuais.                                                                                  | Média      |
| 3.2.1 | RF   | Como usuário, quero poder acessar mapas e rotas offline para planejar minha viagem mesmo sem conexão à internet.                                                                                                               | Alta       |
| 3.2.2 | RF   | Como usuário, quero salvar rotas e horários para visualizá-los quando estiver offline, garantindo que eu possa usar o Moovit em áreas sem sinal.                                                                               | Média      |
| 3.3.1 | RF   | Como usuário, quero uma interface simplificada e intuitiva para a usabilidade mais responsiva do app sem confusão.                                                                                                             | Alta       |
| 4.1.1 | RF   | Como usuário, quero poder solicitar um serviço de ride-sharing (ex.: Uber) diretamente pelo Moovit quando não houver transporte público disponível.                                                                            | Alta       |
| 4.1.2 | RF   | Como usuário, quero ver uma comparação de custos entre o transporte público e opções de ride-sharing para decidir a melhor opção de viagem.                                                                                    | Alta       |
| 4.2.1 | RF   | Como usuário, quero integrar o Moovit com outros aplicativos de mapas (ex.: Google Maps) para ampliar as opções de navegação.                                                                                                  | Média      |
| 4.2.2 | RF   | Como usuário, quero compartilhar minha rota ou localização em tempo real com contatos para que saibam onde estou durante a viagem.                                                                                             | Média      |
| 4.3.1 | RF   | Como usuário, quero pagar diretamente minhas passagens de transporte público via aplicativo para simplificar minhas transações diárias.                                                                                        | Alta       |
| 5.1.1 | RF   | Como usuário, quero poder enviar feedback sobre minha experiência de viagem para ajudar a melhorar o serviço.                                                                                                                  | Média      |
| 5.1.2 | RF   | Como usuário, quero ver avaliações de outros usuários sobre as condições das linhas ou estações para tomar decisões mais informadas.                                                                                           | Média      |
| 5.2.1 | RF   | Como usuário, quero reportar problemas (ex.: atrasos, acidentes) para que outros usuários sejam informados.                                                                                                                    | Alta       |
| 5.2.2 | RF   | Como usuário, quero ver informações em tempo real reportadas por outros usuários para ter um panorama mais preciso da situação do transporte.                                                                                  | Alta       |
| 5.3.1 | RF   | Como gerente de produto, desejo expandir a cobertura do Moovit para incluir mais cidades em regiões menos servidas para aumentar a base de usuários.                                                                           | Média      |
| 5.4.1 | RF   | Como gerente de produto, quero garantir que os usuários tenham acesso a rotas otimizadas durante grandes eventos, para melhorar a mobilidade dos participantes.                                                                | Média      |
| 5.5.1 | RF   | Como usuário, desejo poder usar o aplicativo em mais idiomas, especialmente em regiões onde a língua oficial ainda não é suportada.                                                                                            | Média      |
| 6.1.1 | RF   | Como usuário, quero acessar bicicletas e patinetes compartilhados diretamente no app para planejar minhas viagens de maneira integrada.                                                                                        | Alta       |
| 7.1.1 | RF   | Como usuário, quero encontrar a rota mais eficiente, econômica e segura para chegar ao meu destino a tempo e evitar áreas inseguras.                                                                                           | Média      |
| 7.2.1 | RF   | Como usuário, quero ver opções de transporte acessível que me permitam evitar longas caminhadas.                                                                                                                               | Alta       |
| 7.3.1 | RF   | Como usuário, quero receber sugestões de rotas alternativas rapidamente em caso de interrupções no serviço, podendo aconselhar ao usuário descer do ônibus em que está para esperar por outro que melhore sua rota e conforto. | Média      |
| 7.4.1 | RF   | Como usuário, quero orientações detalhadas para encontrar pontos turísticos e restaurantes sem me perder.                                                                                                                      | Média      |
| 7.5.1 | RF   | Como usuário, quero ferramentas mais eficientes para mapear e atualizar informações de transporte público na minha cidade e maiores benefícios por assinaturas.                                                                | Alta       |


## Sprint Planning

| Requisito | Feature                                                | Sprint | Pontos de Prioridade |
|-----------|--------------------------------------------------------|--------|----------------------|
| 1.1.1     | Seleção de Rota                                        | 1      | 9                    |
| 1.1.2     | Seleção de Rota                                        | 1      | 8                    |
| 1.1.3     | Seleção de Rota                                        | 1      | 8                    |
| 1.2.1     | Personalização de Rota                                 | 1      | 8                    |
| 1.2.2     | Personalização de Rota                                 | 1      | 9                    |
| 1.2.3     | Personalização de Rota                                 | 1      | 9                    |
| 2.1.1     | Monitoramento de Transporte                            | 2      | 9                    |
| 2.1.2     | Monitoramento de Transporte                            | 2      | 6                    |
| 2.1.3     | Monitoramento de Transporte                            | 2      | 9                    |
| 5.5.1     | Suporte a Idiomas Adicionais                           | 2      | 5                    |
| 7.1.1     | Rotas Rápidas, Econômicas e Seguras                    | 2      | 5                    |
| 2.2.1     | Alertas e Notificações                                 | 3      | 6                    |
| 2.2.2     | Alertas e Notificações                                 | 3      | 9                    |
| 2.2.3     | Alertas e Notificações                                 | 3      | 4                    |
| 2.2.4     | Alertas e Notificações                                 | 3      | 4                    |
| 2.3.1     | Monitoramento de Atrasos e Mudanças                    | 3      | 6                    |
| 3.2.1     | Modo Offline                                           | 3      | 8                    |
| 3.2.2     | Modo Offline                                           | 3      | 8                    |
| 3.3.1     | Interface Simples para Idosos                          | 4      | 6                    |
| 3.1.1     | Interface Intuitiva                                    | 4      | 4                    |
| 4.1.1     | Integração com Serviços de Ride-Sharing                | 4      | 5                    |
| 4.1.2     | Integração com Serviços de Ride-Sharing                | 4      | 5                    |
| 4.2.1     | Integração com Mapas                                   | 4      | 7                    |
| 4.2.2     | Integração com Mapas                                   | 4      | 9                    |
| 4.3.1     | Integração com Pagamentos Digitais                     | 5      | 3                    |
| 7.3.1     | Sugestões de Rotas Alternativas ou Troca de Ônibus     | 5      | 8                    |
| 5.1.2     | Coleta de Feedback                                     | 5      | 7                    |
| 5.2.1     | Comunidade e Colaboração                               | 5      | 6                    |
| 5.3.1     | Expansão de Cobertura Geográfica                       | 5      | 7                    |
| 5.4.1     | Suporte Multimodal para Grandes Eventos                | 5      | 9                    |
| 5.1.1     | Coleta de Feedback                                     | 5      | 7                    |
| 6.1.1     | Implementação de Suporte à Micromobilidade             | 6      | 6                    |
| 7.2.1     | Opções de Transporte Acessível                         | 6      | 3                    |
| 7.4.1     | Orientação Passo a Passo com Pontos Turísticos         | 6      | 3                    |
| 7.5.1     | Aprimoramento da Experiência de Uso para Mooviters     | 6      | 5                    |
| 5.2.2     | Comunidade e Colaboração                               | 6      | 6                    |
| 3.1.2     | Interface Intuitiva                                    | 6      | 6                    |


## MVP1

| Requisito | Feature                                                | Sprint | Pontos de Prioridade |
|-----------|--------------------------------------------------------|--------|----------------------|
| 1.1.1     | Seleção de Rota                                        | 1      | 9                    |
| 1.1.2     | Seleção de Rota                                        | 1      | 8                    |
| 1.1.3     | Seleção de Rota                                        | 1      | 8                    |
| 1.2.1     | Personalização de Rota                                 | 1      | 8                    |
| 1.2.2     | Personalização de Rota                                 | 1      | 9                    |
| 1.2.3     | Personalização de Rota                                 | 1      | 9                    |
| 2.1.1     | Monitoramento de Transporte                            | 2      | 9                    |
| 2.1.2     | Monitoramento de Transporte                            | 2      | 6                    |
| 2.1.3     | Monitoramento de Transporte                            | 2      | 9                    |
| 5.5.1     | Suporte a Idiomas Adicionais                           | 2      | 5                    |
| 7.1.1     | Rotas Rápidas, Econômicas e Seguras                    | 2      | 5                    |

### Histórico de Versões

|Autor | Versão          |Data | Descrição |
|-----------------------------------------------|----------------------------------|-----------|------------------------------------------------|
| Guilherme Coelho                              | [1.0](../Agil/versao1Backlog.md) |20/08/2024 | Adição da primeira versão do Backlog           |
|[Victor Hugo](https://github.com/ViictorHugoo) | 2.0                              |21/08/2024 | Atualização do Backlog + sprint planning + mvp1|