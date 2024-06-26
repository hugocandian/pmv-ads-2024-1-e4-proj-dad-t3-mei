# Registro de Testes de Software

<span style="color:red">Pré-requisitos: <a href="3-Projeto de Interface.md"> Projeto de Interface</a></span>, <a href="8-Plano de Testes de Software.md"> Plano de Testes de Software</a>

Relatório com as evidências dos testes de software realizados no sistema pela equipe, baseado em um plano de testes pré-definido.

## Avaliação

Discorra sobre os resultados do teste. Ressaltando pontos fortes e fracos identificados na solução. Comente como o grupo pretende atacar esses pontos nas próximas iterações. Apresente as falhas detectadas e as melhorias geradas a partir dos resultados obtidos nos testes.

**Testes Unitários API**:
- Collections Model:

![Models](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2024-1-e4-proj-dad-t3-mei/assets/113808083/7f053cd6-31bb-47dc-a8e0-8de6c2a8afce)

**Teste Software Sistema Web versão 1**

[Link para Youtube](https://youtu.be/gRRu6zKhhXQ)

Observações do teste:
1. CT 01 Funcionando
2. CT 02 funcionando com um leve delay de atualização entre registro da venda e aparecer no faturamento geral e a frase confirmando o cadastro não aparece;;
3. CT 03 funciona, mas a frase confirmando o cadastro não aparece;
4. CT 04 funciona, mas a frase confirmando o cadastro não aparece;
5. CT 05 funciona, mas a frase confirmando o cadastro não aparece;
6. CT 06 precisa de ser melhorada para atingir o objetivo de teste;

**Teste Software App Web versão 1**


https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2024-1-e4-proj-dad-t3-mei/assets/114624183/3e4e078d-5f01-4733-a5e3-ae2c383be4ca


1. CT 01 - Logar no Sistema : OK;
2. CT 02 - Cadastrar Venda para exibir o Faturamento: OK;
3. CT 03 - Cadastrar Despesas: OK;
4. CT 04 - Cadastrar Clientes: em desenvolvimento;
5. CT 05 - Cadastrar Produtos e Serviços: OK;
6. CT 06 - Procurar um contador próximo a minha localização: em desenvolvimento;

Observação (correções futuras):

1. Cadastro de vendas: sistema não exibe nada ao selecionar a opção 'serviço';
2. Ao adicionar, editar e excluir 'produto/ serviço/ categoria', a tela inicial não é atualizada;
3. Melhoria: exibir mensagem de sucesso ao editar/excluir poduto/serviço/categoria; No momento só exibe mensagem de sucesso ao incluir;
4. Corrigir mensagem de sucesso ao adicionar categoria: trocar adicionado por adicionada;
