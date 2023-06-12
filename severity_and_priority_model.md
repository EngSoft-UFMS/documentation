# Modelo de severidade e prioridade 

## Severidade do projeto
O grau de severidade é um conceito importante para avaliar a gravidade dos problemas, guiando a equipe para que apliquem os recursos de maneira eficiente. Ele desempenha um papel crucial no suporte e gereciamento de crises.

### Critérios de Severidade:

- Critical: um defeito que dificulta ou bloqueia completamente o produto ou recurso. Se o software travar, se tornar inutilizável ou incapaz de prosseguir, a issue deve ser classificada como critical.
- Major: qualquer recurso principal implementado que não esteja atendendo a seus requisitos e se comporte de maneira diferente do esperado.
- Minor: qualquer recurso implementado que se comporte de maneira diferente do esperado, mas que o impacto seja insignificante até certo ponto ou que não tenha um impacto importante no aplicativo.
- Enhancement: qualquer defeito cosmético, incluindo erros de ortografia, problemas de alinhamento ou letras maiúsculas e minúsculas.

### Tomada de decisão
Escolhemos esse formato de classificação de severidade porque ele abrange uma variedade de problemas que podem ocorrer em um projeto de software, desde falhas críticas até melhorias cosméticas. Isso permite uma classificação clara e uma priorização adequada das tarefas de correção e aprimoramento.

### Aplicação
Os títulos de severidade serão aplicados às issues do repositório do projeto, permitindo que a equipe identifique rapidamente a gravidade de cada problema e direcione seus esforços para as correções mais críticas ou melhorias necessárias.

### Exemplos
- Uma issue relatando que o software está travando completamente seria classificada como "Critical".
- Uma issue que descreve um recurso principal que não está funcionando corretamente seria classificada como "Major".
- Uma issue que relata um problema que afeta parcialmente a funcionalidade seria classificada como "Moderate".
- Uma issue que relata um problema cosmético ou de formatação seria classificada como "Enhancement".

## Prioridade do projeto
A priorização é essencial para gerenciar efetivamente as mudanças em um projeto de software. Ela envolve a classificação das tarefas de acordo com sua necessidade e urgência, permitindo que a equipe foque nas atividades mais relevantes e críticas.

### Critérios de Prioridade:
A priorização foi dividida em classificações representadas por notas, para as categorias de NECESSIDADE e URGÊNCIA dos problemas e funcionalidades envolvidas na aplicação. Sendo que para ambas as classificações, existe uma nota que a representa respectivamente, variando de 4 até 1, da mais urgente e necessária para a menos. 

Para a categoria de NECESSIDADE, seja ela a de corrigir um problema ou adicionar uma nova funcionalidade, as classificações variam entre:

- Extremamente necessário (4): problemas ou funcionalidades críticas que afetam diretamente a usabilidade ou funcionalidade essencial do software.
- Necessário (3): problemas ou funcionalidades importantes, mas com impacto menos crítico no uso do software.
- Otimização (2): melhorias que não afetam diretamente a funcionalidade principal, mas podem otimizar a experiência do usuário ou o desempenho do sistema.
- Incremento (1): melhorias cosméticas ou de baixa prioridade, que não têm um impacto significativo no uso do software.

Para a categoria de URGÊNCIA, a rapidez relacionada para a resolução do problema ou criação de uma nova funcionalidade se dispõe entre:

- Urgente (4): problemas ou funcionalidades que requerem uma ação imediata, devido ao seu impacto crítico ou riscos envolvidos.
- Assim que possível (3): problemas ou funcionalidades importantes, mas que podem aguardar um pouco mais para serem abordados.
- Pouco urgente (2): problemas ou funcionalidades que têm um impacto menor e podem ser resolvidos em um prazo mais flexível.
- Pode esperar (1): problemas ou funcionalidades com baixa urgência, que podem ser abordados posteriormente, quando recursos estiverem disponíveis.

![TabelaDeClassificacaoDasCategorias](https://github.com/EngSoft-UFMS/documentation/blob/main/images/Classificacoes%20das%20categorias.png)

### Tomada de decisão
Escolhemos esse formato de classificação de prioridade porque ele permite estabelecer uma ordem clara para as tarefas, com base na importância e urgência. Dessa forma, a equipe pode direcionar seus esforços para resolver os problemas críticos e implementar as funcionalidades necessárias de forma eficiente.

### Aplicação
Os títulos de prioridade serão aplicados às issues do repositório do projeto, juntamente com os títulos de severidade. Isso permitirá que a equipe tenha uma visão abrangente das prioridades de cada problema ou funcionalidade e possa planejar o agendamento das atividades de acordo. Além disso, a combinação das classificações de severidade e prioridade ajudará a determinar a abordagem adequada para cada tarefa.
 
### Exemplos
- Uma issue descrevendo um exercício com um erro grave na solução ou enunciado que afeta a compreensão ou execução correta seria classificada como "Extremamente necessário" e "Urgente".
- Uma issue descrevendo a necessidade de adicionar um exercício novo seria classificada como "Necessário" e "Assim que possível".
- Uma issue sugerindo uma otimização nos exercícios já existentes para melhorar a clareza ou eficiência da solução seria classificada como "Otimização" e "Pouco urgente".
- Uma issue propondo uma melhoria cosmética, como a padronização do formato dos arquivos ou a correção de pequenos erros gramaticais nos enunciados, seria classificada como "Incremento" e "Pode esperar".

![TabelaDeExemplos](https://github.com/EngSoft-UFMS/documentation/blob/main/images/Exemplo%20de%20aplicacao.png)
