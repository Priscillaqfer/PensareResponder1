# Análise de Vendas

## Descrição
Este script gera um conjunto de dados fictício de vendas, salva os dados em um arquivo CSV, carrega os dados e realiza uma análise mensal das vendas. O relatório mensal inclui a quantidade total vendida, o valor total das vendas e o preço unitário médio por mês.

## Funcionalidades
- Geração de um dataframe com 1000 linhas de dados fictícios de vendas.
- Salvamento do dataframe em um arquivo CSV.
- Carregamento dos dados de vendas a partir do arquivo CSV.
- Cálculo do valor total das vendas.
- Extração do mês a partir da data da venda.
- Agrupamento dos dados por mês e cálculo de estatísticas (quantidade vendida, valor total e preço unitário médio).
- Formatação dos valores monetários com o símbolo "R$".
- Exibição do relatório mensal.

## Como Executar
Para executar o script, siga os passos abaixo:

1. Certifique-se de ter o Python instalado em sua máquina.
2. Instale as bibliotecas necessárias:
    ```sh
    pip install pandas numpy
    ```
3. Execute o script:
    ```sh
    python Untitled-1.py
    ```

## Exemplo de Saída

O script gera um relatório mensal como o exemplo abaixo:

| Mês | Quantidade Vendida | Valor Total | Preço unitario |
|-----|---------------------|-------------|----------------|
| 1   | 860                 | R$43718.48  | R$56.09        |
| 2   | 803                 | R$41815.38  | R$52.94        |
| 3   | 935                 | R$48734.38  | R$53.35        |
| 4   | 953                 | R$56151.91  | R$58.18        |
| 5   | 1007                | R$57503.00  | R$56.96        |
| 6   | 979                 | R$55894.50  | R$56.99        |
| 7   | 910                 | R$50773.45  | R$56.15        |
| 8   | 861                 | R$46809.26  | R$54.84        |
| 9   | 823                 | R$50809.23  | R$59.46        |
| 10  | 835                 | R$47578.85  | R$58.79        |
| 11  | 925                 | R$52067.22  | R$54.33        |
| 12  | 1088                | R$63124.32  | R$57.52        |


## Contribuição
Se você deseja contribuir com este projeto, siga os passos abaixo:

1. Faça um fork do projeto.
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`).
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`).
4. Faça o push para a branch (`git push origin feature/nova-feature`).
5. Abra um Pull Request.

## Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.


