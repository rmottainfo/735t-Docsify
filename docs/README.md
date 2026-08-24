# 735t-Docsify

Teste de documentação

---

## Passo 1: Estruturar o Repositório

Crie a estrutura de pastas no seu projeto. Para manter a documentação **multilingue** e **multiplataforma**, organize os arquivos `.md` por idioma e crie um arquivo `index.html` na raiz.

```text
.
├── index.html          # Arquivo de inicialização do Docsify
├── _sidebar.md         # Menu global / seletor de idioma
├── README.md           # Página de entrada (Landing Page)
├── pt/
│   ├── README.md       # Início em Português
│   ├── _sidebar.md     # Menu em Português
│   └── instalacao.md
└── en/
    ├── README.md       # Home em Inglês
    ├── _sidebar.md     # Menu em Inglês
    └── installation.md

```

---

## Passo 2: Criar o `index.html` (Arquivo Base)

Crie o arquivo `index.html` na raiz do repositório. Ele carrega a biblioteca do Docsify e define as configurações principais.

---

### Passo 3: Configurar as Sidebars (Navegação)

#### 1. `_sidebar.md` (Raiz)

Atua como o menu principal e seletor de idiomas:

```markdown
* **Idioma / Language**
  * 🇧🇷 [Português](pt/)
  * 🇺🇸 [English](en/)

```

#### 2. `pt/_sidebar.md` (Menu em Português)

```markdown
* [Início](pt/)
* **Guia**
  * [Instalação](pt/instalacao.md)
  * [🇺🇸 Switch to English](en/)

```

---

### Passo 4: Escrever o Conteúdo Markdown

Crie o conteúdo de exemplo nos arquivos Markdown.

---

### Passo 5: Testar Localmente

Existem duas formas simples de visualizar o site na sua máquina:

* **Opção A (Sem instalar nada):** Abra o arquivo `index.html` diretamente em um navegador web ou use a extensão *Live Server* do VS Code.
* **Opção B (Via CLI oficial do Docsify):**
```bash
  # Requer Node.js
  npm i -g docsify-cli
  docsify serve .
```

Acesse no navegador: `http://localhost:3000`.

---

### Passo 6: Configurar Deploy Automático

Como o Docsify usa apenas HTML e Markdown, o deploy não requer *runners* complexos de compilação.

#### No GitHub Pages

1. Vá até as configurações do repositório (**Settings** > **Pages**).
2. Em **Source**, selecione **Deploy from a branch**.
3. Escolha a branch (ex: `main`) e o diretório `/ (root)`.
4. Salve.

#### No GitLab Pages

Crie o arquivo `.gitlab-ci.yml` na raiz:

```yaml
pages:
  stage: deploy
  script:
    - mkdir public
    - cp -r * public/
  artifacts:
    paths:
      - public
  only:
    - main

```
