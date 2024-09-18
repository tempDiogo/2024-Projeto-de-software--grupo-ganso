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

![Opa! Parece que a imagem nao funcionou!](https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Copy%20of%20Diagrama%20sem%20nome.drawio#R%3Cmxfile%3E%3Cdiagram%20name%3D%22P%C3%A1gina-1%22%20id%3D%22g9BKU89KwJ0dT-WAyuCA%22%3E7R1Zd5s6%2Btf4nJkH57Avj1naTpfM6W16M%2Bm8zKGAbW4xcgE3yf31IwHCIMmAMUhqmz6kRhICvn2TtNCvt09vUm%2B3uQVBGC80JXha6DcLTbNsB%2F5FDc9Vg66UDes0Csom9dBwF%2F0dVo142D4Kwqw1MAcgzqNdu9EHSRL6eavNS1Pw2B62AnH7qTtvHVINd74X063%2FiYJ8U7VqinLo%2BFcYrTf40a5W9Ww9PLpqyDZeAB4bTfqrhX6dApCXv7ZP12GMgIcBU973%2Bkhv%2FWZpmORDblDeBe%2FX2fv%2FAvVv96%2FPD4r%2FVo2WulZO88OL99UnV2%2BbP2MYhElwiUAJrxKQwMarTb6N4ZUKf6ZgnwQheoQCr1YgySskqvADr7LcS3GDA6%2FhVI0rf5%2F%2BKG5FE9GfU31hGLRQVH3cmxBswzx9hgMeD4gxK1hvGijBbWkYe3n0o41Yr6KPdT1d%2FYSPIIJvoikVKRtuRcoVJTuu0p4iA%2FvUD6u7mnggJjIxbR%2BbCMJsHebURPBH47MPTQWa2Sj%2F7ub5%2FVvVt7bm3bflH5vn7cf10jUHoDyOIYchVD9uojy823k%2B6nmEPN5G%2F1Gs%2FQjTPHzqxBuGh2K24WFV1w282uZxvLJQ2ILZyQByJ%2BWJ8CnKHxq%2Fv6DfF2Z1dfPU6Lp5ri5kZwazjTJVsUcyg6G3JnL1YbwAYe89N4bt0ICsg3l19vseyKSccSyj%2BcC4%2BXT7Z%2FLuNoWwvldWm91%2BadBUA7F3V12CNN%2BANUi8%2BNWhlSCdw5gPAOwq6vorzPPnSop6%2Bxy0aW8MtdHEDFteR%2Bhrz6TGc2UuiTZVudAGEQhNsdqF2%2FxnUDMPIuDJhLAtmxBu86HDUQZ%2FePeYXd1%2BfHy4vo4%2BPn39Hqz%2FWKqqEOZJ4Ls%2FHDgGXX6pmQReHPinuOoV1yUVdXxnReAlFXeMM6ZmuLOwo1PEm8PnIjM%2FhH9isI4SCn1t5MxP0YbVJmnVUCiSVjWGirTmomlHDEmPlO29pDs5SbIFt%2BUQeCRNjQnN5Y7PbNB6Rd%2BvszDZIKIPoZcDCh80TcMcZDTpb8D26z7jQ%2Fa2dtE2zjQG4bsMWa4qcxG%2BRYHQByANwgQ6xOmi9o%2FFyQoIkBbIDOGygjYPksW1vrjUAQUs%2BI15GyJeHK0T%2BNuHEAlT2IAgEflefFl1bKMgiI8ZFm3gT2FbuG0OrqHWgK7FAC7pC0xnXNBBjyza%2FnyANew2YHVTNGBNMSqustrqi4bTM8Zq67XGdElU33ROSvRkf7rPV1fLT7fO9cPVQ%2FbGuFrSbCICveMtFNUaiE8s2idG6KlRCtu0Cd1t6kRM99Q7zo5sdAK2QRm7FKzCLEP6XLAytywSJlzVOZOTaLkozFft59hBcvEu2Kr%2F%2FpL97%2F6tvf%2BWv1%2FaubZaqpx8As0ljVyLNF6HBiBVeioyqDFRDFJzXOYrT8WpTMKzhCrkqcIo%2FYRn8SE83VBGkd0IdDLTdSrtKzXxWXn4rbzadBHlOor8pdFzLKI8jgJOyx%2BOtwyw8G8SFhPg2tR0dZZ9jV%2B7oXfvoiwPt3XsbeXFuceIQHDXweaF0g7emzZHJcwUEkPM2Trk3oBHtvF2qL8kxtzLUf8qiuNrEEN7B92oK8W%2FgmJT8C1s9KxWVc8EYCVTpQx%2FT5%2FJ32NClI4Dj1A3DUiT7vRXkOdg245igl2YUJLgONQHOt1NidFFPHMrGFMjXD5jmDEyQsEwP5OOdp4nS46xyQTMQAb4dXeggNHmYgfaK6LZ4UDIfuxlWeQvhpQOcFC945WpMdBIG%2BoccCphIEw5g%2BS0wfU87hE65MSyp1WrDKG6sZ5lRa1qg1ZHF7r0CmQG1XXGKiQhO0ObiOyo4O9AsjvVbTUV4oXbbisdktKcrvFnu7ls%2Fw9rj%2BlF7wnELCAkMxmbvHDJLMKZkWoSJZ2nIbIu4pkuzs7JBCCozBwbRDSdnokmksW6TjxHN3tkMZkcaI2fSRYP8Qp%2FPjNYEprVHOfCVqchW9Zc81XXdGYMmqVk%2BxTFswRHsDSDiNYzihYcBppJRTVZVbraE%2FuVqp544oR8r5XDzPQyoahMnik4K2TQlUkNxcdxDcK3lYALxFRRjnBtDxqIGxfYQ7kAm6WycAFd7gZ%2FJaxSSt5qQBz9M%2FO5dLDnykt8VH1apH8CL5ABaEQ5pfjUjzrtkq6jMJLESCRXVZEVDYO9Z7I2wh7o2ExlHjISnrPgrT%2F9IxmCKcSQOb6hKCYUPDXP3Ag%2BLT4yGsG9yYkXBM%2BEYDoy6%2B9WNI7FrXWzVVo7WYz1EVPodDaITguYzCjk5MrQ0TzgTMQD5Dxz8wArq27FaHHBHv5Yox9bL0%2BLFR43%2Fh4tpSu74ePqEVLxDGsJB1eeGbKJAReekS1xQvCMM5HeoOaZm2eGLJDmgmBHcgSP3YeERDDnzJjGySXrRTAmbFkRPNp7IxBMzTMzgvXTcvIzmva%2FrFnT6yTMjWJO3ps0mJtGtZo988yNNU7%2BhixYawfDxu%2Fb1TPP3FgbUJr7C2HNmSqE2TPP3FijA5g%2BcvOu9CBaF2F7tHSDnfIWuf8Pfm9h%2Fh2dF03g1DLByBEeN3IYEqGMG6B1VC1AWd%2F3AHcssyLNeQkHOLunAja4G8ca3iYrgEgSBSTsgl5NlI1WiuyS8inMdiDJil71RxhljXBF%2BWT5IhYOIwc1F7bYOVdOEQtJ5De5XeZ4Ae6Sy7lnTEKxMXfauo5JPFX2i0gWiqAxM9oiNrg5MmzIcoo29VdmvKB4LhTT2lJ8IooACUeLgg0jATE55otIVijOYIOxMRuKDebLRXVCtisX5ee7TMIMFAE4jikoNiQ5xTf7mcWVnFnGB8qMnonmZhYBmXn2i8huFow270kUzxigYUOWU1it1%2FL7lVVerxE5N5J%2FN9%2Fbnkj%2BKj0TzY03Tm6ZJHgz9cliJj0TzY032tfKvLiMF6YRvYWtSDuSZ6i703yTK9RNGF6iPVP795IEmtkWvKMlgWZagqOnNitLIcKGduQysBiYGaumdcXonmhuFHMKG%2FXa0C8ongvFGLINFB8qlnGsKNt5yYKVdfzq%2Bd%2FWBZKXfrkZGEo%2BRkmUR9AsYCUgyyJoBa8CrGNR5SMkCEdpFoEQ0RrSkSUc5WiyM%2BFYR5ZiQs6xWwzZZgqjCNUqx3ffFsoTokO0jizxO1c285LkidEhApIneIcInN%2BrLE4nllaPrmak8Mb5FFKHU1FFv834C6urXvNzbiRP67VPvqOGNDgnwqxjmVojdnPiztScfH1p8GZNo0Q1q2eiuY%2BEHlIUcLRsWbJCAdIKFV756dKeWVk766aR2DAvBSrRTqzLPFk0XCFBgauPd15Eb3HDNThOJBAY%2B47zrdpS5ttxcSH17rf958LYcikMYm%2Fk0acWmUc2J%2BRVS4nh%2BpvvRdi9xaCA47LOlCO0TxYmWZR49NmYPI%2B01YnddVmbsLGOuZxxE0JXJPlPvr8%2Brz0Cj1nRBHo5R1VVxh7d%2Fj7NBFO9Sh41xpHq2WeP6Z1E%2F3L2GM1YXUeK9R49Jm6Pzq7XbjDJjZeL36eZcdIYi1Nm226SCauXsNe4UKdruBc4FnZ67EsZMNt0uoSJeGbdGwqVrMpMOXS7xK7z1qjDcXnWvzFhhjc2eNEr5%2BkVrC96FQve%2F0MSxcIwvz5LcQQAQ7XYjBMXZ1MtPjBuPt3%2Bmby7TeHE98pqs9tjNSy%2F5zHrOXRsQjIGMsDgPfvmPe7d0aEsJrYnqejmmJJj3KIqWvc9tt17z%2BLcg2CYpNrtL0gUI%2BJBcqYUJGepJ5Mc45ZekrM4kFwnPhq65EOU5fXxyLieUPHBFv31oicvK%2BCHwlyxV25mUo7dpWEWJuUWKFIqI5blxtfP0YUexvErGW9YPvQbb0MzGpyiAvTKutfoCHLx%2FMLSlAzrba7TOzoNjwa0PkolZWwpoUYvL0A0BvYUuOBX5m2YeNVJ4j6ESZgu6CPGt1EQxMd87zb4m7Kg02w4k0oVGt4sqa7OJtXpapD7kLFq76eDtu3KCG2zU4dKE%2F44TRPy9%2F5wVKM%2Frj551vWI36U5Fzi2gS22sfl%2BW7MuHOdI4I5TbJOxbeytl%2BNCJvG6i2EhO4ZwC5nW%2BJ9B7sXYyVghY0mqciamvudbBEY7cbgILOtdatZYX5auv3r%2FgC8J30Ih%2FvtnATql2A1z5W2j%2BLm8ZQuge1gCu%2B4%2F7JapVLtlKkjzLStld1m8BpSFja4ST6gnARXO6CVuC80sEAL7N7cgCGPU8KpoTQEcWV9hqJkF3GDLDfqNyNhEcDIhsPvGqvVYTCujptEO05TIqXt8UBaGmmVpqFkXh%2BLxJabq8ZjAYUOTxFF%2FATDUXpA5alGLy8azS9oe8nV1V%2F1hBwYwEQvUI3XrAAnl%2BdBeiFncXrJE3YfYAndVrFH3GY3bEIfj9nXj%2BSTYi8sa9s3GNkVU4yjSkW%2BZpIntJgHFuJ3%2B87EI0RGBzF2ZMaJuqvC8tk57YpdB5EfQ%2BBToHWgzgpxVEM2AOGmKDYD4omLqho12YGf91f8B%3C%2Fdiagram%3E%3C%2Fmxfile%3E)

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
