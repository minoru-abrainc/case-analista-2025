## Case – Estágio em Dados | EDA

### Contexto
Você recebeu uma base hipotética de lançamentos imobiliários. Cada linha representa um lançamento de empreendimento residencial.  
A base foi mockada para simular padrões de mercado, mas sem compromisso de refletir a realidade. Trate-a como dados de treino para análise.  
Seu desafio é explorar o dataset e preparar uma leitura executiva do que ele revela.

---

### Schema da base
Colunas disponíveis:
- `id` (int) – identificador do lançamento  
- `data_lancamento` (date) – data do lançamento  
- `preco_venda_unidade` (int) – preço de venda por unidade (R$)  
- `padrao_unidade` (string) – “econômico” ou “médio padrão”  
- `qtd_unidades` (int) – número de unidades do lançamento  
- `incorporadora` (string) – empresa incorporadora  
- `municipio` (string) – “são paulo”, “rio de janeiro”, “belo horizonte”  
- `lati` / `long` (float) – coordenadas aproximadas  

---

### O que esperamos que você faça
Realize uma análise exploratória (EDA) livre. Use seu critério para decidir:
- quais perguntas investigar primeiro,
- quais cortes e métricas fazem sentido,
- quais gráficos ajudam a contar a história,
- quais hipóteses podem ser levantadas a partir dos padrões observados.

---

### Requisito de código
Inclua no material entregue **pelo menos um exemplo de código em Python/Pandas ou SQL** que você tenha usado na análise.  
Pode ser um recorte pequeno (por exemplo, a construção de uma métrica específica, um agrupamento, uma limpeza ou transformação). A ideia é enxergar um pouco do seu jeito de pensar e implementar.

---

### Entrega e entrevista
- Você pode trabalhar no formato que preferir (notebook, apresentação de slides, dashboard).  
- Na entrevista, você terá **até 8 minutos** para fazer um **pitch de EDA**, cobrindo:
  1. como você abordou a exploração;  
  2. principais achados/padrões;  
  3. hipóteses ou perguntas que investigaria em seguida;  
  4. limitações que notou nos dados;  
  5. um comentário rápido sobre o trecho de código escolhido (o que ele calcula e por quê).

---

### Avaliação (referência)
Vamos observar:
- lógica do caminho exploratório (priorização e método);
- leitura correta dos dados;
- capacidade de síntese e clareza da narrativa;
- postura crítica com o dataset;
- código coerente com a análise.
