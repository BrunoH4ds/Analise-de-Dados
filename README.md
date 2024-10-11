# Análise de Cancelamentos

Este projeto tem como objetivo realizar uma análise dos cancelamentos de contratos, identificando padrões e causas que impactam a decisão dos clientes em cancelar seus contratos. O processo é dividido em várias etapas, desde a importação da base de dados até a visualização e análise dos dados.

## Insights

- **Contratos Mensais:** Todos os clientes que possuem contrato mensal cancelaram. Uma sugestão é oferecer descontos para planos anuais e trimestrais.
- **Atendimentos ao Call Center:** Clientes que ligam mais de quatro vezes para o call center tendem a cancelar. É recomendado criar um processo para resolver problemas em até três ligações.
- **Atrasos no Pagamento:** Clientes que atrasaram mais de 20 dias também cancelaram. Sugere-se estabelecer uma política para resolver atrasos em até 10 dias pela equipe financeira.

## Instalação das Dependências

1. Antes de executar o projeto, é necessário instalar as dependências. Execute o seguinte comando:

   ```bash
   pip install pandas numpy openpyxl nbformat plotly
   
2. Executando o Projeto: 
Após a instalação das dependências e a preparação do arquivo cancelamentos_sample.csv, você pode executar o script de análise. Certifique-se de que todos os arquivos necessários estejam na mesma pasta.

## Observações

- **Limpeza de Dados:** É crucial revisar e limpar os dados antes da análise para garantir resultados precisos.
- **Ajustes nos Gráficos:** Os gráficos podem ser ajustados conforme a necessidade para melhor visualização dos dados.
Este projeto fornece insights valiosos que podem ajudar a empresa a entender melhor os motivos dos cancelamentos e implementar estratégias para reduzi-los.
