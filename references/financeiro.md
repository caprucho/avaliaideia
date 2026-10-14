# Modelo financeiro para decisões de viabilidade

Use somente as partes materiais ao modelo de negócio. Valores ilustrativos devem ser identificados como simulação, nunca como preços ou resultados de mercado. Identifique moeda, competência, unidade, fonte e tratamento dos impostos. Não misture valores nominais/reais nem taxas mensais/anuais.

## Premissas e horizonte

Separe dados observados de hipóteses. Para parâmetros críticos, registre valor/faixa, justificativa e como validar. Horizonte deve cobrir implantação, maturação, sazonalidade e compromissos relevantes. Modele caixa mensal quando recebimentos, estoque, investimento ou prazo até equilíbrio forem materiais; acrescente visão semanal se o aperto de caixa justificar.

Distinga unidades vendidas, clientes, pedidos, transações, assinantes e horas faturáveis. Em marketplaces, GMV não é receita da plataforma; receita é a parcela efetivamente apropriada. Não inclua impostos repassados como margem.

## Investimento e custos

**Inicial:** pesquisa/piloto, abertura/licenças, projeto, obra, caução, equipamentos, instalação, desenvolvimento, migração, dados, estoque inicial, treinamento e lançamento. Identifique gastos recuperáveis, ativos revendáveis e custos irrecuperáveis. Contingência precisa de base ou faixa explícita.

**Fixos e semifixos:** aluguel, pessoal e encargos, pró-labore, contabilidade, seguros, ferramentas, infraestrutura mínima, manutenção, contratos e despesas administrativas. Considere degraus de custo ao exceder capacidade.

**Variáveis:** insumos/CMV, embalagem, frete subsidiado, comissões, taxas de pagamento, impostos sobre venda conforme regime verificado, consumo por uso, atendimento por unidade, perdas, garantia, retrabalho e reembolsos. Não duplique gastos já descontados da receita.

**Trabalho do dono:** mostre caixa sem desembolso e resultado econômico com remuneração compatível com horas/função. Se não houver referência, use faixa assumida. Lucro antes da remuneração do dono não é lucro disponível para investidor passivo.

**Capital de giro:** considere prazo e saldo de estoque, contas a receber, fornecedores, antecipações, inadimplência e reserva operacional. Negócio lucrativo pode quebrar por descasamento de caixa.

## Contas essenciais

Declare a convenção de receita usada e evite deduzir duas vezes taxas/impostos.

- Receita do período = volume × preço médio realizado, ajustada por descontos/devoluções aplicáveis. Para múltiplos produtos, some por produto e explicite o mix.
- Margem de contribuição unitária (MCu) = receita unitária na convenção adotada − custos/despesas variáveis unitários ainda não descontados.
- Margem de contribuição percentual = contribuição total ÷ receita na mesma convenção.
- Resultado operacional gerencial = contribuição total − custos fixos/semifixos; explicite pró-labore, depreciação e demais itens incluídos/excluídos.
- Ponto de equilíbrio em unidades = custos fixos ÷ MCu, se MCu > 0. Arredonde para unidade vendável e confronte com capacidade/demanda.
- Ponto de equilíbrio em receita = custos fixos ÷ margem de contribuição percentual positiva. Em mix, use composição defensável e teste mudanças.
- Volume para meta de resultado = (custos fixos + meta de resultado) ÷ MCu, sem duplicar remuneração do dono. Declare se a meta é antes/depois de tributos e financiamento.
- Caixa final = caixa inicial + entradas efetivamente recebidas − saídas efetivamente pagas. Separe operação, investimento e financiamento.

MCu nula/negativa não produz ponto de equilíbrio finito pela fórmula; aumentar volume não resolve por si. Economias de escala ou reajuste exigem evidência de novo custo/preço e demanda.

## Aquisição, retenção e capacidade

