# Ponte: projeto do app ⇄ projeto do site

Este arquivo é mantido pelo projeto **Folha a Folha** (o app). O projeto do **site** o lê. Só entra aqui o que é público: versões, links, guia e pedidos. Nada interno, nenhuma chave, nenhum dado de cliente.

Última atualização: 2026-11-26 (guia: endereço reservado)

## Estado atual do app
- Windows: 2.7.0 publicada.
- Linux: 2.7.0 publicada.
- Android e iPhone: ainda não existem para download. Não pôr botão.
- 2.8.0 (português do Brasil e inglês no app): em preparação, **não publicada**.
- Guia de uso (para pessoas e para IA de atendimento): **endereço reservado, conteúdo ainda em preparação** (as páginas dizem isso). O conteúdo completo sai junto com a 2.8.0.
  - Português: https://github.com/Primor-Labs-Admin/folha-a-folha-downloads/blob/main/guia/pt-BR/guia-de-uso.md
  - English: https://github.com/Primor-Labs-Admin/folha-a-folha-downloads/blob/main/guia/en/user-guide.md
  - Índice: https://github.com/Primor-Labs-Admin/folha-a-folha-downloads/blob/main/guia/README.md

## Links fixos
- Windows: https://github.com/Primor-Labs-Admin/folha-a-folha-downloads/raw/main/Folha-a-Folha-Windows.zip
- Linux: https://github.com/Primor-Labs-Admin/folha-a-folha-downloads/raw/main/Folha-a-Folha-Linux.zip
- Conferência dos arquivos: `SHA256SUMS.txt` neste repositório.

## Pedidos do app para o site
- Botões de download apontando para os links acima (texto em português e inglês).
- Link "Guia de uso" / "User guide" no site, apontando para o endereço do guia acima (já reservado; o aviso "em preparação" some quando o conteúdo sair).

## Como as duas pontas se avisam
- O projeto do app atualiza este arquivo a cada versão aprovada ou mudança que afete o site.
- O projeto do site, ao mexer em download, preço, texto sobre o app ou guia, lê este arquivo primeiro (endereço bruto: https://raw.githubusercontent.com/Primor-Labs-Admin/folha-a-folha-downloads/main/PONTE.md).
- O projeto do site deixa seus recados para o app em `PONTE.md` no repositório `primor-labs-site`, que o projeto do app lê antes de mexer em download, guia ou versão.
