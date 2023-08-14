<h1 align="center">Compradores da Data Mundo em 2023</h1>

O projeto foi desenvolvido para a empresa Data Mundo

| ✨ Nome | **Análise dos Compradores em 2023 da Data Mundo**<br>
| 🏷️ Tecnologias | Power BI, Excel (tecnologias utilizadas)

<h2>Detalhes do Projeto</h2>
<h3>VISÃO GERAL DO DASHBOARD</h3>

Inicialmente este projeto foi desenvolvido utilizando as ferramentas de Power BI e Excel. O Excel foi utilizado para juntar, ou melhor, conciliar as tabelas de 3 turmas em uma só tabela. No Power BI foram feitos os processos de transformação e limpeza dos dados utilizando Power Query e algumas medidas em DAX para criar cálculos.

O projeto foi desenvolvido para análise de perfil dos compradores durante o primeiro semestre da empresa Data Mundo referente ao seu produto. O intuito foi extrair insights e entender o perfil dos compradores e buscar melhorias para obter mais compradores de demais perfis.

O Dashboard contém 5 páginas sendo o menu principal, 1 página de cada mês referente as turmas dos compradores e por último a aba total, com alguns indicadores de volume e demais outros dados.

**Menu (Pág1)** - Essa página demonstra como construido um menu interativo de cada página, que no caso são os meses e a última página de Totais. Realizando os cliques nos blocos, podemos ir até a página escolhida.

**Janeiro (Pág2)** - Nessa página, fornece a apresentação dos dados sendo destacado pelos indicadores referentes aos compradores da primeira turma do ano que foi em Janeiro.
Como principais indicadores, destaco o Volume de Compradores por idade, uma tabela apontando os números separados por sexo e o maior objetivo dos compradores dessa turma.

**Março (Pág3) e Maio (Pág4)** - Nessas páginas foram esclarecidos os indicadores referentes a cada turma, no mesmo padrão que foi realizado na página 2 de Janeiro.

**Totais (Pág5)** -  Para finalizar essa página fornece os valores totais, onde foi destacado os indicadores conciliados de todas as turmas para construir os indicadores e demonstrar de forma visual nos gráficos.

## ANÁLISE EXPLORATÓRIA ##

Para explicar de forma mais completa nesse tópico, decidi fazer para as 3 Turmas que são de Janeiro, Março e Maio as mesmas métricas para identificar padrões de perfis entre e outro.

O primeiro gráfico utilizado foi o de Área, fornece a visão para idenficar o maior volume de compradores por idade que se interessaram pelo produto.
Em ambas as turmas, houve um padrão com idades entre 25 a 35 com maior volume.

![image](https://github.com/iuryml/Analise-Leads-Compradores/assets/55949523/102faef1-e4d0-4c0e-9fe0-e94f51cece54)


Para realizar a apresentação desses valores de idade, não tinha uma coluna de idade apenas da Data de Nascimento. Portanto, realizei uma médida DAX para criar um cálculo com os dias de hoje. Esse será atualizado automaticamente sempre com o momento de agora.

O segundo gráfico de colunas, fornece a visão do maior objetivo do comprador referente ao que ele espera com o produto. Grande parte de todas as turmas preferiram por Migrar de Área, ou seja, mudar a posição atual de carreira para uma nova.

![Volume de objetivos](https://github.com/iuryml/Analise-Leads-Compradores/assets/55949523/6f508e96-c2d2-42dc-b900-15e1637a68b0)


Para completar, elaborei uma tabela com a segmentação desses compradores alinhados por sexo, estado civil e se tem ou não filhos por colunas de nível de escolaridade

![image](https://github.com/iuryml/Analise-Leads-Compradores/assets/55949523/65ebb5ce-b39a-42f7-b2d9-925022f8a1cf)


Para a última página, apresentei 4 indicadores. 
Começo pelo gráfico de área, com uma análise temporal por bimestre, Podemos compreender que a Turma de Março houve um maior volume de compradores enquanto o mês Maio houve uma queda maior de 23% em relação a turma anterior.

![image](https://github.com/iuryml/Analise-Leads-Compradores/assets/55949523/e9f06e82-16a2-4780-a408-d1586267478d)


O gráfico de pizza com um cartão acima, demonstra os valores de segmentação de divisão, onde grande parte foi adquirida por sexo Masculino enquanto feminino há um valor bem abaixo se comparado. No total teve 660 Compradores do Produto da empresa.

![image](https://github.com/iuryml/Analise-Leads-Compradores/assets/55949523/314ad7eb-e51d-4f8d-a775-32601400ac4d)


Ao lado temos um gráfico de barras empilhado, fornecendo a contagem total de onde os compradores conheceram o produto, como destaque o Instagram com grande porcentagem.

![image](https://github.com/iuryml/Analise-Leads-Compradores/assets/55949523/13fc39fd-09ad-4c5c-a1e4-5e0383508131)


Finalizando, com um mapa e uma tabela, contabilizando o total de compradores por estado e no mapa o volume por estado.

![image](https://github.com/iuryml/Analise-Leads-Compradores/assets/55949523/cd3605a0-1711-4105-8aec-f0afc43c7c4c)


<h3>CONCLUSÃO</h3>

Destaco que grande parcela dos compradores são da Região Centro-Sul do Brasil, com maior parcela do sexo Masculino e grande maioria preferem migrar de área em suas posições de carreira atuais. O Instagram é a plataforma que mais conseguiu captar clientes para a empresa. 

Caso queira ter iteratividade no dashboard pelo Power BI, fale comigo por e-mail: **iurylima98@outlook.com**
