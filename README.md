# Projeto de Registro de Visitas

Este projeto realiza o registro e a sincronização de visitas de colaboradores a partir de uma lista no SharePoint, integrando com dois sistemas via API para consolidar produtos, resultados e próximos passos. Foi desenvolvido a partir de um curso inicial da Microsoft voltado ao Databricks, adaptado para o contexto interno, com foco em automação, padronização e disponibilização de dados para análise.

## Funcionamento

- Foram desenvolvidos dois aplicativos:
  - Desktop (visualização e edição): consulta, filtra e atualiza a base de dados, com validações e sincronização com a lista do SharePoint e APIs dos sistemas.
  - Mobile (registro): registra visitas em campo e alimenta a base central, com suporte a modo offline e sincronização quando online.

<br>
<div align="center">
  <img src="docs\img\screen_mobile.gif" alt="Exemplo do aplicativo" height="370">
  <img src="docs\img\screen_desktop.gif" alt="Exemplo desktop" height="370">
</div>
<p align="center"><i>Exemplo do aplicativo (esquerda) e da lista (direita).</i></p>

## Data de finalização e Certificado

- Data de finalização: 28 de fevereiro de 2025
- Certificado: [Introdução aos aplicativos de tela do Power Apps](docs\certificate_microsoft_learn.pdf)
