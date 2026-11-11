# Meu Kit de IA

Desafio de Projeto da [DIO](https://dio.me): monte o seu kit de IA para o dia a dia e delegue uma tarefa real, com você no comando.

O kit foi criado pelo Expert Bruno Lima com os prompts, templates, checklists e skills usados nas Aulas. Ele não é uma apostila: abra a pasta que resolve o seu problema, copie o modelo, adapte e use.

**Copie → adapte → teste → confira → melhore**

## Como Fazer o Desafio

Você não precisa instalar nada nem saber programar. Tudo acontece no navegador.

1. Clique em **Use this template**, depois em **Create a new repository**. Dê um nome simples, como `meu-kit-de-ia`, deixe **Public** e confirme.
2. Siga os passos abaixo com uma tarefa real da sua semana.
3. Preencha a seção [Minha Entrega](#minha-entrega) da sua cópia e entregue o link dela na DIO.

## Os Passos

1. **Escolha uma tarefa real.** Comece pelo trabalho que se repete na sua semana, como preparar uma reunião ou montar um relatório, e não pela ferramenta.
2. **Pegue um modelo.** Abra a pasta do kit que combina com a sua tarefa. Cada modelo tem um botão de copiar no canto.
3. **Adapte.** Troque o que está entre colchetes pelo seu contexto, objetivo, dados, limites e formato.
4. **Teste.** A primeira resposta é um ponto de partida. Ajuste até funcionar para a sua realidade.
5. **Delegue.** Com o [template de delegação](02-templates/03-delegacao.md), entregue a tarefa à IA. Peça o plano antes de ela começar, acompanhe e valide o resultado.
6. **Confira.** Provável não é o mesmo que verdadeiro. Revise com o [Pare, Confira, Use](03-checklists/01-pare-confira-use.md) antes de usar.

## O Que Tem no Kit

| Pasta | Para que serve |
|---|---|
| [01-prompts](01-prompts) | Pedidos prontos para adaptar: escrita, comunicação, pesquisa, comparação e preparação de reuniões |
| [02-templates](02-templates) | Estruturas para preencher: bom pedido, pesquisa e decisão, e delegação |
| [03-checklists](03-checklists) | Revisão de respostas, de textos e de tarefas delegadas |
| [04-skills](04-skills) | Como criar uma skill, e a Skill Preparador de Reuniões usada nas Aulas |
| [05-delegacao-e-automacao](05-delegacao-e-automacao) | Gatilhos de automação, supervisão e checkpoints |

## Os Frameworks das Aulas

- **Bom pedido:** contexto + instrução + objetivo + formato. Quanto menos a IA precisa adivinhar, melhor você consegue avaliar a resposta.
- **Pesquisa e decisão:** pergunta → pesquisa → critérios → comparação → você. Peça fontes quando precisar de informação externa. A decisão final é sua.
- **Segurança:** pare → confira → use. Valide fatos, números, datas, fontes e contexto.
- **Atalhos reutilizáveis:** criar → testar → ajustar → salvar. Separe as instruções fixas das informações que mudam a cada uso.
- **Delegação:** objetivo + contexto + recursos + limites + sucesso. Autonomia funciona melhor quando o resultado esperado está claro.
- **Supervisão:** definir → delegar → acompanhar → validar. Em tarefas maiores, confira o plano, acompanhe os checkpoints e valide o resultado.

> A IA pode ajudar você a escrever, pesquisar, organizar e executar. A responsabilidade pelo resultado continua sendo sua.

---

## Minha Entrega

Na sua cópia, abra este README, clique no lápis (**Edit this file**) e role até aqui. Troque cada frase em itálico pelo que você fez e cole o texto dentro dos blocos já prontos. Para pôr um print, é só colar a imagem com Ctrl+V. No fim, clique em **Commit changes**.

Nada de e-mail, nome de cliente, dado da empresa, senha ou informação pessoal nos textos e nos prints.

### Minha Tarefa Real
<img width="515" height="231" alt="image" src="https://github.com/user-attachments/assets/3ec92ca5-21b3-40dc-b8fd-ab80513627c1" />

Geração automática de escala dos colaboradores

### Meus Atalhos

Utilizei modelo próprio de prompt para a criação de aplicações web e mobile.

```text
CONTEXTO
[Informações e legislação vigente aplicada sobre as diferentes escalas de trabalho (6x1, 5x2, 12x36, 24x72).]

INSTRUÇÃO
[Desenvolver uma página web localhost para aplicar as regras para criação da aplicação de escalas.]

OBJETIVO
[Reduzir o tempo para a criação de escalas, minimizar ao máximos os erros que prejudicam o colaborador e o RH da empresa e que podem levar a aplicação de medidas administrativas.]

FORMATO
[Página HTML+JS+CSS rodando localmente sem dependência interna ou externa de serviços.]
```

```text
Cole aqui o seu segundo atalho, já adaptado.
```

### Minha Delegação

```text
Cole aqui o pedido que você entregou à IA, com objetivo, contexto, recursos, limites e sucesso.

Baseado nas informações referentes a escala 6x1 de trabalho presente na imagem.
- O colaborador Fábio trabalha 2 domingos no mês e folga dois domingos.
- Temos a folga dupla que no caso do Fábio ocorre após trabalhar sem ter folga na semana
- Após a folga dupla ira folga novamente após 6 dias e trabalhará o domingo e também irá trabalhar o próximo domingo e folga no próximo dia.
- Esta escala e quinzenal
- Identificar quando o mês for de 31 e 29 dias para adequação.
- Permitir marcações manuais dos dias de folga.
- Quando o dia da folga coincidir com feriado alertar sobre a folga
- Identificar que sempre deve ter um colaborador no horário das 6 da manhã.
- Identificar que sempre deve ter um colaborador no horário das 14 da tarde.
- Utilizar HTML+JS+CSS para compor o layout de tela.
```

### O Plano da IA

Neste primeiro momento informações reais foram utilizadas para uma melhor assertividade da IA, que depois foram ajustadas para limpar informações acerca de colaboradores para não contaminar o código gerado e nem expor informações sensíveis.

1. Funcionalidades implementadas
- Geração automática da escala mensal.
- Identificação automática de meses com 28, 29, 30 e 31 dias.
- Ciclo quinzenal configurado para Fábio.
- Escala 6x1 para Jader e Maycon.
- Configuração dos horários de entrada e saída.
- Alteração manual das folgas.
- Marcação de folga dupla, PEC, férias e folga normal.
- Cadastro manual de feriados.
- Destaque de folgas coincidentes com feriados.
- Identificação dos domingos trabalhados por Fábio.
- Exportação da escala para CSV.
- Impressão da escala.
2. Validações automáticas
A aplicação verifica três condições importantes:
Regra	Validação
Domingos do Fábio	Meta de 2 domingos trabalhados
Cobertura das 06h	Pelo menos um colaborador
Cobertura das 14h	Pelo menos um colaborador
Folga em feriado	Emissão de alerta
Domingos consecutivos	Verificação da folga posterior

3. Regra de funcionamento do Fábio
Implementei inicialmente este ciclo-base de 14 dias:
Período	Situação
Dias 1 e 2	Folga dupla
Dias 3 a 8	Trabalho
Dia 9	Folga
Dias 10 a 14	Trabalho

### O Resultado

Motor de geração de escala configurável, sem regras vinculadas a nomes.
Ciclos de trabalho e folga independentes por colaborador.
Preservação da sequência quinzenal configurada.
Conferência dos domingos trabalhados e de folga.
Verificação da cobertura dos horários de 06h e 14h.
Ajustes manuais pelo gestor quando necessário.
Salvamento automático e histórico por mês.
Exportação CSV e impressão.
Restauração da escala originalmente gerada.
Aplicação autocontida.
Sem necessidade de servidor ou internet.
Armazenamento local por mês.
Feriados persistentes.
Configuração individual dos colaboradores.
Edição manual e exportação CSV.

### Como Foi para Você

O resulto e bastante satisfatório, mas é preciso revisar sempre o que foi entregue baseado no que foi pedido
e assim ajustar conforme as necessidades e evoluções futuras do projeto.
