# Planilha Financeira Inteligente

Uma planilha financeira criada a partir de dados fictícios gerados a partir de IA.

💸[Clique aqui para baixar a planilha](https://github.com/anagalli/PlanilhaFinanceira/blob/main/Planilha%20Financeira%20DIO.xlsx)

# 💻 Tecnologias utilizadas no projeto
- [ChatGPT](https://chatgpt.com/) para geração dos dados e criação do avatar
- [WPS Office](https://br.wps.com/) para criação da planilha

# 🧠 Prompts utilizados

**ChatGPT**
| Ação | Promtp |
|------|--------|
| Gerar dados fictícios para base de dados da planilha|Preciso fazer um projeto de planilha financeira e gostaria de alguns dados fictícios para montar minha base de dados.<br><br>Gostaria de uma simulação desses dados contendo as seguintes colunas:<br><br>DATA TIPO CATEGORIA DESCRIÇÃO VALOR STATUS<br><br>{REGRAS}<br>- As datas devem se manter em um ano somente, podendo variar de janeiro a dezembro seguindo a ordem cronológica (como se fosse um histórico de transações)<br>- O tipo refere-se a ENTRADA e SAÍDA somente<br>- Categorias podem variar desde contas, salário, lazer, Investimentos etc<br>- Valores devem ser escritos somente em número, utilizando vírgula como separador decimal.<br>- Status variam entre PAGO, PENDENTE, RECEBIDO
|Complementar dados da planilha|Gere mais dados variando mais as categorias|
|Gerar dados para as caixinhas|Gere agora para mim alguns dados de depósito em uma caixinha de economias para o futuro, devem conter os seguintes dados, mês a mês até outubro:<br><br>DATA MOTIVO VALOR<br><br>{Regras} <br><br>- O motivo é a finalidade da caixinha (exemplo: reserva de emergência e casa própria|
|Gerar avatar da planilha | Gere para mim a imagem de um avatar feminino cartoon dando oi, converta a imagem em .png|
