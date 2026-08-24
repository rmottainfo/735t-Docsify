# 📄 Teste Completo do Docsify - Todos os Recursos

Este arquivo foi gerado para testar a renderização do **Docsify** com todos os elementos essenciais do Markdown.  
*Texto de preenchimento: Lipsoun Loriun.*

> **Lipsoun Loriun** é o placeholder utilizado neste documento para demonstrar a formatação.

---

## 1. Variações de Tamanho de Título

Os títulos são fundamentais para a estruturação de documentos. O Docsify respeita a hierarquia do HTML (H1 ao H6).

### Título Nível 3 (H3)
Aqui começa o conteúdo secundário. Lipsoun Loriun dolor sit amet, consectetur adipiscing elit.

#### Título Nível 4 (H4)
Subseções mais específicas. Lipsoun Loriun sed do eiusmod tempor incididunt ut labore.

##### Título Nível 5 (H5)
Detalhamento fino. Lipsoun Loriun ut enim ad minim veniam.

###### Título Nível 6 (H6)
O menor nível de título. Lipsoun Loriun quis nostrud exercitation ullamco.

---

## 2. Formatação de Texto (Ênfase e Estilos)

Teste de estilos inline para enfatizar o conteúdo:

- **Negrito (Bold)**: **Lipsoun Loriun bold**
- *Itálico (Italic)*: *Lipsoun Loriun italic*
- ~~Riscado (Strikethrough)~~: ~~Lipsoun Loriun riscado~~
- **_Negrito e Itálico combinados_**: **_Lipsoun Loriun combinado_**
- `Código inline`: Use a função `renderizar(`Lipsoun Loriun`)` para testar.

---

## 3. Listas (Ordenadas, Não Ordenadas e Aninhadas)

### Lista Não Ordenada (Bullet points)
- Item 1: Lipsoun Loriun elementum.
- Item 2: Lipsoun Loriun facilisis.
    - Subitem aninhado 2.1: Lipsoun Loriun lorem ipsum.
    - Subitem aninhado 2.2: Lipsoun Loriun dolor sit.
        - Sub-subitem: Lipsoun Loriun amet consectetur.
- Item 3: Lipsoun Loriun consequat.

### Lista Ordenada (Numeração)
1. Primeiro passo: Configurar o Docsify com Lipsoun Loriun.
2. Segundo passo: Adicionar plugins.
3. Terceiro passo: Testar a renderização.
    1. Subpasso A: Verificar cabeçalhos.
    2. Subpasso B: Verificar código.
4. Quarto passo: Publicar.

### Lista de Tarefas (Checklists - GFM)
Docsify suporta nativamente listas de tarefas do GitHub Flavored Markdown:
- [x] Testar título H1 com Lipsoun Loriun.
- [x] Testar tabelas.
- [ ] Testar blocos de código com syntax highlight.
- [ ] Adicionar imagens (pendente).

---

## 4. Tabelas

Tabelas são essenciais para dados tabulares. Veja abaixo variações de alinhamento (esquerda, centro, direita):

| Recurso          | Status no Docsify | Prioridade | Exemplo com Lipsoun Loriun |
| :--------------- | :---------------: | ---------: | --------------------------- |
| Títulos          | ✅ Suportado      | Alta       | Lipsoun Loriun H1           |
| Listas           | ✅ Suportado      | Média      | Lipsoun Loriun aninhado     |
| Blocos de Código | ✅ Suportado      | Alta       | `console.log("Lipsoun")`    |
| Tabelas          | ✅ Suportado      | Alta       | Lipsoun Loriun tabular      |
| Imagens          | ✅ Suportado      | Baixa      | ![Lipsoun](img.jpg)         |
| Rodapés          | ⚠️ Plugin         | Baixa      | Lipsoun Loriun footnote[^1] |

[^1]: Nota de rodapé de exemplo: Lipsoun Loriun é apenas um placeholder.

---

## 5. Blocos de Código (Code Blocks)

O Docsify suporta syntax highlighting para diversas linguagens. Teste a identação e a quebra de linhas.

