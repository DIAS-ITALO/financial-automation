# financial-automation

. VerVerificar se valores estão pagos ou não e caso estejam, verificar a forma de pagamento '''
. Com base em uma planilha, pegar o CPF e consultar no site disponibilizado para verificar se a conta está ou não paga '''
. Caso esteja paga, preenchr a planilha de fechamento como "ok", caso contrário, informar que continua pendente.

* Extrair CPF do cliente
* Entrar no site com o CPF da planilha e pesquisar o status de pagamento daquele cliente
* Verificar se está "em dia" ou "atrasado"
* Se estiver "em dia", pegar a data de pagamento e o metódo de pagamento
* Caso contrário (se estiver atrasado), colocar o status como pendente
* Inserir essas novas informações em uma nova planilha
* Repetir até chegar no último cliente

