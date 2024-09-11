# Análise dos Cenários
## Verificação:

### 1. Identificação de Domínios Comuns
Os cenários apresentados estão relacionados ao domínio de transporte público e serviços associados, mais especificamente no contexto de uso do aplicativo Moovit. As funcionalidades descritas nos cenários incluem:

- Consulta e Planejamento de Rotas: CN1, CN4, CN5, CN8.
- Interação com Outros Serviços de Mobilidade: CN2, CN4.
- Gerenciamento de Preferências e Informação: CN6, CN7, CN10, CN11.
- Assinaturas e Benefícios Premium: CN3, CN12.
- Relato e Atualização de Problemas: CN9, CN11.

### 2. Reutilização de Domínios e Estruturas

Ao verificar os requisitos, podemos identificar áreas onde os cenários compartilham funcionalidades ou informações que podem ser reutilizadas:

#### a. Reutilização de Recursos Comuns:

- `Conexão à internet, localização ativada, e o aplicativo Moovit instalado` são recursos comuns a quase todos os cenários. Em vez de repetir esses requisitos em cada cenário, eles poderiam ser definidos como requisitos globais ou pré-condições para o uso do sistema.
- `Interação com serviços externos` (como caronas pagas ou bicicletas compartilhadas em CN2 e CN4) pode ser encapsulada em uma funcionalidade genérica de integração com serviços de mobilidade, facilitando a adição de novos serviços no futuro.

#### b. Reutilização de Ações e Episódios:

