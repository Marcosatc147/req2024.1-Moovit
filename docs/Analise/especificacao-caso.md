# Inspeção da Especificação dos Casos de Uso


Utilizando o método da inspeção para a análise dos Casos de Uso, prática comum na Engenharia de Requisitos, utilizada para garantir que os casos de uso sejam completos, corretos, consistentes e compreensíveis. Essa atividade faz parte de um processo de verificação e validação dos requisitos funcionais do sistema.


O processo de inspeção é essencial para garantir que os casos de uso possam ser usados como uma base confiável para o desenvolvimento, testes e outras atividades dentro do ciclo de vida do software.


Aqui estão os passos e aspectos utilizados no formato de perguntas ao fazer a análise de inspeção de casos de uso, com o intuito de respondê-las.

1. Está definido de forma clara e objetiva os critérios de inspeção? 
2. O Fluxo de Eventos possui um Fluxo Principal conciso?
3. As Exceções e Fluxos Alternativos foram documentados e tem uma sequência lógica?
4. As Pré-condições e Pós-condições estão bem definidas?
5. Está consistente com os demais requisitos funcionais e não funcionais?
6. Atores e Cenários são identificáveis e entendidos por inexperientes?

Ao analisar todas as especificações de casos de uso, de acordo com as respostas das perguntas acima, marcamos na tabela de avaliação com um "X" aqueles que são atendidos.

|Caso de Uso|1|2|3|4|5|6|
|---|---|---|---|---|---|--|
|UC001|X|X|X|X|X|X|
|UC002||X|X||X|X|
|UC008|X|X||X|X|X|
|UC009|X|X||X|X|X|
|Diagrama|X|X||||X|

## Conclusão

1. (UC002) Esclarecer o papel do Mooviter como ator, oque diferencia dele para um usuário? Porque somente ele é o ator e o usuário também não se aplica?

3. (UC008) Não documentado. Poderia aproveitar o Pós-Condição inserido para incrementar um Fluxo Alternativo, inclusive faria mais sentido.

3. (UC009) Não documentado.

4. (UC002) Como o mooviter terá essas permissões de editar e atualizar as novas informações de transportes? Qual a diferença entre usuário e moviter? O que é necessário para me tornar um mooviter?

5. (Todos) Referências aos termos do léxico encontradas na aba “Análise de Protocolo e Baseline”.



| Autor  | Versão          |Data|
|-------|-----------------|----|
|Guilherme|1ª   |09/09/2024|