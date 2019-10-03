# Orientações
## Qual o objetivo?

### Negócio
- Analise a história e defina os testes de aceitação.
- Exponha o planejamento para execução dos testes.
- Informe e justifique as técnicas de testes escolhidas.


### Técnico
- Desenvolver projeto de testes automatizados para testes de UI e Serviços.
- Escolha a tecnologia e o framework de automação de testes de sua preferência.
- Limite a quantidade de testes automatizados e foque na qualidade da solução.

### O que será avaliado?
- Analise, planejamento e técnicas de teste.
- Mapeamento de cenários de testes.
- Orientação a objetos.
- Estrutura dos testes automatizados (Preparação, Execução e Validação).
- Arquitetura do projeto de automação (PageObjects, Features, Step Definitions, Datapool, Dataprovider, Framework).
- Boas práticas de desenvolvimento de software (design pattern, clean code e etc).
- Simplicidade e objetividade.
- Teste


## Chegou a hora de poupar! Mas quanto? Em quanto tempo? Como posso saber?

Nosso associado gostaria de simular o investimento na poupança para descobrir qual o valor ideal e quanto ele vai poupar no prazo que escolher.

Vamos construir um simulador de investimentos?

### História
Com o propósito de Simular um Investimento na Poupança como um Associado, eu gostaria de preencher o formulário de simulação
e ver a tabela de resultado com Mês e Valor.

#### Critério de aceitação:
- O associado preencher todos os campos corretamente e visualizar o formulário de simulação
- O associado preencher o valor inferior a “R$ 20.00” e receber a mensagem de orientação “Valor mínimo de R$ 20.00”.
- Url: https://www.sicredi.com.br/html/ferramenta/simulador-investimento-poupanca/

API:
A API do Simulador de Investimento está disponível em:

Get:
Url: http://5b847b30db24a100142dce1b.mockapi.io/api/v1/simulador

Response:

{
    "id": 1,
    "meses": ["112", "124", "136", "148"],
    "valor": ["2.802", "3.174", "3.564", "3.971"]
}

### Entrega
Crie um repositório de versionamento para seus arquivos, tal como Git, e nos envie somente a URL. Não aceitaremos entregas de outras maneiras.

Bom teste!