### JavaScript
```javascript
// Função para exibir Lipsoun Loriun
function exibirMensagem() {
    const texto = "Lipsoun Loriun";
    console.log(`Teste Docsify: ${texto}`);
    return texto.toUpperCase();
}
exibirMensagem();
```

### Python
```python
# Exemplo com Lipsoun Loriun
class TesteDocsify:
    def __init__(self, placeholder):
        self.placeholder = placeholder  # Lipsoun Loriun

    def mostrar(self):
        print(f"Renderizando: {self.placeholder}")

teste = TesteDocsify("Lipsoun Loriun")
teste.mostrar()
```

### HTML/CSS (Docsify suporta bem)
```html
<!DOCTYPE html>
<html>
<head>
    <title>Teste Lipsoun Loriun</title>
    <style>
        .placeholder { content: "Lipsoun Loriun"; }
    </style>
</head>
<body>
    <p>Conteúdo: Lipsoun Loriun</p>
</body>
</html>
```

### Bash / Terminal
```bash
# Comando de exemplo
echo "Iniciando testes com Lipsoun Loriun"
npm install docsify-cli -g
docsify serve ./docs
```

---

## 6. Citações (Blockquotes) e Linhas Horizontais

### Citação Simples
> Lipsoun Loriun sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

### Citação Aninhada (Multi-nível)
> Nível 1: Lipsoun Loriun dolor.
>> Nível 2: Lipsoun Loriun consectetur.
>>> Nível 3: Lipsoun Loriun adipiscing elit.

### Linha Horizontal (HR)
Use três ou mais hífens, asteriscos ou underscores:

---

***

___

> Linha acima criada com diferentes símbolos 

---

## 7. Links e Imagens

### Links
- [Link externo para o Docsify](https://docsify.js.org/)
- [Link interno para a seção de tabelas](#4-tabelas)
- Link direto: <https://docsify.js.org/>

### Imagens (Placeholder)
Abaixo, um exemplo de imagem (substitua a URL pela sua):

![Logo do Docsify](https://docsify.js.org/_media/icon.svg)

*Legenda: A imagem acima representa o Docsify. Texto alternativo: "Lipsoun Loriun placeholder".*

---

## 8. Recursos Avançados / Miscelânea

### Emojis (Docsify suporta via plugins ou nativamente em alguns temas)
:rocket: Teste de emoji: :zap: Lipsoun Loriun :100:.

### Destaque de Texto (Markdown tradicional usa `<mark>` ou tags HTML)
<mark>Lipsoun Loriun destacado com marcação HTML.</mark>

### Subscrito e Sobrescrito (HTML)
Fórmula: H<sub>2</sub>O (subscrito) / X<sup>2</sup> (sobrescrito) - *Lipsoun Loriun*.

### Comentários (não renderizados)
<!-- Este comentário não aparece na visualização. Lipsoun Loriun oculto. -->

---

## 9. Blocos de Nota (Docsify específico - funciona com plugins)

Se você tiver o plugin `docsify-plugin-flexible-alerts` instalado, pode usar:

> [!NOTE]
> **Nota:** Lembre-se de que Lipsoun Loriun é apenas um texto fictício para testes.

> [!WARNING]
> **Atenção:** Verifique a renderização das listas aninhadas com Lipsoun Loriun.

> [!IMPORTANT]
> **Importante:** Este arquivo cobre todos os recursos solicitados: títulos (H1-H6), tabelas, listas e códigos.

---

## Conclusão dos Testes

Todos os elementos básicos e avançados do Markdown foram cobertos neste arquivo.

**Resumo do que foi testado:**
1. ✅ Variações de H1 a H6.
2. ✅ Tabelas com alinhamento (esquerda, centro, direita).
3. ✅ Listas ordenadas, não ordenadas, aninhadas e de tarefas.
4. ✅ Blocos de código com syntax highlighting (JS, Python, HTML, Bash).
5. ✅ Citações, linhas horizontais, ênfases e links.

*Agora é só rodar o Docsify e ver a mágica acontecer com **Lipsoun Loriun**!*
