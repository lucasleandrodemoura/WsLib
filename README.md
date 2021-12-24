# WsLib

<br>

https://api.connect.libercapital.com.br/v1/buyers/docs#operation/submit_invoice

<br>
<b>Parâmetros necessários que precisam ser criados e preenchidos</b><br/>
LC_CLIID : Client ID<br />
LC_CLISEC : Chave secreta cliente<br />
LC_ENV : Produção ou homologação<br />
LC_URLHOMO : URL Homologação<br />
LC_URLPROD : URL Produção<br />
LC_PROGRAM : Programa<br />
LC_DOCUMEN : Documento 8 primeiros digitos do CNPJ<br />


<br />
Função LcGetTitulo
<br>
Retorno
<br>
[1] => ID <br>
[2] => STATUS <br>
[3] => Codigo de referencia informado <br>
[4] => Número do titulo <br>
[5] => Status do ultima mudança <br>
[6] => Erros gerados na última mudança <br>
[7] => Tipo do título <br>
[8] => Data do vencimento <br>
[9] => Moeda do título <br>
[10] => Valor do título <br>
[11] => Tipo de documento do fornecedor <br>
[12] => Nome do fornecedor <br>
[13] => CNPJ/CPF do fornecedor <br>
[14] => Tipo de documento do pagador <br>
[15] => CNPJ/CPF do pagador <br>
[16] => Nome do pagador <br>
[17] => Última negociação <br>
[18] => Toda a chave <br>
<br />


<br>
LCCreateTitulo
<br>
Retorno <br>
Se tiver sucesso (202)<br>
[1] = Código do status da operação <br>
[2] = Ultimo status de atualização<br>
[3] = Erros da ultima atualização<br>
[4] = Código ID gravado<br>
[5] = String completa de retorno que pode ser quebrada com JsonObject:fromJson<br>
<br>
Se tiver dado erro<br>
[1] = Código do status da operação <br>
[2] = Ultimo status de atualização<br>
[3] = Erros da ultima atualização<br>
[4] = String completa de retorno que pode ser quebrada com JsonObject:fromJson<br>



<br>
LCUpdateTitulo<br>
Retorno<br>
[1] = Código do status da operação<br>
[2] = Array com erros apresentados<br>
[3] = String completa de retorno que pode ser quebrada com JsonObject:fromJson<br>


Desenvolvedor<br/>
Lucas Leandro de Moura - <a href=mailto:lucas@8bit.inf.br>lucas@8bit.inf.br</a>
