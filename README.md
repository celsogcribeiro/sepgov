# SEPDATA - Monitoramento CEGOVE

Painel web de monitoramento das contratações de soluções de TIC da Secretaria de Tecnologia da Informação do Conselho da Justiça Federal.

Acesse em: [sepdata.com.br](https://sepdata.com.br)

## Seções

- **Contratos** - vigência dos contratos de TIC, com alerta para os que vencem em até 195 dias
- **ARPs** - vigência das Atas de Registro de Preços, com o mesmo critério de alerta
- **PDTI 2024–2026** - Plano Diretor de Tecnologia da Informação ([PDF](./pdti_2024-2026.pdf))
- **PCTIC 2027** - Plano de Contratações de Soluções de TIC ([PDF](./pctic_2027.pdf))
- **Controle · PCTIC 2027** - andamento, por etapa, dos itens de nova contratação do PCTIC
- **Manual de Redação e Padronização** - manual prático para padronizar documentos e publicações ([PDF](./manual_redacao.pdf))

## Dados

| Arquivo | Conteúdo |
| --- | --- |
| `contratos.json` | Contratos de TIC (fonte: Consolidado - CTRs) |
| `arps.json` | Atas de Registro de Preços (fonte: Consolidado - ARPs) |
| `pctic_progresso.json` | Progresso dos itens do PCTIC 2027 (fonte: planilha PCTIC 2027) |

Para atualizar o painel, basta substituir o arquivo JSON correspondente. A página lê os dados a cada acesso.

## Publicação

O site é publicado pelo GitHub Pages a partir do branch `main`, com o domínio próprio `sepdata.com.br` (arquivo `CNAME`).
