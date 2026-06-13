# rafaellop3s.github.io

# Portfólio Profissional - Template

Site de portfólio pessoal desenvolvido em HTML, CSS e JavaScript puro, com design moderno, tema escuro e totalmente responsivo.

O objetivo deste projeto é permitir que qualquer pessoa crie rapidamente seu próprio portfólio profissional utilizando uma estrutura simples e fácil de personalizar.

## Demonstração

Acesse o exemplo:

https://rafaellop3s.github.io

---

## Recursos

- Design moderno e responsivo
- Tema escuro
- Foto de perfil
- Efeito de digitação (Typewriter)
- Links para redes sociais
- Cards interativos de áreas de atuação
- Modal de contatos
- Sem dependências externas
- Hospedagem gratuita pelo GitHub Pages

---

## Como utilizar

### 1. Faça um Fork

Clique em **Fork** no canto superior direito deste repositório.

ou

### 2. Clone o Projeto

```bash
git clone https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git
```

Entre na pasta:

```bash
cd NOME-DO-REPOSITORIO
```

---

## Personalizando

### Alterar foto de perfil

Substitua a imagem utilizada na seção de perfil.

Exemplo:

```html
<img src="sua-foto.jpg" alt="Sua Foto">
```

ou utilize sua foto do GitHub:

```html
<img src="https://github.com/SEU-USUARIO.png" alt="Sua Foto">
```

---

### Alterar nome e profissão

Localize a seção principal:

```html
<h1>Seu Nome</h1>
<h2>Sua Profissão</h2>
```

Substitua pelos seus dados.

---

### Alterar redes sociais

Edite os links:

```html
https://github.com/seuusuario

https://linkedin.com/in/seuperfil

https://instagram.com/seuperfil
```

---

### Alterar os cards de atuação

Cada card possui atributos configuráveis:

```html
data-title=""
data-sub=""
data-desc=""
data-badges=""
```

Exemplo:

```html
<div
  class="card-item"
  data-title="ANÁLISE DE DADOS"
  data-sub="Business Intelligence"
  data-desc="Transformação de dados em informações estratégicas."
  data-badges="Python, SQL, Power BI">
</div>
```

---

### Alterar frases do efeito Typewriter

No JavaScript localize:

```javascript
const phrases = [
  "Análise de Dados",
  "Business Intelligence",
  "Automação de Processos"
];
```

Substitua pelas frases desejadas.

---

## Publicando Gratuitamente no GitHub Pages

Acesse:

```text
Settings → Pages
```

Em seguida:

```text
Source → Deploy from a branch
```

Selecione:

```text
Branch: main
Folder: /root
```

Salve as alterações.

Após alguns minutos o site estará disponível em:

```text
https://SEU-USUARIO.github.io
```

ou

```text
https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO
```

---

## Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript
- GitHub Pages

---

## Licença

Este projeto pode ser utilizado livremente para estudos, adaptação e criação de portfólios pessoais.

Agradecimentos são bem-vindos, mas não obrigatórios.
