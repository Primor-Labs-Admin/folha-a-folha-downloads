# Ponte: projeto do app ⇄ projeto do site

Este arquivo é mantido pelo projeto **Folha a Folha** (o app). O projeto do **site** o lê. Só entra aqui o que é público: versões, links, guia e pedidos. Nada interno, nenhuma chave, nenhum dado de cliente.

Última atualização: 2026-11-26

## Estado atual do app
- Windows: 2.7.0 publicada.
- Linux: 2.7.0 publicada.
- Android e iPhone: ainda não existem para download. Não pôr botão.
- 2.8.0 (português do Brasil e inglês no app): em preparação, **não publicada**.
- Guia de uso (para pessoas e para IA de atendimento): **ainda não publicado**. Previsto junto com a 2.8.0, na pasta `guia/` deste repositório, em português e inglês.

## Links fixos
- Windows: https://github.com/Primor-Labs-Admin/folha-a-folha-downloads/raw/main/Folha-a-Folha-Windows.zip
- Linux: https://github.com/Primor-Labs-Admin/folha-a-folha-downloads/raw/main/Folha-a-Folha-Linux.zip
- Conferência dos arquivos: `SHA256SUMS.txt` neste repositório.

## Pedidos do app para o site
- Botões de download apontando para os links acima (texto em português e inglês).
- Quando o guia sair, o site ganha um link para ele (o endereço será escrito aqui).

## Como as duas pontas se avisam
- O projeto do app atualiza este arquivo a cada versão aprovada ou mudança que afete o site.
- O projeto do site, ao mexer em download, preço, texto sobre o app ou guia, lê este arquivo primeiro (endereço bruto: https://raw.githubusercontent.com/Primor-Labs-Admin/folha-a-folha-downloads/main/PONTE.md).
- O projeto do site deixa seus recados para o app em `PONTE.md` no repositório `primor-labs-site`, que o projeto do app lê antes de mexer em download, guia ou versão.
