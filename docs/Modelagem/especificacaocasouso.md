# Especificação de Caso de Uso
Uma especificação de caso de uso é um documento que descreve, de forma detalhada, como um sistema interage com seus usuários (atores) para atingir um objetivo específico. Ela inclui o fluxo de eventos, condições iniciais, resultados esperados, e exceções.

## Modelo de especificação de caso de uso
- ID do Caso de Uso: Identificador do caso de uso, formatado como “UC000”
- Nome do Caso de Uso: Um título claro e objetivo que descreve a ação principal.
- Objetivo: O que o sistema deve alcançar com esse caso de uso.
- Atores: Quem interage com o sistema durante esse caso de uso.
- Pré-condições: Estado que deve ser verdadeiro antes do caso de uso iniciar.
- Fluxo Principal: Passos sequenciais que descrevem a interação principal entre o ator e o sistema.
- Fluxos Alternativos: Variações do fluxo principal para situações excepcionais ou alternativas.
- Pós-condições: Estado esperado após a execução bem-sucedida do caso de uso.
- Requisitos Associados: IDs de requisitos específicos que esse caso de uso cobre.

## Caso de Uso: Consultar Rotas de Transporte Público
- ID do Caso de Uso: UC001
- Nome do Caso de Uso: Consultar Rotas de Transporte Público.
- Objetivo: Permitir que o usuário consulte as rotas disponíveis para transporte público.
- Atores: Usuário.
- Pré-condições: O usuário deve ter acesso ao aplicativo Moovit e estar conectado à internet.
- Fluxo Principal:
O usuário acessa a função de consulta de rotas no aplicativo.
O sistema solicita o ponto de partida e destino.
O usuário insere as informações necessárias.
O sistema apresenta as rotas de transporte público disponíveis.
O usuário seleciona a rota desejada para visualizar mais detalhes.
- Fluxos Alternativos: Se o usuário não inserir o ponto de partida e destino, o sistema não prossegue.
- Pós-condições: O usuário visualiza as rotas disponíveis.
- Requisitos Associados: RF01, RF03, RF05, RF06.

## Caso de Uso: Planejamento de Viagem com Múltiplos Modos de Transporte
- ID do Caso de Uso: UC008
- Nome do Caso de Uso: Planejar Viagem com Múltiplos Modos de Transporte.
- Objetivo: Permitir que o usuário planeje sua viagem com múltiplos modos de transporte.
- Atores: Usuário.
- Pré-condições: O usuário deve ter acesso ao aplicativo Moovit e estar conectado à internet.
O usuário deve baixar o aplicativo externo de transporte.
- Fluxo Principal:
O usuário abre o aplicativo Moovit.
O usuário acessa a opção de planejamento de viagem.
O usuário insere o local de partida (ponto A) e o destino (ponto B).
O usuário utiliza a função de filtrar rotas para selecionar preferências, como evitar determinados modos de transporte ou priorizar rotas mais rápidas.
O sistema exibe uma lista de opções de rota, combinando diferentes modos de transporte, como ônibus, metrô e caminhada.
O usuário revisa as opções e seleciona a rota mais conveniente.
O sistema exibe as instruções detalhadas para cada etapa da viagem, incluindo horários, pontos de transferência, e estimativas de tempo de caminhada.
O usuário confirma a rota selecionada.
O usuário inicia a viagem utilizando as instruções fornecidas pelo sistema.

- Pós-condições: O usuário tem uma rota planejada detalhando cada etapa da viagem, incluindo horários e pontos de transferência.
O sistema sugere uma rota alternativa caso um dos modos de transporte esteja indisponível.

- Requisitos Associados: RF08, RF16, RF17

## Caso de Uso: Reportar um problema no transporte público
- ID do Caso de Uso: UC009
- Nome do Caso de Uso: Reportar um problema no transporte público
- Objetivo: Permitir que o usuário reporte, aos administradores, um problema no transporte público.
- Atores: Usuário, Moovit.
- Pré-condições: O usuário deve ter acesso ao aplicativo Moovit e estar conectado à internet.
A funcionalidade de reportar problemas deve estar habilitada e operacional.

- Fluxo Principal:
O usuário abre o aplicativo Moovit durante ou após a viagem.
O usuário acessa a opção de reportar um problema.
O usuário seleciona o tipo de problema que deseja reportar (ex.: atraso, superlotação, alteração de rota).
O usuário insere detalhes adicionais sobre o problema (ex.: horário, local) e, se possível, anexa uma foto.
O sistema recebe o report do usuário.
O sistema encaminha o reporte para os responsáveis pelo transporte público.
O sistema notifica outros usuários que utilizam o mesmo serviço sobre o problema relatado.

- Pós-condições: O problema reportado é recebido e encaminhado aos responsáveis, e outros usuários são notificados sobre o problema no transporte público.

- Requisitos Associados: RF09