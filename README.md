# Projeto: Otimização de Despesas com Marketing - Y.Afisha (Empresa fictícia)

## Descrição do Projeto

Este projeto foi desenvolvido como parte do estágio no departamento analítico da Y.Afisha, uma empresa focada em oferecer eventos e entretenimento online. O objetivo principal foi analisar os dados de uso do produto e de compras para otimizar as despesas de marketing da empresa.

Os dados analisados abrangem o período de janeiro de 2017 até dezembro de 2018, e incluem:
- Logs do servidor com dados sobre acessos à plataforma Y.Afisha;
- Um arquivo de despejo contendo todos os pedidos realizados durante o período;
- Estatísticas detalhadas sobre as despesas com marketing.

## Objetivos da Análise

1. **Compreender como os usuários utilizam o produto:**
   - Identificar padrões de navegação e uso da plataforma.
   
2. **Analisar o comportamento de compra dos usuários:**
   - Determinar quando os usuários começam a comprar após acessar a plataforma.

3. **Calcular o valor de vida do cliente (LTV):**
   - Estimar quanto dinheiro cada cliente traz para a empresa ao longo do tempo.

4. **Avaliar o retorno sobre o investimento (ROI) em marketing:**
   - Determinar quando as despesas com marketing serão cobertas pelos lucros gerados pelos clientes.

## Etapas do Projeto

1. **Coleta e Processamento dos Dados:**
   - Importação dos logs do servidor, arquivo de pedidos e dados de marketing.
   - Limpeza e formatação dos dados para análise.

2. **Análise Exploratória:**
   - Exploração inicial dos dados para identificar tendências, outliers e padrões relevantes.
   - Criação de gráficos e tabelas para visualização dos resultados.

3. **Métricas de Desempenho:**
   - Cálculo do CAC (Custo de Aquisição de Cliente).
   - Cálculo do LTV para diferentes coortes de usuários.
   - Análise do ROMI (Return on Marketing Investment).

4. **Insights e Recomendações:**
   - Identificação de coortes mais lucrativas.
   - Sugestões para otimizar campanhas de marketing com base no ROI.

## Ferramentas Utilizadas

- **Python**: Pandas, NumPy, Matplotlib, Seaborn
- **Jupyter Notebook**: Para desenvolvimento e análise interativa
- **GitHub**: Controle de versão e compartilhamento do projeto

## Conclusões

A análise revelou insights importantes sobre o comportamento dos usuários e a eficiência das campanhas de marketing:
- A maior parte dos usuários faz uma compra dentro de 30 dias após o primeiro acesso.
- Coortes específicas de clientes apresentaram um LTV significativamente maior.
- As despesas com marketing para determinadas campanhas foram cobertas em até 6 meses.

Esses resultados foram utilizados para ajustar o orçamento de marketing e concentrar os esforços em coortes mais lucrativas.

## Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone <URL_DO_REPOSITORIO>
   ```

2. Instale as dependências necessárias:
   ```bash
   pip install -r requirements.txt
   ```

3. Execute os notebooks na ordem fornecida para reproduzir a análise.

## Estrutura do Repositório

- `data/`: Contém os arquivos de dados (não incluídos por questões de privacidade).
- `notebooks/`: Notebooks Jupyter com a análise passo a passo.
- `src/`: Scripts auxiliares para processamento de dados.
- `README.md`: Este documento.

## Contato

Para dúvidas ou sugestões, entre em contato via [lara.danilo25@gmail.com].

# projeto-8
