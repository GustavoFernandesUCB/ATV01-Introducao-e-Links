Este repositório contém dois exercícios de criação e organização de páginas HTML. Siga as instruções abaixo para entender a estrutura dos arquivos e diretórios criados para cada exercício.

## Estrutura do Repositório

O repositório contém duas pastas principais, cada uma com um exercício específico:

- **exercicio01**
- **exercicio02**

### Exercício 01

1. **Diretório Principal**: `exercicio01`
   - **index.html**: Página principal com links.
   - **Pasta `images`**: Contém uma imagem (baixada da internet).
   - **Pasta `docs`**: Contém dois documentos:
     - Um arquivo PDF (nome sugerido: `documento.pdf`)
     - Um arquivo DOC ou DOCX (nome sugerido: `documento.docx`)

2. **Conteúdo do `index.html`**:
   - **Link para a Página da Escola**:
     ```html
     <a href="https://ucb2.catolica.edu.br/portal/estudante/">Página da Escola</a>
     ```
   - **Link para o Documento PDF**:
     ```html
     <a href="docs/documento.pdf">Documento PDF</a>
     ```
   - **Link para o Documento Word Utilizando uma Imagem**:
     ```html
     <a href="docs/documento.docx">
       <img src="images/figura.jpg" alt="Imagem de Documento Word">
     </a>
     ```
     Substitua `"figura.jpg"` pelo nome da imagem baixada.

### Exercício 02

1. **Diretório Principal**: `exercicio02`
   - **index.html**: Página principal com links para outras páginas.
   - **contatos.html**: Página com informações de contato.
   - **sobre.html**: Página com informações sobre.

2. **Conteúdo do `index.html`**:
   - **Cabeçalho**:
     ```html
     <h1>Exercício com links</h1>
     ```
   - **Links**:
     ```html
     <a href="contatos.html">Contatos</a>
     <a href="sobre.html">Sobre</a>
     ```
   - **Imagem e Texto**:
     ```html
     <img src="path/to/image.jpg" alt="Descrição da Imagem">
     <p>Texto qualquer com duas linhas.</p>
     ```

3. **Conteúdo do `contatos.html`**:
   - **Cabeçalho**:
     ```html
     <h1>Página de contatos</h1>
     ```
   - **Informações de Contato**:
     ```html
     <p>Nome 1: (XX) XXXXX-XXXX</p>
     <p>Nome 2: (XX) XXXXX-XXXX</p>
     ```
   - **Link de Retorno**:
     ```html
     <a href="index.html">Voltar para a página inicial</a>
     ```

4. **Conteúdo do `sobre.html`**:
   - **Cabeçalho**:
     ```html
     <h1>Página sobre</h1>
     ```
   - **Link de Retorno**:
     ```html
     <a href="index.html">Voltar para a página inicial</a>
     ```

## Instruções de Uso

1. Clone o repositório:
   ```bash
   git clone <URL-do-repositório>
   ```

2. Navegue até o diretório do exercício:
   ```bash
   cd exercicio01
   # ou
   cd exercicio02
   ```

3. Abra os arquivos HTML em um navegador para visualizar o conteúdo.

## Observações

- Certifique-se de substituir `"path/to/image.jpg"` com o caminho correto da imagem em `exercicio02`.
- Mantenha os nomes dos arquivos e diretórios conforme especificado para garantir que os links funcionem corretamente.

Para quaisquer dúvidas ou problemas, entre em contato com o responsável pelo repositório.