- `Inserção de destino e apresentação de rotas:` A sequência de ações em CN1, CN4, CN5, e CN8 compartilha um fluxo comum de inserção de destino, cálculo de rota, e apresentação de resultados. Isso sugere que essa funcionalidade poderia ser centralizada e reutilizada em diferentes cenários.
- `Favoritar e salvar preferências`:` CN6 e CN12 têm funcionalidades relacionadas ao gerenciamento de preferências do usuário (favoritar linhas e assinar Moovit+). Essas ações poderiam ser abstraídas em um módulo comum de gerenciamento de preferências do usuário.

#### c. Reutilização de Regras e Restrições:

- `Atualização e precisão em tempo real:` A necessidade de informações atualizadas e precisas aparece repetidamente (CN1, CN2, CN5, CN7, CN8). Definir essa restrição como um requisito global para o sistema, ao invés de individualmente para cada cenário, ajudaria na consistência e clareza dos requisitos.
- `Manutenção de dados e verificação por Mooviters (CN11):` Esta funcionalidade poderia ser estendida e utilizada para validar dados em qualquer cenário onde a precisão das informações seja crítica.

### 3. Aplicação de Reutilização no Design
No design de um sistema, essa análise de reutilização poderia resultar em:

- `Módulos de serviços compartilhados:` Um módulo para gestão de integração de serviços externos (CN2, CN4), outro para cálculo e apresentação de rotas (CN1, CN4, CN5, CN8), e um para gerenciamento de preferências (CN6, CN12).
- `Modelagem de fluxos reutilizáveis:` Criar fluxos de uso que são reutilizados em múltiplos cenários, como o fluxo de inserção de destino e cálculo de rota.
- `Requisitos globais e pré-condições:` Estabelecer uma seção de requisitos globais no documento de requisitos, definindo pré-condições como "Conexão à internet" e "Localização ativada".

### 4. Revisão de Cenários Específicos
Aplicando as observações acima, a seguir alguns exemplos de como cenários específicos poderiam ser ajustados para melhor reutilização:

#### CN1 (Consulta de Rotas de Transporte Público)
- Recursos: Reduzir as especificações duplicadas, referindo-se ao requisito global de "Conexão à internet, localização ativada, Moovit instalado".
- Episódios: Clarificar que a "inserção de destino e apresentação de rotas" reutiliza o fluxo comum de cálculo de rotas definido em um módulo compartilhado.

#### CN4 (Integração com Serviços de Carona Paga)
- Episódios: Incorporar a integração com serviços de mobilidade externa como um caso específico de um módulo de integração genérico, que pode ser reutilizado em outros cenários (como CN2).

#### CN11 (Atualização de Informações de Transporte Público por um Mooviter)

- Restrição: Destacar que a "precisão das informações em tempo real" também se aplica a outros cenários e que as regras de validação de dados por Mooviters podem ser reutilizadas onde relevante.

## Validação

### Cenário CN1: Consulta de Rotas de Transporte Público

#### Pontos de Vista:
- **Usuário:** Deseja encontrar a rota mais eficiente.
- **Governo do Estado:** Deseja fornecer dados precisos e atualizados.
- **Operadora de Transporte Público:** Precisa garantir que as informações sejam precisas e atualizadas.
- **Desenvolvedor do Sistema:** Deve garantir a integração com os dados e uma interface amigável.

#### Avaliação:
- **Usuário:** Cenário atende às expectativas, fornecendo uma rota eficiente. No entanto, o usuário pode ficar frustrado se os dados não estiverem atualizados.
- **Governo do Estado:** Cenário contribui para o objetivo de melhorar a experiência do transporte público, mas depende da qualidade dos dados.
- **Operadora de Transporte Público:** Cenário não detalha como garantir a precisão dos dados, o que pode ser um problema.
- **Desenvolvedor do Sistema:** Precisa de mais detalhes sobre como integrar e atualizar dados em tempo real.

#### Sugestões:
- Adicionar detalhes sobre a atualização e validação dos dados.
- Incluir funcionalidades para o usuário verificar a atualização dos dados e reportar inconsistências.

### Cenário CN2: Utilização de Serviço de Bicicletas Compartilhadas

#### Pontos de Vista:
- **Usuário:** Quer saber a disponibilidade de bicicletas e como acessá-las.
- **Empresa de Bicicletas Compartilhadas:** Precisa garantir que os dados sobre a disponibilidade de bicicletas estejam corretos.
- **Desenvolvedor do Sistema:** Deve implementar a integração com o sistema de bicicletas e garantir a precisão das informações.

#### Avaliação:
- **Usuário:** Cenário atende às necessidades de encontrar e usar bicicletas compartilhadas, mas precisa de atualização precisa sobre a disponibilidade.
- **Empresa de Bicicletas:** Cenário deve garantir a precisão das informações fornecidas para não gerar frustração no usuário.
- **Desenvolvedor:** Deve assegurar que a integração e a interface estejam funcionando corretamente e atualizem as informações em tempo real.

#### Sugestões:
- Incluir detalhes sobre como o sistema lida com a atualização das informações sobre bicicletas.
- Adicionar um mecanismo de feedback para relatar problemas com a disponibilidade das bicicletas.

### Cenário CN3: Uso de Benefícios Premium no Moovit

#### Pontos de Vista:
- **Usuário:** Quer entender os benefícios do plano premium e pagar de forma segura.
- **Desenvolvedor do Sistema:** Deve garantir a integração segura com o sistema de pagamento e a funcionalidade do Moovit+.

#### Avaliação:
- **Usuário:** Cenário aborda bem a compra e utilização do pacote premium, mas deve garantir que o processo de pagamento seja seguro.
- **Desenvolvedor:** Precisa garantir que o sistema de pagamento funcione sem falhas e que as funcionalidades premium estejam claramente descritas.

#### Sugestões:
- Detalhar o processo de segurança do pagamento e como lidar com falhas no pagamento.

### Cenário CN4: Integração com Serviços de Carona Paga

#### Pontos de Vista:
- **Usuário:** Quer combinar transporte público com carona paga de forma eficiente.
- **Serviço de Carona Paga:** Deve garantir que a integração com o Moovit seja fluida e eficiente.
- **Desenvolvedor do Sistema:** Deve assegurar a integração técnica entre o Moovit e os serviços de carona paga.

#### Avaliação:
- **Usuário:** Cenário aborda bem a combinação de transporte público e carona paga, mas deve garantir a integração eficiente e a disponibilidade dos serviços de carona.
- **Serviço de Carona Paga:** Deve garantir a disponibilidade e a integração com o Moovit.
- **Desenvolvedor:** Precisa assegurar que a integração funcione sem problemas e que os usuários possam facilmente utilizar ambos os serviços.

#### Sugestões:
- Incluir detalhes sobre a integração com serviços de carona paga e como lidar com a indisponibilidade de carros.

### Cenário CN5: Procura por uma Linha de Ônibus Específica

#### Pontos de Vista:
- **Usuário:** Deseja encontrar informações sobre uma linha específica de ônibus.
- **Operadora de Transporte Público:** Precisa garantir que as informações estejam atualizadas.
- **Desenvolvedor do Sistema:** Deve implementar a funcionalidade de busca e garantir que as informações sejam precisas.

#### Avaliação
- **Usuário:** Cenário atende bem a necessidade de encontrar informações sobre uma linha específica.
- **Operadora de Transporte Público:** Deve garantir que as informações sobre horários e paradas estejam sempre atualizadas.
- **Desenvolvedor:** Precisa assegurar que a funcionalidade de busca funcione corretamente e que as informações sejam precisas.

#### Sugestões:
- Adicionar mecanismos para verificar a precisão dos horários e paradas e fornecer rotas alternativas em caso de alterações.

### Cenário CN6: Usuário Favorita Linhas de Transporte para Acesso Rápido

#### Pontos de Vista:
- **Usuário:** Quer acessar rapidamente suas linhas favoritas.
- **Desenvolvedor do Sistema:** Deve garantir que a funcionalidade de favoritos seja fácil de usar e atualize as informações em tempo real.

#### Avaliação:
- **Usuário:** Cenário atende bem à necessidade de acessar rapidamente linhas favoritas.
- **Desenvolvedor:** Precisa garantir que a funcionalidade de favoritos esteja bem implementada e que as informações sejam atualizadas em tempo real.

#### Sugestões:
- Incluir detalhes sobre como o sistema lida com mudanças nas linhas favoritas e atualiza as informações.

### Cenário CN7: Verificação da Proximidade de um Ônibus

#### Pontos de Vista:
- **Usuário:** Quer saber a localização e o tempo de chegada do ônibus.
- **Desenvolvedor do Sistema:** Deve garantir que a localização e o tempo de chegada sejam precisos e atualizados.

#### Avaliação:
- **Usuário:** Cenário atende bem à necessidade de verificar a proximidade do ônibus, mas deve garantir a precisão dos dados.
- **Desenvolvedor:** Precisa assegurar que a funcionalidade de rastreamento e a estimativa de chegada estejam corretas e atualizadas.

#### Sugestões:
- Adicionar mecanismos para lidar com falhas na obtenção da localização do ônibus e sugerir opções alternativas.

### Cenário CN8: Planejamento de Viagem com Múltiplos Modos de Transporte

#### Pontos de Vista:
- **Usuário:** Quer planejar uma viagem usando diferentes modos de transporte.
- **Desenvolvedor do Sistema:** Deve garantir que o planejamento multimodal funcione corretamente e forneça informações precisas.

#### Avaliação:
- **Usuário:** Cenário atende bem à necessidade de planejamento multimodal, mas deve garantir a precisão das informações sobre os diferentes modos de transporte.
- **Desenvolvedor:** Precisa assegurar que a funcionalidade de planejamento multimodal seja precisa e eficiente.

#### Sugestões:
- Detalhar como o sistema lida com a indisponibilidade de modos de transporte e sugere rotas alternativas.

### Cenário CN9: Usuário Reporta um Problema no Transporte Público

#### Pontos de Vista:
- **Usuário:** Quer relatar problemas encontrados durante o uso do transporte público.
- **Desenvolvedor do Sistema:** Deve garantir que a funcionalidade de reporte de problemas esteja funcionando e seja eficaz.

#### Avaliação:
- **Usuário:** Cenário atende bem à necessidade de reportar problemas, mas deve garantir que o sistema processe e encaminhe os relatórios eficientemente.
- **Desenvolvedor:** Precisa assegurar que a funcionalidade de reporte de problemas esteja bem implementada e funcione sem falhas.

#### Sugestões:
- Incluir detalhes sobre como o sistema lida com falhas no processamento de relatórios e sugere alternativas.

### Cenário CN10: Acesso a Notícias Relacionadas ao Transporte Público

#### Pontos de Vista:
- **Usuário:** Quer se manter informado sobre as últimas notícias e atualizações relacionadas ao transporte público.
- **Desenvolvedor do Sistema:** Deve garantir que a funcionalidade de notícias esteja atualizada e forneça informações relevantes.

#### Avaliação:
- **Usuário:** Cenário atende bem à necessidade de acessar notícias e atualizações, mas deve garantir a precisão e relevância das informações.
- **Desenvolvedor:** Precisa assegurar que as notícias sejam atualizadas e relevantes para o usuário.

#### Sugestões:
- Adicionar mecanismos para lidar com a falta de notícias e falhas na atualização das informações.

### Cenário CN11: Atualização de Informações de Transporte Público por um Mooviter

#### Pontos de Vista:
- **Mooviter:** Deve garantir que as informações sobre linhas de ônibus estejam atualizadas.
- **Desenvolvedor do Sistema:** Deve garantir que o processo de atualização seja seguro e eficiente.

#### Avaliação:
- **Mooviter:** Cenário aborda bem a necessidade de atualizar informações, mas deve garantir a precisão e a segurança das atualizações.
- **Desenvolvedor:** Precisa assegurar que o sistema permita atualizações seguras e que as informações sejam rapidamente refletidas no sistema.

#### Sugestões:
- Detalhar como o sistema lida com atualizações de dados e garantir a precisão e segurança do processo.

### Cenário CN12: Exibição de Mapas com Rotas de Transporte Público

#### Pontos de Vista:
- **Usuário:** Quer visualizar rotas de transporte público de forma clara e precisa.
- **Desenvolvedor do Sistema:** Deve garantir que a exibição dos mapas e rotas seja precisa e fácil de entender.

#### Avaliação:
- **Usuário:** Cenário atende bem à necessidade de visualizar rotas, mas deve garantir a clareza e a precisão dos mapas.
- **Desenvolvedor:** Precisa assegurar que a exibição de mapas e rotas seja eficaz e sem erros.

#### Sugestões:
- Adicionar funcionalidades para lidar com a visualização de rotas alternativas e garantir que os mapas sejam atualizados com precisão.

| Autor  | Versão          |Data|
|-------|-----------------|----|
|[Pedro Paulo](https://github.com/Pedrin0030)|1ª   |08/09/2024|