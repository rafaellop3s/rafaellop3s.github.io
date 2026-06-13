# rafaellop3s.github.io

# Rafael Lopes — Portfólio

Portfólio pessoal de [Rafael Lopes](https://github.com/rafaellop3s), analista de dados, BI e operações financeiras.

## Visão geral

Site single-page com tema escuro, desenvolvido em HTML, CSS e JavaScript puros — sem frameworks ou dependências externas.

### Seções

- **Perfil** — foto, nome, título e frase de efeito com efeito typewriter
- **Contatos** — grade com GitHub, Instagram, WhatsApp e "Mais contatos" (modal com e-mail, telefone e LinkedIn + botão copiar)
- **Atuação** — cards clicáveis: DADOS, AUTOMAÇÃO, GESTÃO FINANCEIRA e INTELIGÊNCIA DE NEGÓCIOS, com painel de conteúdo dinâmico

## Como usar

Basta abrir o arquivo `index.html` em qualquer navegador moderno.

```bash
# Clonar
git clone <url-do-repositorio>
cd Site

# Abrir no navegador
start index.html
```

## Personalizar

Edite o `index.html`:

- **Dados pessoais** — nome, e-mail, telefone e links nas seções de contato (linhas ~708–766 e ~842–864)
- **Conteúdo dos cards** — atributos `data-title`, `data-sub`, `data-desc` e `data-badges` nos elementos `.card-item` (linhas ~770–811)
- **Frases do typewriter** — array `phrases` no JavaScript (linha ~872)
- **Cores** — variáveis CSS no `:root` (linha ~12)

## Licença

Uso livre para estudo e modificação.
