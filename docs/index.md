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

[Uploading Diagrama sem nome…]()<mxfile host="app.diagrams.net" agent="Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/127.0.0.0 Safari/537.36 OPR/113.0.0.0" version="24.7.14">
  <diagram name="Página-1" id="g9BKU89KwJ0dT-WAyuCA">
    <mxGraphModel grid="1" page="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" pageScale="1" pageWidth="1200" pageHeight="1920" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="0JdKgsKZo1z9jTX0cI1i-32" value="" style="endArrow=none;html=1;rounded=0;fontSize=12;startSize=8;endSize=8;curved=1;" edge="1" parent="1">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="498" y="890" as="sourcePoint" />
            <mxPoint x="510" y="890" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-95" value="" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="505" y="865" width="75" height="50" as="geometry" />
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-99" value="" style="endArrow=none;html=1;rounded=0;exitX=0;exitY=0.5;exitDx=0;exitDy=0;" edge="1" parent="1">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="55" y="1070" as="sourcePoint" />
            <mxPoint x="43" y="930" as="targetPoint" />
            <Array as="points">
              <mxPoint x="43" y="1070" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="co4DRMUnJMrighV0fhpu-4" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0;exitY=0.5;exitDx=0;exitDy=0;endArrow=none;endFill=0;" edge="1" parent="1">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="43" y="1010.2" as="targetPoint" />
            <mxPoint x="52.99999999999994" y="1010" as="sourcePoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-97" value="" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="50" y="985" width="75" height="50" as="geometry" />
        </mxCell>
        <mxCell id="qLJwsBMPwXCCiPxbqdgQ-11" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" edge="1" parent="1" source="qLJwsBMPwXCCiPxbqdgQ-3" target="qLJwsBMPwXCCiPxbqdgQ-4">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="qLJwsBMPwXCCiPxbqdgQ-3" value="tela de login" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="460" y="140" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="qLJwsBMPwXCCiPxbqdgQ-8" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;endArrow=none;endFill=0;" edge="1" parent="1" source="qLJwsBMPwXCCiPxbqdgQ-4">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="680" y="170" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="qLJwsBMPwXCCiPxbqdgQ-4" value="login/senha estao corretos" style="rhombus;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="472.5" y="240" width="95" height="100" as="geometry" />
        </mxCell>
        <mxCell id="qLJwsBMPwXCCiPxbqdgQ-6" value="coordenador " style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="229" y="440" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="qLJwsBMPwXCCiPxbqdgQ-7" value="não" style="text;html=1;align=center;verticalAlign=middle;whiteSpace=wrap;rounded=0;" vertex="1" parent="1">
          <mxGeometry x="590" y="260" width="60" height="30" as="geometry" />
        </mxCell>
        <mxCell id="qLJwsBMPwXCCiPxbqdgQ-12" value="sim" style="text;html=1;align=center;verticalAlign=middle;whiteSpace=wrap;rounded=0;" vertex="1" parent="1">
          <mxGeometry x="470" y="350" width="60" height="30" as="geometry" />
        </mxCell>
        <mxCell id="qLJwsBMPwXCCiPxbqdgQ-15" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=1;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" target="qLJwsBMPwXCCiPxbqdgQ-3">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="680" y="170" as="sourcePoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="ix7RVtfB-RM8CXBXsG4B-2" value="" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="qLJwsBMPwXCCiPxbqdgQ-16" target="qLJwsBMPwXCCiPxbqdgQ-20">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="757.5" y="530" />
              <mxPoint x="757.5" y="530" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="qLJwsBMPwXCCiPxbqdgQ-16" value="professor" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="667.5" y="440" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="ix7RVtfB-RM8CXBXsG4B-5" style="rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.5;entryY=0;entryDx=0;entryDy=0;edgeStyle=orthogonalEdgeStyle;" edge="1" parent="1" target="Sdm1NYs_VI7uktK-7t2f-14">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="292.5" y="600" as="sourcePoint" />
            <mxPoint x="192.5" y="650" as="targetPoint" />
            <Array as="points">
              <mxPoint x="289" y="600" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="ix7RVtfB-RM8CXBXsG4B-6" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" edge="1" parent="1" target="Sdm1NYs_VI7uktK-7t2f-16">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="340" y="600" as="sourcePoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="0JdKgsKZo1z9jTX0cI1i-10" style="edgeStyle=none;curved=1;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;fontSize=12;startSize=8;endSize=8;" edge="1" parent="1" source="qLJwsBMPwXCCiPxbqdgQ-20" target="0JdKgsKZo1z9jTX0cI1i-2">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="qLJwsBMPwXCCiPxbqdgQ-20" value="Sistema de faltas" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="665.03" y="570" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="Sdm1NYs_VI7uktK-7t2f-2" value="" style="ellipse;html=1;shape=startState;fillColor=#000000;strokeColor=#ff0000;" vertex="1" parent="1">
          <mxGeometry x="505" y="50" width="30" height="30" as="geometry" />
        </mxCell>
        <mxCell id="Sdm1NYs_VI7uktK-7t2f-3" value="" style="edgeStyle=orthogonalEdgeStyle;html=1;verticalAlign=bottom;endArrow=open;endSize=8;strokeColor=#ff0000;rounded=0;" edge="1" parent="1" source="Sdm1NYs_VI7uktK-7t2f-2">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="520" y="140" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="Sdm1NYs_VI7uktK-7t2f-4" value="" style="rounded=0;whiteSpace=wrap;html=1;fillColor=#000000;" vertex="1" parent="1">
          <mxGeometry x="460" y="390" width="120" height="20" as="geometry" />
        </mxCell>
        <mxCell id="Sdm1NYs_VI7uktK-7t2f-6" value="" style="endArrow=classic;html=1;rounded=0;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" edge="1" parent="1" source="qLJwsBMPwXCCiPxbqdgQ-4" target="Sdm1NYs_VI7uktK-7t2f-4">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="540" y="440" as="sourcePoint" />
            <mxPoint x="590" y="390" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="Sdm1NYs_VI7uktK-7t2f-9" value="" style="endArrow=classic;html=1;rounded=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;exitX=1;exitY=0.5;exitDx=0;exitDy=0;" edge="1" parent="1" source="Sdm1NYs_VI7uktK-7t2f-4" target="qLJwsBMPwXCCiPxbqdgQ-16">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="420" y="440" as="sourcePoint" />
            <mxPoint x="470" y="390" as="targetPoint" />
            <Array as="points">
              <mxPoint x="500" y="400" />
              <mxPoint x="728" y="400" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="Sdm1NYs_VI7uktK-7t2f-11" value="" style="endArrow=classic;html=1;rounded=0;exitX=0;exitY=0.5;exitDx=0;exitDy=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;edgeStyle=orthogonalEdgeStyle;" edge="1" parent="1" source="Sdm1NYs_VI7uktK-7t2f-4" target="qLJwsBMPwXCCiPxbqdgQ-6">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="420" y="440" as="sourcePoint" />
            <mxPoint x="470" y="390" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="Sdm1NYs_VI7uktK-7t2f-12" value="" style="endArrow=classic;html=1;rounded=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;edgeStyle=orthogonalEdgeStyle;" edge="1" parent="1" source="qLJwsBMPwXCCiPxbqdgQ-6" target="qLJwsBMPwXCCiPxbqdgQ-20">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="520" y="500" as="sourcePoint" />
            <mxPoint x="580" y="500" as="targetPoint" />
            <Array as="points">
              <mxPoint x="330" y="535" />
              <mxPoint x="725" y="535" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="Sdm1NYs_VI7uktK-7t2f-13" value="" style="endArrow=classic;html=1;rounded=0;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" edge="1" parent="1">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="288.71" y="500" as="sourcePoint" />
            <mxPoint x="288.71" y="570" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="Sdm1NYs_VI7uktK-7t2f-14" value="turma" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="249" y="660" width="80" height="40" as="geometry" />
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-110" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0;exitY=0.5;exitDx=0;exitDy=0;entryX=1;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" source="Sdm1NYs_VI7uktK-7t2f-16" target="q9ttVI1c6m5Sk-QhymPg-106">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="Sdm1NYs_VI7uktK-7t2f-16" value="professores" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="490" y="660" width="80" height="40" as="geometry" />
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-118" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=1;exitY=0.5;exitDx=0;exitDy=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" source="Sdm1NYs_VI7uktK-7t2f-17" target="q9ttVI1c6m5Sk-QhymPg-112">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="Sdm1NYs_VI7uktK-7t2f-17" value="alunos" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="20" y="660" width="80" height="40" as="geometry" />
        </mxCell>
        <mxCell id="ix7RVtfB-RM8CXBXsG4B-9" value="Banco de dados" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="229" y="570" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="Sdm1NYs_VI7uktK-7t2f-19" value="" style="endArrow=none;html=1;rounded=0;" edge="1" parent="1">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="43" y="950" as="sourcePoint" />
            <mxPoint x="42.5" y="700" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="Sdm1NYs_VI7uktK-7t2f-20" value="" style="endArrow=none;html=1;rounded=0;" edge="1" parent="1" source="Sdm1NYs_VI7uktK-7t2f-21">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="42.5" y="730" as="sourcePoint" />
            <mxPoint x="90" y="730" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="Sdm1NYs_VI7uktK-7t2f-22" value="" style="endArrow=none;html=1;rounded=0;" edge="1" parent="1" target="Sdm1NYs_VI7uktK-7t2f-21">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="42.5" y="730" as="sourcePoint" />
            <mxPoint x="90" y="730" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="Sdm1NYs_VI7uktK-7t2f-21" value="cpf" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="50" y="710" width="65" height="40" as="geometry" />
        </mxCell>
        <mxCell id="Sdm1NYs_VI7uktK-7t2f-23" value="" style="endArrow=none;html=1;rounded=0;" edge="1" parent="1" source="Sdm1NYs_VI7uktK-7t2f-24">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="42.5" y="780" as="sourcePoint" />
            <mxPoint x="90" y="780" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="Sdm1NYs_VI7uktK-7t2f-24" value="&lt;u&gt;matrícula&lt;/u&gt;" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="50" y="760" width="65" height="40" as="geometry" />
        </mxCell>
        <mxCell id="Sdm1NYs_VI7uktK-7t2f-25" value="" style="endArrow=none;html=1;rounded=0;" edge="1" parent="1" source="Sdm1NYs_VI7uktK-7t2f-26">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="42.5" y="830" as="sourcePoint" />
            <mxPoint x="90" y="830" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="Sdm1NYs_VI7uktK-7t2f-27" value="" style="endArrow=none;html=1;rounded=0;" edge="1" parent="1" source="Sdm1NYs_VI7uktK-7t2f-28">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="42.5" y="890" as="sourcePoint" />
            <mxPoint x="90" y="890" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="Sdm1NYs_VI7uktK-7t2f-29" value="" style="endArrow=none;html=1;rounded=0;" edge="1" parent="1" source="Sdm1NYs_VI7uktK-7t2f-30">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="42.5" y="950" as="sourcePoint" />
            <mxPoint x="90" y="950" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="Sdm1NYs_VI7uktK-7t2f-31" value="" style="endArrow=none;html=1;rounded=0;" edge="1" parent="1" target="Sdm1NYs_VI7uktK-7t2f-24">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="42.5" y="780" as="sourcePoint" />
            <mxPoint x="92.5" y="730" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="Sdm1NYs_VI7uktK-7t2f-32" value="" style="endArrow=none;html=1;rounded=0;" edge="1" parent="1">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="42" y="830" as="sourcePoint" />
            <mxPoint x="52" y="830" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="Sdm1NYs_VI7uktK-7t2f-33" value="" style="endArrow=none;html=1;rounded=0;" edge="1" parent="1">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="43" y="890" as="sourcePoint" />
            <mxPoint x="53" y="890" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="Sdm1NYs_VI7uktK-7t2f-34" value="" style="endArrow=none;html=1;rounded=0;" edge="1" parent="1">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="83" y="950" as="sourcePoint" />
            <mxPoint x="43" y="950" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="Sdm1NYs_VI7uktK-7t2f-30" value="código da turma" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="50" y="930" width="65" height="40" as="geometry" />
        </mxCell>
        <mxCell id="Sdm1NYs_VI7uktK-7t2f-26" value="nome" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="50" y="810" width="65" height="40" as="geometry" />
        </mxCell>
        <mxCell id="Sdm1NYs_VI7uktK-7t2f-28" value="&lt;font style=&quot;font-size: 8px;&quot;&gt;Informações dos Responsáveis&lt;/font&gt;" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="50" y="870" width="65" height="40" as="geometry" />
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-15" value="" style="endArrow=none;html=1;rounded=0;" edge="1" parent="1">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="498" y="950" as="sourcePoint" />
            <mxPoint x="497.5" y="700" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-16" value="" style="endArrow=none;html=1;rounded=0;" edge="1" parent="1" source="q9ttVI1c6m5Sk-QhymPg-18">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="497.5" y="730" as="sourcePoint" />
            <mxPoint x="545" y="730" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-17" value="" style="endArrow=none;html=1;rounded=0;" edge="1" parent="1" target="q9ttVI1c6m5Sk-QhymPg-18">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="497.5" y="730" as="sourcePoint" />
            <mxPoint x="545" y="730" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-18" value="cpf" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="505" y="710" width="65" height="40" as="geometry" />
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-19" value="" style="endArrow=none;html=1;rounded=0;" edge="1" parent="1" source="q9ttVI1c6m5Sk-QhymPg-20">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="497.5" y="780" as="sourcePoint" />
            <mxPoint x="545" y="780" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-20" value="&lt;u&gt;ctps&lt;/u&gt;" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="505" y="760" width="65" height="40" as="geometry" />
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-21" value="" style="endArrow=none;html=1;rounded=0;" edge="1" parent="1" source="q9ttVI1c6m5Sk-QhymPg-29">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="497.5" y="830" as="sourcePoint" />
            <mxPoint x="545" y="830" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-23" value="" style="endArrow=none;html=1;rounded=0;" edge="1" parent="1" source="q9ttVI1c6m5Sk-QhymPg-28">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="497.5" y="950" as="sourcePoint" />
            <mxPoint x="545" y="950" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-24" value="" style="endArrow=none;html=1;rounded=0;" edge="1" parent="1" target="q9ttVI1c6m5Sk-QhymPg-20">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="497.5" y="780" as="sourcePoint" />
            <mxPoint x="547.5" y="730" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-25" value="" style="endArrow=none;html=1;rounded=0;" edge="1" parent="1">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="497" y="830" as="sourcePoint" />
            <mxPoint x="507" y="830" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-27" value="" style="endArrow=none;html=1;rounded=0;" edge="1" parent="1">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="538" y="950" as="sourcePoint" />
            <mxPoint x="498" y="950" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-28" value="salário" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="505" y="930" width="65" height="40" as="geometry" />
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-29" value="nome" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="505" y="810" width="65" height="40" as="geometry" />
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-77" value="" style="endArrow=none;html=1;rounded=0;" edge="1" parent="1">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="257" y="950" as="sourcePoint" />
            <mxPoint x="256.5" y="700" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-78" value="" style="endArrow=none;html=1;rounded=0;" edge="1" parent="1" source="q9ttVI1c6m5Sk-QhymPg-80">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="256.5" y="730" as="sourcePoint" />
            <mxPoint x="304" y="730" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-79" value="" style="endArrow=none;html=1;rounded=0;" edge="1" parent="1" target="q9ttVI1c6m5Sk-QhymPg-80">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="256.5" y="730" as="sourcePoint" />
            <mxPoint x="304" y="730" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-80" value="matrí&lt;span style=&quot;background-color: initial;&quot;&gt;cula alunos&lt;/span&gt;" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="264" y="710" width="65" height="40" as="geometry" />
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-81" value="" style="endArrow=none;html=1;rounded=0;" edge="1" parent="1" source="q9ttVI1c6m5Sk-QhymPg-82">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="256.5" y="780" as="sourcePoint" />
            <mxPoint x="304" y="780" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-82" value="ctps professor" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="264" y="760" width="65" height="40" as="geometry" />
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-83" value="" style="endArrow=none;html=1;rounded=0;" edge="1" parent="1" source="q9ttVI1c6m5Sk-QhymPg-91">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="256.5" y="830" as="sourcePoint" />
            <mxPoint x="304" y="830" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-84" value="" style="endArrow=none;html=1;rounded=0;" edge="1" parent="1">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="329" y="890" as="sourcePoint" />
            <mxPoint x="304" y="890" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-86" value="" style="endArrow=none;html=1;rounded=0;" edge="1" parent="1" target="q9ttVI1c6m5Sk-QhymPg-82">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="256.5" y="780" as="sourcePoint" />
            <mxPoint x="306.5" y="730" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-87" value="" style="endArrow=none;html=1;rounded=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="257" y="890" as="sourcePoint" />
            <mxPoint x="271" y="890" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-88" value="" style="endArrow=none;html=1;rounded=0;" edge="1" parent="1">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="256" y="830" as="sourcePoint" />
            <mxPoint x="266" y="830" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-90" value="&lt;u&gt;código da turma&lt;/u&gt;" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="264" y="870" width="65" height="40" as="geometry" />
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-91" value="série" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="264" y="810" width="65" height="40" as="geometry" />
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-93" value="telefone dos pais" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="55" y="990" width="65" height="40" as="geometry" />
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-103" value="" style="endArrow=classic;html=1;rounded=0;exitX=0;exitY=0.5;exitDx=0;exitDy=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;edgeStyle=orthogonalEdgeStyle;" edge="1" parent="1" target="Sdm1NYs_VI7uktK-7t2f-17">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="228" y="600" as="sourcePoint" />
            <mxPoint x="59" y="660" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-117" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0;exitY=0.5;exitDx=0;exitDy=0;entryX=1;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" source="q9ttVI1c6m5Sk-QhymPg-106" target="Sdm1NYs_VI7uktK-7t2f-14">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-106" value="ensinam" style="rhombus;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="380" y="660" width="60" height="40" as="geometry" />
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-119" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=1;exitY=0.5;exitDx=0;exitDy=0;" edge="1" parent="1" source="q9ttVI1c6m5Sk-QhymPg-112">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="250" y="680" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-112" value="cursam" style="rhombus;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="140" y="660" width="60" height="40" as="geometry" />
        </mxCell>
        <mxCell id="0JdKgsKZo1z9jTX0cI1i-13" style="edgeStyle=none;curved=1;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;fontSize=12;startSize=8;endSize=8;" edge="1" parent="1" source="0JdKgsKZo1z9jTX0cI1i-2" target="0JdKgsKZo1z9jTX0cI1i-12">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="0JdKgsKZo1z9jTX0cI1i-2" value="Data" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="665.03" y="660" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="0JdKgsKZo1z9jTX0cI1i-7" value="" style="endArrow=none;html=1;rounded=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="256.5" y="949.57" as="sourcePoint" />
            <mxPoint x="270.5" y="949.57" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="0JdKgsKZo1z9jTX0cI1i-8" value="sala física" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="267.5" y="930" width="65" height="40" as="geometry" />
        </mxCell>
        <mxCell id="0JdKgsKZo1z9jTX0cI1i-34" style="edgeStyle=none;curved=1;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;fontSize=12;startSize=8;endSize=8;" edge="1" parent="1" source="0JdKgsKZo1z9jTX0cI1i-12" target="0JdKgsKZo1z9jTX0cI1i-33">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="0JdKgsKZo1z9jTX0cI1i-12" value="Turma" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="665.03" y="750" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="co4DRMUnJMrighV0fhpu-2" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=1;exitY=0.5;exitDx=0;exitDy=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" edge="1" parent="1" source="0JdKgsKZo1z9jTX0cI1i-14" target="0JdKgsKZo1z9jTX0cI1i-26">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="837.53" y="960" />
              <mxPoint x="837.53" y="1020" />
              <mxPoint x="777.53" y="1020" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="co4DRMUnJMrighV0fhpu-3" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0;exitY=0.5;exitDx=0;exitDy=0;" edge="1" parent="1" source="0JdKgsKZo1z9jTX0cI1i-14" target="0JdKgsKZo1z9jTX0cI1i-25">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="617.53" y="960" />
              <mxPoint x="617.53" y="1020" />
              <mxPoint x="677.53" y="1020" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="0JdKgsKZo1z9jTX0cI1i-14" value="Lista de alunos com caixas assinalaveis de presença" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="665.03" y="930" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="0JdKgsKZo1z9jTX0cI1i-38" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;fontSize=12;startSize=8;endSize=8;" edge="1" parent="1" source="0JdKgsKZo1z9jTX0cI1i-25" target="0JdKgsKZo1z9jTX0cI1i-37">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="0JdKgsKZo1z9jTX0cI1i-25" value="Falta" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="637.53" y="1050" width="80" height="40" as="geometry" />
        </mxCell>
        <mxCell id="0JdKgsKZo1z9jTX0cI1i-26" value="Presença" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="737.53" y="1050" width="80" height="40" as="geometry" />
        </mxCell>
        <mxCell id="0JdKgsKZo1z9jTX0cI1i-29" value="Faltou" style="text;html=1;align=center;verticalAlign=middle;whiteSpace=wrap;rounded=0;fontSize=10;" vertex="1" parent="1">
          <mxGeometry x="637.53" y="1000" width="20" height="10" as="geometry" />
        </mxCell>
        <mxCell id="0JdKgsKZo1z9jTX0cI1i-30" value="Veio" style="text;html=1;align=center;verticalAlign=middle;whiteSpace=wrap;rounded=0;fontSize=10;" vertex="1" parent="1">
          <mxGeometry x="797.53" y="1000" width="20" height="10" as="geometry" />
        </mxCell>
        <mxCell id="0JdKgsKZo1z9jTX0cI1i-35" style="edgeStyle=none;curved=1;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;fontSize=12;startSize=8;endSize=8;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" edge="1" parent="1" source="0JdKgsKZo1z9jTX0cI1i-33" target="0JdKgsKZo1z9jTX0cI1i-14">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="728.12" y="900" as="sourcePoint" />
            <mxPoint x="726.885" y="930" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="0JdKgsKZo1z9jTX0cI1i-33" value="Matéria" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="665.03" y="840" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="0JdKgsKZo1z9jTX0cI1i-36" value="Total de faltas" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="55" y="1050" width="65" height="40" as="geometry" />
        </mxCell>
        <mxCell id="q9ttVI1c6m5Sk-QhymPg-94" value="telefones&lt;span style=&quot;color: rgba(0, 0, 0, 0); font-family: monospace; font-size: 0px; text-align: start; text-wrap: nowrap;&quot;&gt;%3CmxGraphModel%3E%3Croot%3E%3CmxCell%20id%3D%220%22%2F%3E%3CmxCell%20id%3D%221%22%20parent%3D%220%22%2F%3E%3CmxCell%20id%3D%222%22%20value%3D%22codigo%20da%20turma%22%20style%3D%22ellipse%3BwhiteSpace%3Dwrap%3Bhtml%3D1%3B%22%20vertex%3D%221%22%20parent%3D%221%22%3E%3CmxGeometry%20x%3D%22360%22%20y%3D%22930%22%20width%3D%2265%22%20height%3D%2240%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3C%2Froot%3E%3C%2FmxGraphModel%3E&lt;/span&gt;" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="510" y="870" width="65" height="40" as="geometry" />
        </mxCell>
        <mxCell id="0JdKgsKZo1z9jTX0cI1i-37" value="Lista de faltas" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="617.53" y="1160" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="0JdKgsKZo1z9jTX0cI1i-39" value="Adiciona" style="text;html=1;align=center;verticalAlign=middle;whiteSpace=wrap;rounded=0;fontSize=12;" vertex="1" parent="1">
          <mxGeometry x="617.53" y="1110" width="60" height="30" as="geometry" />
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>



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
