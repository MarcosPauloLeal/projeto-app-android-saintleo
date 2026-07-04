# AeroLog - Diário de Bordo Digital

Projeto de aplicativo Android desenvolvido na disciplina Desenvolvimento de Aplicativos (COM-437PT-AVBR1) da Saint Leo University, sob orientação do Professor Gesiel Rios Lopes. Este documento reúne o rascunho inicial do projeto, que será construído de forma incremental ao longo dos módulos do curso.

## Descrição do projeto

O AeroLog é um diário de bordo digital voltado para pilotos e estudantes de pilotagem. Ele permite registrar cada voo realizado, com dados como data, aeronave, aeroporto de origem, aeroporto de destino e duração, e acompanhar de forma automática o total de horas voadas. O nome une a referência à aviação e a palavra log, que remete ao registro de atividades.

## Problema que o aplicativo pretende resolver

O registro das horas de voo é uma exigência importante na aviação, pois serve de base para a obtenção e a manutenção de licenças e habilitações. Ainda assim, muitos pilotos em formação anotam tudo em cadernetas de papel, um método frágil, que pode ser perdido ou danificado, dificulta a soma das horas e não oferece uma visão consolidada do histórico. O AeroLog digitaliza esse registro, guarda os dados de forma segura no aparelho e calcula os totais automaticamente.

## Plataforma escolhida

A plataforma escolhida é o Android. O sistema é o mais usado no mundo e abrange aparelhos de todas as faixas de preço, o que amplia o alcance entre estudantes de aviação. O desenvolvimento será feito no MIT App Inventor, que gera aplicativos Android e favorece o aprendizado ao longo do curso. Por ser um projeto de uso pessoal e que funciona sem conexão, não há necessidade, neste momento, de versões para outras plataformas.

## Interface do usuário e interface do administrador

A interface do usuário é simples e direta. A tela inicial funciona como um menu com poucas opções, que levam ao registro de um novo voo, à lista de voos já registrados e ao resumo de horas. A tela de registro concentra os campos essenciais em um único formulário, e a tela de histórico mostra os voos em lista, do mais recente ao mais antigo.

Como o AeroLog é um aplicativo de uso individual, não há um administrador externo. O papel administrativo fica reservado a uma área de gerenciamento das aeronaves, na qual o próprio usuário cadastra e mantém a lista de aviões que costuma pilotar, separando a manutenção desses dados de referência do uso cotidiano de registrar voos.

## Principais funcionalidades

- Registro de um voo com data, aeronave, origem, destino e duração
- Armazenamento dos registros no próprio aparelho
- Histórico de voos apresentado em lista
- Cálculo automático do total de horas voadas
- Gerenciamento da lista de aeronaves que alimenta o formulário de registro

Nos módulos seguintes, essas funcionalidades serão ampliadas com recursos como filtros por período ou por aeronave, resumo de horas por tipo de avião e, mais adiante, exportação do histórico, sempre mantendo a simplicidade como princípio.

## Design das telas

O esquema das telas principais está registrado no arquivo `wireframes.png`, incluído neste repositório. Ele apresenta, em baixa fidelidade, a tela inicial com o menu, a tela de registro de voo com o formulário, a tela de histórico com a lista de voos e a tela de resumo com o total de horas. Os wireframes definem a organização dos elementos e o fluxo entre as telas e serão refinados nas próximas etapas.

## Autor

Marcos Paulo Leal Silva
