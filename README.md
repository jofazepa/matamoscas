# Temas Matamoscas para Mattermost

**Matamoscas Claro** e **Matamoscas Escuro** são dois temas personalizados para o
Mattermost, desenvolvidos internamente para a DPQ.
São temas adaptados dos temas para Mattermost **github** (Matamoscas Claro) e **monokai** (Matamoscas Escuro).

Os temas utilizam a paleta institucional de três cores:

| Cor       | Hex       | Utilização                                          |
|-----------|-----------|-----------------------------------------------------|
| Azul      | `#009DE0` | Acentos: links, botões, indicações de actividade     |
| Ardósia   | `#46555F` | Barra lateral (tema claro), superfícies (tema escuro)|
| Cinzento  | `#D2D3D4` | Texto secundário e fundos neutros                    |

## Os dois temas

| Tema              | Descrição                                                                 |
|-------------------|---------------------------------------------------------------------------|
| **Matamoscas Claro** | Área de mensagens clara, com a barra lateral (menu e lista de salas) em ardósia escura |
| **Matamoscas Escuro** | Tema integralmente escuro, com o azul institucional a orientar o olhar    |

## Como aplicar

1. Abre o Mattermost e vai a **Settings → Display → Theme**.
2. Seleciona **Edit** e depois **Custom Theme**.
3. Copia o bloco completo do tema pretendido.
4. Confirma com **Save**.

## Matamoscas Claro

{
  "sidebarBg": "#46555F",
  "sidebarText": "#D2D3D4",
  "sidebarUnreadText": "#FFFFFF",
  "sidebarTextHoverBg": "#55656F",
  "sidebarTextActiveBorder": "#009DE0",
  "sidebarTextActiveColor": "#FFFFFF",
  "sidebarHeaderBg": "#39464E",
  "sidebarHeaderTextColor": "#FFFFFF",
  "onlineIndicator": "#009DE0",
  "awayIndicator": "#D2D3D4",
  "dndIndicator": "#D24C4C",
  "mentionBg": "#009DE0",
  "mentionColor": "#FFFFFF",
  "centerChannelBg": "#F7F8F8",
  "centerChannelColor": "#2E3940",
  "newMessageSeparator": "#009DE0",
  "linkColor": "#0084BF",
  "buttonBg": "#009DE0",
  "buttonColor": "#FFFFFF",
  "errorTextColor": "#C43838",
  "mentionHighlightBg": "#DFF4FC",
  "mentionHighlightLink": "#0084BF",
  "codeTheme": "github"
}

## Matamoscas Escuro
{
  "sidebarBg": "#333D45",
  "sidebarText": "#D2D3D4",
  "sidebarUnreadText": "#FFFFFF",
  "sidebarTextHoverBg": "#414F59",
  "sidebarTextActiveBorder": "#009DE0",
  "sidebarTextActiveColor": "#FFFFFF",
  "sidebarHeaderBg": "#28313A",
  "sidebarHeaderTextColor": "#FFFFFF",
  "onlineIndicator": "#009DE0",
  "awayIndicator": "#8A9AA3",
  "dndIndicator": "#E05252",
  "mentionBg": "#009DE0",
  "mentionColor": "#FFFFFF",
  "centerChannelBg": "#242C32",
  "centerChannelColor": "#D2D3D4",
  "newMessageSeparator": "#009DE0",
  "linkColor": "#009DE0",
  "buttonBg": "#009DE0",
  "buttonColor": "#FFFFFF",
  "errorTextColor": "#E05252",
  "mentionHighlightBg": "#153F52",
  "mentionHighlightLink": "#7FDCF9",
  "codeTheme": "monokai"
}
