# Dashboard de Assinaturas - Xbox Game Pass

## Objetivo
Transformar dados brutos de assinaturas em visualizações estratégicas para:
- **Analisar desempenho de planos (Core, Standard, Ultimate)**
- **Monitorar adesão a serviços complementares (EA Play e Minecraft)**
- **Avaliar impacto de renovação automática e cupons de desconto**
- **Identificar padrões de faturamento por tipo de assinatura**

## Dados Utilizados
Conjunto de dados contendo:
- **Subscriber ID, Name, Plan type**
- **Start Date e Auto Renewal status**
- **Subscription Price e Type (Monthly/Quarterly/Annual)**
- **EA Play Season Pass (status e preço)**
- **Minecraft Season Pass (status e preço)**
- **Coupon Value e Total Value**

**Fonte**: Dados estruturados na aba `Bases` da planilha (3500+ registros)

## Funcionalidades do Dashboard
1. **Visão Consolidada**:
   - **KPIs de faturamento total por categoria de plano**
   - **Análise comparativa de planos anuais vs mensais**
   - **Desempenho de serviços complementares**

2. **Segmentação por Serviços**:
   - **Adoção de EA Play Season Pass (por tipo de assinatura)**
   - **Penetração do Minecraft Season Pass**
   - **Efeito de cupons no valor total**

3. **Análise de Comportamento**:
   - **Correlação entre renovação automática e ticket médio**
   - **Distribuição temporal de novas assinaturas**

4. **Painel Interativo**:
    ![](image/opa.pngopa.png)

   - **Filtros dinâmicos por tipo de plano e serviço**
   - **Tabelas dinâmicas com detalhamento de valores**
   - **Visualização de tendências temporais**

## Perguntas de Negócio Resolvidas
O dashboard responde a:
1. **Faturamento total de planos anuais** (agregado e por status de renovação)
2. **Volume de vendas do EA Play Season Pass** (segmentado por plano)
3. **Desempenho do Minecraft Season Pass** (comparativo entre planos)
4. **Impacto de cupons no valor total** por categoria

⮕ **Excel Intermediário** (Tabelas Dinâmicas, Formatação Condicional)  
⮕ **Design System Xbox** (paleta de cores oficial da marca)  
⮕ **Análise Direcionada a Negócios** (foco em serviços de assinatura)

**Arquivo disponível :**
[Download do documento](/downloads/Analise_xbox.rar)