- CAC = despesas de aquisição atribuíveis ÷ novos clientes adquiridos no período/coorte adequado. Distingua CAC pago de CAC completo, incluindo vendas, ferramentas e trabalho. Não divida por leads nem por todos os clientes históricos.
- Payback de CAC = tempo até a contribuição acumulada da coorte recuperar aquisição; considere implantação, inadimplência, churn e ramp-up. Fórmula simplificada só com contribuição mensal estável e premissas explícitas.
- LTV deve refletir contribuição recuperável por cliente/coorte, não faturamento. Aproximação contribuição mensal ÷ churn mensal só serve sob hipóteses fortes de estabilidade; não aplique a negócio novo sem ressalva nem use churn zero para produzir infinito. Não imponha relação LTV/CAC universal como prova de viabilidade.
- Capacidade de serviço = horas disponíveis para entrega ÷ horas por atendimento, descontando vendas, administração, pausas e retrabalho. Em operação física, considerar estações, ciclos, turnos, ocupação e gargalo limitante.
- O faturamento projetado deve respeitar volume captável, ciclo de vendas, capacidade e capital de giro. Em recorrência, modele clientes iniciais + aquisições − cancelamentos; use coortes quando churn e maturação alterarem a conclusão.

## Caixa, retorno e cenários

Monte cenários conservador, base e favorável alterando fatores causais: aquisição, conversão, preço, frequência, retenção, ocupação, perdas, custos, prazo de implantação e recebimento. Não aplique apenas +/-20% em tudo. Evite combinar melhor demanda com custos incompatíveis com o atendimento.

Calcule o maior déficit acumulado antes do financiamento e a reserva necessária. Separe investimento inicial de despesas operacionais/estoque já modeladas para não duplicar necessidade de capital. Aporte e empréstimo aumentam caixa, não lucro. Inclua juros, amortização e condições quando financiamento for necessário.

Payback do projeto usa fluxo de caixa acumulado após investimento, com horizonte e inclusão/exclusão da remuneração do dono explícitos. Não divida investimento por lucro de um mês maduro se houver ramp-up. Se não ocorrer no horizonte, diga isso. Se o fluxo voltar a negativo depois de recuperar o investimento, mostre a necessidade posterior.

VPL/TIR só quando o horizonte, montante e qualidade das premissas justificarem. Declare taxa de desconto e fundamentação; compare risco, liquidez e trabalho com alternativa compatível. TIR pode ser ambígua com múltiplas mudanças de sinal; não é garantia de retorno.

Faça sensibilidades sobre as variáveis decisivas e calcule os limites úteis: preço mínimo, custo máximo, volume/ocupação necessários, CAC suportável no horizonte e atraso máximo antes de acabar o caixa. Diferencie limiar matemático de alvo comercial seguro.

Quando investimento for parcialmente irreversível, acrescente alternativas por etapas: piloto, adiamento, expansão e encerramento, com custos, informação obtida e recuperação de ativos. Considere multas, desmontagem, rescisão e outras obrigações de saída. A lógica de flexibilidade de Dixit e Pindyck, resumida em [base-metodologica.md](base-metodologica.md), não exige modelagem matemática de opções em todo pequeno negócio.

Para uma próxima decisão, compare benefícios e custos futuros incrementais: despesas passadas irrecuperáveis não são justificativa para continuar. Não as apague do retorno histórico total do projeto. Um teste informativo vale se puder alterar uma decisão e seu custo couber na exposição aceitável; sem probabilidades defensáveis, apresente condições e faixas, sem inventar valor esperado monetário da informação.

## Revisão antes do parecer

- Receita não foi confundida com lucro, GMV ou dinheiro recebido?
- Investimentos, depreciação, estoque e financiamento estão no lugar correto, sem duplicação?
- Pró-labore e horas não remuneradas estão visíveis? A meta de renda do usuário foi considerada?
- Tributos/taxas têm base verificável ou hipótese explicitamente pendente?
- Cenários respeitam capacidade, sazonalidade, ciclo de venda e caixa?
- Métricas recorrentes usam períodos compatíveis e não inventam retenção?
- Os números fecham e podem ser recalculados a partir das premissas apresentadas?
- O negócio continua aceitável sob premissas conservadoras plausíveis? Se não, qual exposição e evidência seriam necessárias para aceitar o risco?
