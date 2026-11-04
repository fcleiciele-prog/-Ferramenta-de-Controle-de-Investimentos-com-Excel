
# -Ferramenta-de-Controle-de-Investimentos-com-Excel
O que aprendi neste projeto

Enquanto montava este simulador de investimentos em FIIs no Excel, aproveitei para entender melhor algumas funções e conceitos importantes.

Função VF (Valor Futuro)
 Usei a função VF para projetar quanto o patrimônio pode crescer ao longo do tempo, considerando:

aportes mensais;
taxa de rendimento mensal;
prazo do investimento;
valor inicial investido.

O mais importante foi entender a lógica por trás do cálculo: o dinheiro investido hoje e os aportes futuros vão se acumulando e rendendo juros ao longo dos meses.

PROCV com chave composta
 Também precisei buscar percentuais diferentes para cada combinação de perfil de investidor e tipo de fundo. Como o PROCV trabalha com apenas um valor de busca, a solução foi criar uma chave composta juntando informações como:

Moderado|Papel
Moderado|Tijolo
Conservador|Papel


Dessa forma, cada combinação se torna única e o PROCV consegue localizar o percentual correto.

Principais aprendizados

Como projetar investimentos usando a função VF.
Diferença entre aporte no início e no final do período.
Como criar identificadores únicos usando chaves compostas.
Aplicação prática de conceitos de modelagem de dados dentro do Excel.

Mais do que aprender fórmulas, este projeto ajudou a entender a lógica por trás dos cálculos e das consultas de dados.<img width="1280" height="800" alt="Captura de Tela (4)" src="https://github.com/user-attachments/assets/6d32bc8b-060a-4ffb-a586-48cb07a4ce8d" />
