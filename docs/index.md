<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
*&lt;Nome do Projeto&gt;*
</center></font>

>*Observação 1: A estrutura inicial deste documento é só um exemplo. O seu grupo deverá alterar esta estrutura de acordo com o que está sendo solicitado na disciplina.*

>*Observação 2: O índice abaixo não precisa ser editado se você utilizar o Visual Studio Code com a extensão **Markdown All in One**. Essa extensão atualiza o índice automaticamente quando o arquivo é salvo.*

**Conteúdo**

- [Autores](#nome-alunos)
- [Descrição do Projeto](#introdução-do-projeto)
- [Análise de Requisitos Funcionais e Não-Fucionais](#descrição-dos-requisitos)
- [Diagrama de Atividades](#diagrama-de-atividades) 
- [Diagrama de Casos de Uso](#diagrama-de-comportamento-atores)
- [Descrição dos Casos de Uso](#descrição-das-funcões)
- [Diagrama de Senquencia](#diagrama-de-ordem-interações)
- [Diagrama de Classes](#diagrama-orientado-objetos)
- [Diagrama de Estados](#diagrama-estrutura-componente)
- [Diagrama de Implantação](#diagrama-de-hardware-software)
- [Referências](#referências)


# Autores

* Caio Guilherme dos Santos Silva
* Diogo Fassina Garcia
* Francisco Losada Totaro
* Aluno 4
* Aluno 5
* Aluno 6
* Aluno 7
* Aluno 8


# **1. Descrição do Projeto**

Desenvolver um sistema de presenças para a escola INFINITO para acesso dos professores, tendo um acesso próprio para cada professor e que registra a chamada no ínicio das aulas e logo após o intervalo, gerando um relatório das faltas de cada aluno, podendo ser agrupado por data, ano de ensino, turma, etc. Além de enviar notificações para os responsáveis por excessor de faltas, contando com acessibilidade e acesso à partir da web.

# **2. Análise de Requisito funcional e Não-funcional**

- **Funcional**<br>
Sistema de Login<br>
Registro de aluno e turma<br>
Atribuição de turma ao aluno<br>
Acesso dos professores as turmas<br>
Sistema de presença<br>
Registro de faltas<br>
Sistema de notificação automático por email<br>
Acessibilidade<br>
Responsividade<br>
Registro/Leitura do email dos responsáveis<br>
Relatório de faltas agrupados por:
    1. Data
    2. Ano de ensino
    3. Turma
    4. Professor
    5. Disciplina
    6. Aluno
<br>

- **Não-Funcional**<br>
Garantir que informações pessoais sejam criptografadas<br>
O sistema deve estar disponível 99,99% do tempo (alta disponibilidade)<br>
O sistema deve ter um tempo de resposta inferior a 5 segundos<br>
O sistema deve suportar o acesso simultâneo de todos os professores<br>
O sistema deve ser capaz de processar 500 transações por segundo<br>
O sistema precisa ter acesso a um banco de dados para permanência das informações<br>
O sistema deve ser capaz de calcular a porcentagem de faltas dos alunos<br>
O sistema deve ser capaz de detectar incongruências nos dados<br>
O sistema deve ser capaz de disparar emails através da web



# Diagrama de Atividades

![Opa! Parece que a imagem nao funcionou!](https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Diagrama%20sem%20nome#R%3Cmxfile%3E%3Cdiagram%20name%3D%22P%C3%A1gina-1%22%20id%3D%22g9BKU89KwJ0dT-WAyuCA%22%3E7R1Zd5s6%2Btf4nJkH57Avj1naO10yJ7fpzaTzModibHOLkS%2FgJrm%2FfiRAGCSxGIOktulDaiQh4Ns3SQv9evf8W%2BLtt7dgFUQLTVk9L%2FSbhaapmq7D%2F1DLS9ViFS2bJFyVbceG%2B%2FDvoGxUytZDuArSxsAMgCgL981GH8Rx4GeNNi9JwFNz2BpEzafuvU1ANdz7XkS3%2FidcZVv8GYpy7PhXEG62%2BNGuVvbsPDy6bEi33go81Zr0Nwv9OgEgK37tnq%2BDCIEPA6a4721Lb%2FVmSRBnQ25Q3q8%2BbNIP%2FwXq3%2B6fnx8V%2F50aLnWtmOa7Fx3KTy7fNnvBMAji1SUCJbyKQQwbr7bZLoJXKvyZgEO8CtAjFHi1BnFWIlGFH3iVZl6CGxx4DaeqXfmH5Ht%2BK5qoeGywovBx%2FD61ghokuADsgix5gUOejogxS1hvayjBbUkQeVn4vTm9V9LHppquesIdCOGDNaUkZsN1iltKUnZcpTlFCg6JH5R31fFATGRi2m6bCMJsE2TURPBH7bOPTTma2Sj%2Fy82yh3eqb%2B3M%2B2%2FL37cvu7vN0jUHoDyKIIchVD9twyy433s%2B6nmCXN5EfwuS4OxBkgXPnXjD8FDMJjys8rqGV9tsxysLhQ2YnQwgd1KeCJ7D7LH2%2Bwv6fWGWVzfPta6bl%2FKiFawEf4hiBrOJMlWxRzKDoTcmcvVhvABh773Uhu3RgLSDeXX2%2Bx7JpJhxLKP5wLj5dPtH%2FP42gbB%2BUNbb%2FWFp0FQDsXdfXoIk24INiL3ozbGVIJ3jmI8A7Evq%2BjPIspdSinqHDDRpbwy10cQMW96G6Gtr1DhGNJ8rc0m0qcqFNohAaIrVLtz6P4OaeRABTyaEbdmEcJMPHY4y%2BOP7p%2FTq9u7p8fo6vHv%2B%2Btdq8%2FtSVYUwTwzf%2FfHIMejyS8Uk8OLIP%2FlVr7guqKjjO0sCL6i4Y5wxUPwPZrizsKNTxJvB5yI7P4B%2FIrAJYwp9TeTMT9GG1SRp1VAoklY1hoq05qJpRwxJD5HtY0h3cpJkC27LIfBImhoTmssdn1mj9ZK%2B36ZBvEVEH0AvB%2BQ%2BaJIEGUhp0t%2BC3ddDyofsbe2iaZxpDMJ3GbJcVeYifIsCoQ9Asgpi6BAni8o%2FFicrNJ0EmiFcWtAGQry41heXOqDABb8ya8LEi8JNDH%2F7ECZBAhsQLELfiy7Ljl24WkVtpkUT%2FFNYF26Thyuo1aBrMYBLegPTmRd02CMNdz8eYA27CVjdFA1YU4ySK%2B226qLm9oyx23rtMV0S5TedmxI%2B258esvXV8tOtc%2F149Zj%2BZlwtaTYRgd7xNopqDcQnFu0TI%2FTUOIVt2oQiMnUiqnvqHWfHNjoBW6OMfQLWQZoijS5YnVsWCROu6pzJSbRcnNJbNUyrLvmWyoWi2D3CL7%2B6C5IQfiBSZUVjLzcPkpn3q5367y%2Fp%2Fx7e2Ydv2YelnWnrpcrJY9Bc0pqzSNN2aHhSpaciQx4TRSg1x2W%2B8lRczCRKS6iynirI0k94Fh%2FC0w1lFNmNQCczmafSnlQdn6X%2F38i6TRdvrmLMX2o9bfHmcRRwWnaRifNxZgTWFHVKY2JAO5OuzrK98VvWdPJ9mGbBrorMrb0o8xjxCe762bxQmqF90%2BaooJlCYoipWwXka%2FBIt94e9RfEmHkZ6l%2BHUXQNIpDkN%2BpK%2Fi%2Bn2AR8C2o963XZMwFYyUQqwxfUZ%2FIFmRClo8Qj1E0N0qSr%2FRVkGdg1Y5xgH8SUJGiH%2BkCHvC4guohnbgVjaoQ7aAwzRkYoGOZn0rHQ82RJG5tMwAxk%2BF93BwoYbS52oD0mmh2OhOxHXpqG%2FmJIYQEH1TtedxoDjbShzgGnAgfClDNIThtc7eO20CEnlj2tlmUI1Y2kIEytao1WR5fB9ApkBtV1xjEkITtDm4jsqMDwQLI71W01FeKFm24rHa7SnK7xZ7u5bP8Pa4%2FpRe8JxDyr6D2LCV554LzQjdv0ZfjQ9BB%2FhY9gHx8y7DUeJg%2Ffc7IeCBI2x8YfTadnoolIWNeJ5%2Bhmjxgncw6N8TOR%2FBCH8sezoCWhWa2P1IbSLDXRfAU7nWmGenXaIUFBsHNc1Vb0nVBlYlLJBEYdhMNAMakBJyt1V3tCxlIVKU%2Bc4%2B81n5jJYyYUlckTDGdFGrqSs4H48K9BuMQScIGY0swRHvFR%2B3DjAnsoF2CTVBYuoCvo4K%2BYVZ%2FJWxGIo39mGpiOEV15sY9KWvOs0cpbyQA00qYWnjFSp10n1gojSQxEcqkWWQgx2C0nrSB7oFMzlYHIyJPOgrf%2BrJFkCKYQQ6YGh6KYUPDUPHMj%2BLTYyGgE9%2BY0XhE8E4LpgK6%2FX9M4FreAzlZp7WQxFl1ModPZIDotWDKjkJMrsUfzgDMRD5DzzM0DrGS8FaH1Cgf4Y4N%2B7LwsyReN3PgHtD6v6IaPq0ZIxTOsVSFceWbIzghceEa2jAzBM85EeoOaZ26eGbLqmguCHckRPHZzExLBnKsdNE4uWS%2BCMWHLiuDR3huBYGqemRGsn5bKn9G0%2F2nNml4nYW4Uc%2FLepMHcNKrV7Jlnbqxx8jdkwVozGDZ%2BM7CeeebG2oCK3p8Ia85UIcyeeebGGh3A9JGbd6Wvwk0etkcrPthJb5GbCuH3Fubf0XnRGE4tE4wc4XEjhyERirgBWn7VAJT11wHgjmWapzkv4QBn%2F5zDBnfjWMO7eA0QSaKAhJ3Tq4my0UqeXVI%2BBekexGneq34PwrQWriieLF%2FEwmHkoObCFjvnyiliIYn8JvfgHC%2FAXXKF%2BIxJKDbmTlsOMomnyn4RyUIRNGZGW8QGN0eGDVlO0ab%2ByoxXFM%2BFYlpbik9EESDhaFGwYSQgJsd8EcmKxBlsMDZmQ7HBfLmoTsh25aL8bJ9KmIEiAMcxBcWGJKf4Zj%2BzuJIzy%2FhAmdEz0dzMIiAzz34R2c2C0eY9ieIZAzRsyHIKq%2FVafj%2Bzyus1IudG8q%2Fme9sTyV%2BlZ6K58cbJLZMEb6Y%2BWcykZ6K58Ub7WqkXFfHCJKR3xRVpR%2FIMdXeab3KFugnDS7Rnav9akkAzm4J3tCTQTEtw9NRmZSlE2NCOXAYWAzNj1bSuGN0TzY1iTmGjXhv6FcVzoRhDtobiY8UyjhWley9esLKOXz3%2F2yZH8tIv9hBDyccwDrMQmgWsBGRRBK3gVYBVLKp4hAThKM0iECJaQzqyhKMcTXYmHOvIUkzIOXaLIVtPYeShWqV9Q2%2BhPCE6ROvIEr9zZTMvSZ4YHSIgeYJ3iMD5tcridOwtnlvNSOGN89GmDqeiin6b8SdWV73m59xIntZrn3xHDWlwToRZxzI1tELFMjUnX18avFnTKFHN6plo7nOmhxQFtJYtS1YoQFqhwis%2FXdozK2pn3SQUG%2BalQCXaiXWZx5UGayQocPXx3gvpLW64BseJBAJju3K%2BVVvKfLstLkZtmmvU9TM64Sg%2FA4TnCUd1j6xrI6X%2BA2lsqVQOuYmzQ26ZNDi127aagVc5JgbsL76dYfcuhQIO6jpTFNFuXRCnYezRJ3byPGpXJzY6Ze3jxjp8c8Z9DF2R5D%2F5zv68thlsM8QJ9HIOzKqMLb79Q5IKpnqVPOSMI9WzTz3TO4n%2B9dSzAZzWfpjZgEPPCjrloB263rLGJDdeNslmzxRPMMDYyiaMM85YnDLbjpVMWMkUOesnUXmipa7hXuBw2unhM2XAbNPpEibimaVzKNqyLpLt0HM7e6n4WeyiUUf28iyhY8IM743wqlcm1ivYrulVLMWeIqIUC8P8%2BjzVOQJTqxabcdbjbKrFB8bNp9s%2F4ve3CZz4QVlv9weshuX3PM47v2MaBjAGMkCxYcW5ns2ph8E4OpTFxA4nJd20KTnGLaqidd9j2733LM49R4ZJqt3%2BgkQxIiEkZ4ogOUs9meQYt%2FSSnMWB5DrBX9MlH8M0qw5mxiWJig926K8XPntpDj8U5oq8Yj%2BUYuw%2BCdIgLnZRkVIZsSw3vn6OLvQ8j5%2FaeMOr3vqNN1uk8cZYnPcWHX4unl9YmpJhvc11AEiHndGA1p1UUsaWEmr0CgVEY%2BBAgQt%2BeNaEiVeeYe5DAKDUJHW4%2BS5craI237sJ%2FrosUGakUoWGN0uqkzm%2F6aQ6XVDyEDAW%2Fv1w0LZdGaFtdupQacIfp2lCCbw%2FvFNqf1zdOFODtvhdmnOBYxvYYht71qOtWReO0xK44xTbZOw8e%2BtluBZKvO5iWMiOIdxCpjX%2BZ5B5EXYy1shYOrsi6iy4ERVRTH3Pt46MduJwHVnau1qttkQt2Xz1%2FgFfEr6FQvz3zxx0Sr6h5trbhdFLccsOQPewAHbVf9xwUyk33FSQ5luWyu4yfw0oC2tdBZ5QTwxKnNGr5BaamSME9m9vwSqIUMObvDUBcGR1haFm5nCDLTfoNyJjE8HJhMDuG6tWYzFhjJpGO05TIKfq8UFRW2oW1aVmVV%2BKxxeYqsZjAocNdRJH%2FTnAUHtO5qhFzS9rzy7IfcjXVV3Vhx0ZwEQsUI3UrSMklJdjey5mcXvBElUfYgvcVbJG1WfUbkMcjts3teeTYM8vK9jXG5sUUY6jSEe%2BlZYmtpsE1PN2uMvtEaIWgcxdmTGibqrwvLZOe2KXq9APofEp0DvQZgQ5q6aaAXHSFBsA8UXJ1DUb7cjO%2Bpv%2FAw%3D%3D%3C%2Fdiagram%3E%3C%2Fmxfile%3E)

# Diagrama de Casos de Uso

*&lt;Diagrama para visualizar o comportamento dos atores&gt;*

# Descrição dos Casos de Uso

*&lt;Descrição do comportamento entre os atores/resquisitos&gt;*

# Diagrama de Sequência

*&lt;Diagrama de ordem e interação dos objetos&gt;*

# Diagrama de Classes

*&lt;Diagrama de relacionamento entre classes para os seus atributos e operações&gt;*

# Diagrama de Estados

*&lt;Diagrama para permite modelar o comportamento interno de um determinado objeto, subsistema ou sistema global&gt;*

# Diagrama de Implantação

*&lt;Diagrama para exibir o relacionamento de hardware e software no projeto&gt;*

# Referências

*&lt;Lista de referências&gt;*
