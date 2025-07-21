# Desafio-iPhone-Dio


# 📱 Desafio iPhone - Programação Orientada a Objetos com Java

Este projeto foi desenvolvido como parte de um desafio proposto durante o curso de Análise e Desenvolvimento de Sistemas, com o objetivo de aplicar os conceitos de **POO (Programação Orientada a Objetos)** e **modelagem UML** em Java, simulando funcionalidades inspiradas no lançamento do iPhone 2007.

## 💡 Objetivo

Representar os diferentes papéis do iPhone utilizando interfaces e classes, com base nos conceitos de coesão e responsabilidade única. As funções simuladas são:

- Reprodutor Musical 🎵  
- Aparelho Telefônico 📞  
- Navegador de Internet 🌐  

## 🔧 Tecnologias Utilizadas

- Java (JDK 17+)
- IDE: Intelij
- UML: diagrams.net (draw.io)
- Git & GitHub
<mxfile host="app.diagrams.net" agent="Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/134.0.0.0 Safari/537.36 OPR/119.0.0.0" version="28.0.6">
  <diagram name="IphoneUML" id="AmRszyQjqKVKuHTWl8Pw">
    <mxGraphModel dx="831" dy="444" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" background="none" math="0" shadow="1">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="SPMzj2UWLE0KQYM0oHje-1" value="ReprodutorMusical" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=26;fillColor=none;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="110" y="100" width="140" height="104" as="geometry" />
        </mxCell>
        <mxCell id="SPMzj2UWLE0KQYM0oHje-2" value="+&amp;nbsp; tocar()" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="SPMzj2UWLE0KQYM0oHje-1">
          <mxGeometry y="26" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="SPMzj2UWLE0KQYM0oHje-3" value="+&amp;nbsp; pausar()" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="SPMzj2UWLE0KQYM0oHje-1">
          <mxGeometry y="52" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="SPMzj2UWLE0KQYM0oHje-4" value="+&amp;nbsp; selecionarMusica()" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="SPMzj2UWLE0KQYM0oHje-1">
          <mxGeometry y="78" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="SPMzj2UWLE0KQYM0oHje-6" value="AparelhoTelefonico" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=26;fillColor=none;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="390" y="100" width="140" height="104" as="geometry" />
        </mxCell>
        <mxCell id="SPMzj2UWLE0KQYM0oHje-7" value="+ Ligar()" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="SPMzj2UWLE0KQYM0oHje-6">
          <mxGeometry y="26" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="SPMzj2UWLE0KQYM0oHje-8" value="+ Atender()" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="SPMzj2UWLE0KQYM0oHje-6">
          <mxGeometry y="52" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="SPMzj2UWLE0KQYM0oHje-9" value="+ recusarChamada()" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="SPMzj2UWLE0KQYM0oHje-6">
          <mxGeometry y="78" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="SPMzj2UWLE0KQYM0oHje-22" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" edge="1" parent="1" source="SPMzj2UWLE0KQYM0oHje-10" target="SPMzj2UWLE0KQYM0oHje-18">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="SPMzj2UWLE0KQYM0oHje-10" value="iphone" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=26;fillColor=none;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="250" y="260" width="140" height="130" as="geometry" />
        </mxCell>
        <mxCell id="SPMzj2UWLE0KQYM0oHje-11" value="+ tocar()" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="SPMzj2UWLE0KQYM0oHje-10">
          <mxGeometry y="26" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="SPMzj2UWLE0KQYM0oHje-23" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="SPMzj2UWLE0KQYM0oHje-10" source="SPMzj2UWLE0KQYM0oHje-12">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="210" y="-50" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="SPMzj2UWLE0KQYM0oHje-24" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="SPMzj2UWLE0KQYM0oHje-10" source="SPMzj2UWLE0KQYM0oHje-12">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="-70" y="-50" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="SPMzj2UWLE0KQYM0oHje-12" value="+ pausar()" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="SPMzj2UWLE0KQYM0oHje-10">
          <mxGeometry y="52" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="SPMzj2UWLE0KQYM0oHje-13" value="+ ligar()" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="SPMzj2UWLE0KQYM0oHje-10">
          <mxGeometry y="78" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="SPMzj2UWLE0KQYM0oHje-14" value="+ ..." style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="SPMzj2UWLE0KQYM0oHje-10">
          <mxGeometry y="104" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="SPMzj2UWLE0KQYM0oHje-18" value="NavegadorDeInternet" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=26;fillColor=none;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="250" y="470" width="140" height="104" as="geometry" />
        </mxCell>
        <mxCell id="SPMzj2UWLE0KQYM0oHje-19" value="+ exibirPagina()" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="SPMzj2UWLE0KQYM0oHje-18">
          <mxGeometry y="26" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="SPMzj2UWLE0KQYM0oHje-20" value="+ adicionarNovaAba()" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="SPMzj2UWLE0KQYM0oHje-18">
          <mxGeometry y="52" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="SPMzj2UWLE0KQYM0oHje-21" value="+ atualizarPagina()" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="SPMzj2UWLE0KQYM0oHje-18">
          <mxGeometry y="78" width="140" height="26" as="geometry" />
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>


## 📐 Diagrama UML

O diagrama de classes representa o iPhone como uma classe concreta que **implementa** três interfaces:  
`ReprodutorMusical`, `AparelhoTelefonico` e `NavegadorInternet`.



