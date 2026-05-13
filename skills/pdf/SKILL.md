# PDF Skill

## Objetivo
Gerar relatórios e documentos em PDF diretamente pelo navegador, sem dependências externas.

## Regras
- Usar window.print() com CSS @media print para relatórios simples
- Usar a biblioteca jsPDF para PDFs mais complexos com gráficos e tabelas
- Sempre incluir logo e identidade visual do sistema no PDF
- PDFs devem ser limpos, profissionais e prontos para impressão
- Nunca depender de servidor para gerar o PDF — tudo no frontend

## Stack
- window.print() + CSS @media print (relatórios simples)
- jsPDF + html2canvas (relatórios complexos com gráficos)
- Importar via CDN: https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js

## Entregáveis
- Botão "Exportar PDF" na tela relevante
- PDF gerado direto no navegador
- Layout profissional com cabeçalho, dados e rodapé
- Nome do arquivo sugestivo (ex: relatorio-janeiro-2026.pdf)

## Casos de uso no FretePro
- Relatório financeiro mensal
- Comprovante de frete individual
- Relatório de motoristas e comissões
- Extrato de abastecimentos por caminhão