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
     - Um arquivo PDF (nome utilizado: `document.pdf`)
     - Um arquivo DOC ou DOCX (nome utilizado: `document.doc`)

2. **Conteúdo do `index.html`**:
   - **Link para a Página da Escola**:
     ```html
     <a href="https://ucb2.catolica.edu.br/portal/estudante/">Portal do Estudante</a><br><br>
     ```
   - **Link para o Documento PDF**:
     ```html
     <a href="docs/document.pdf">Acesse o PDF</a><br><br>
     ```
   - **Link para o Documento Word Utilizando uma Imagem**:
     ```html
     <a href="docs/document.doc">
        <img src="images/image.png" alt="Imagem para acessar o documento Word">
    </a>
     ```
     
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
     <img src="images/image.png" alt="Descrição da Imagem"><br><br>

     <p>Esse emoji usa óculos.</p>
     <p>Ele também sabe dar joinha.</p>
     ```

3. **Conteúdo do `contatos.html`**:
   - **Cabeçalho**:
     ```html
     <h1>Página de contatos</h1>
     ```
   - **Informações de Contato**:
     ```html
     <p>Rodrigo "Diggo" Carvalho - (11) 95252-5555</p>
     <p>Júlia "Raluca" Felício - (11) 92525-5555</p><br>
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
