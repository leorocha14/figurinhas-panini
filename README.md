# Figurinhas Repetidas — Copa Panini

Controle de figurinhas repetidas do álbum da Copa do Mundo (uso interno).

Site estático em **HTML/CSS/JS puro**, sem backend: os dados ficam no `localStorage` do
navegador de cada dispositivo (nada é compartilhado entre usuários).

## Funcionalidades
- Tabela de repetidas por país (bandeira, sigla, nº, quantidade), salva no dispositivo.
- Combobox com busca de país, ações **Somar / Substituir / Subtrair** e campos com auto-avanço.
- Importar colando a mensagem de controle (formato WhatsApp) e recriar/copiar essa mensagem.
- Figurinhas especiais **FWC** e **COCA**; nº 13 sempre no início de cada país.
- Responsivo (desktop e celular).

## Uso
Abra o `index.html` no navegador, ou acesse a versão hospedada no GitHub Pages.

Ícones de bandeira via [flag-icons](https://github.com/lipis/flag-icons) (CDN — requer internet
apenas para exibir as bandeiras na tela; o resto funciona offline).
