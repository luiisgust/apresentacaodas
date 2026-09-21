# Agenda Escolar — DAS na prática

Abra `index.html` com Chrome, Edge ou Firefox. Não precisa instalar programas, criar conta ou conectar à internet para usar a agenda. Os links de referências e do vídeo precisam de internet.

## Funcionalidades

- Cadastro de tarefas com título obrigatório.
- Disciplina e prazo opcionais nos ciclos 2 e 3.
- Ordenação por prazo, com itens sem data no final.
- Conclusão e reabertura de tarefas.
- Filtros combinados por disciplina e situação no ciclo 3.
- Exclusão com opção de desfazer a última exclusão durante a sessão.
- Armazenamento local no navegador e tarefas fictícias para demonstração.
- Layout adaptado a computador e celular.

## Apresentação em aula

1. Abra o projeto e clique em **Adicionar tarefas de exemplo**.
2. Mostre **01 · Registrar**: primeira hipótese, cadastrar e concluir tarefas.
3. Relate o feedback simulado “Não vejo o que vence primeiro”.
4. Mostre **02 · Organizar**: disciplina, data e ordenação.
5. Relate o feedback simulado “Quero ver só as pendentes de Matemática”.
6. Mostre **03 · Filtrar**: combine disciplina e situação.
7. Conclua uma tarefa e recarregue a página para demonstrar a persistência.
8. Explique a relação **especular → colaborar → aprender → ajustar a próxima entrega**.

Os três ciclos são demonstrações de evolução do produto e compartilham os mesmos registros. Selecionar um ciclo anterior não apaga datas ou disciplinas. Os feedbacks são fictícios: não foram realizados testes com alunos reais. A implementação foi construída como protótipo educacional; a sequência representa um projeto hipotético conduzido com DAS.

## Plano proposto

Missão: reunir atividades escolares e facilitar o acompanhamento de prazos.

Equipe hipotética: três integrantes com trabalho compartilhado de interface, desenvolvimento e testes, além de cinco colegas convidados para avaliar. Duração proposta: três ciclos de uma semana, escolhida para este exemplo; não é uma duração obrigatória do DAS.

| Ciclo | Hipótese | Entrega | Avaliação proposta | Adaptação |
|---|---|---|---|---|
| 1 | Uma lista será suficiente | Cadastro, lista, conclusão | Colega registra atividade sem ajuda? | Incluir prazos |
| 2 | Datas facilitam priorização | Disciplina, prazo, ordenação | Colega encontra a próxima entrega? | Incluir filtros |
| 3 | Filtros facilitam consulta | Disciplina + situação | Colega encontra tarefas pendentes de uma matéria? | Corrigir falhas observadas |

O plano prevê testes contínuos e revisão ao final de cada ciclo. Critérios técnicos: impedir título vazio; manter tarefas depois de recarregar; ordenar datas; combinar filtros; concluir e reabrir; excluir e desfazer. Critérios com usuários são propostas, não resultados medidos.

## Limitações

Os dados ficam apenas no armazenamento local deste navegador e dispositivo. Não há servidor, contas, sincronização, notificações ou backup automático. Limpar os dados do navegador pode apagar a agenda. O comportamento de armazenamento em arquivos locais depende do navegador; use sempre o mesmo navegador e arquivo. Se o armazenamento estiver bloqueado ou os dados salvos forem inválidos, a página avisa e opera temporariamente em memória, sem sobrescrever os dados anteriores. Evite editar simultaneamente em várias abas.

## Fontes

- Highsmith, Jim. *Agile Software Development Ecosystems*, capítulo 23: https://users.exa.unicen.edu.ar/catedras/agilem/cap23asd.pdf
- Manifesto Ágil: https://agilemanifesto.org/iso/ptbr/manifesto.html
- Vídeo complementar: IRONTEC informática, resumo DAS/ASD, 6min06: https://www.youtube.com/watch?v=q0Bm9uFS90o

O projeto é um exemplo didático original. As fontes fundamentam a metodologia, não resultados de avaliação deste software.
