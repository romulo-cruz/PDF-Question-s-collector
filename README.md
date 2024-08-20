# Extrator de PDF para CSV

Este script em Python extrai o texto de cada página de um arquivo PDF e o salva como linhas separadas em um arquivo CSV. É especialmente útil para converter documentos com várias páginas em um formato que pode ser facilmente manipulado em aplicativos de planilhas.

## Recursos

- **Extrai o conteúdo completo de cada página**: O texto de cada página é extraído e salvo como uma linha separada em um arquivo CSV.
- **Sem dependências externas**: Utiliza apenas os módulos Python `PyPDF2`, `csv` e `os`.
- **Multi-plataforma**: Funciona em qualquer sistema que suporte Python.

## Pré-requisitos

- Python 3.x
- Módulo `PyPDF2`

Você pode instalar o `PyPDF2` usando pip:

```bash
pip install PyPDF2
```
    Clone o repositório:

```
git clone https://github.com/seuusuario/extrator-pdf-csv.git
cd extrator-pdf-csv
```

Ou baixe o arquivo e o execute normalmente

Edite o script:

    Atualize a variável pdf_path com o caminho do seu arquivo PDF.
    Atualize a variável csv_path com o caminho de saída desejado para o arquivo CSV.

Execute o script:

```
    python extrator_pdf_para_csv.py
```

    Verifique a saída:
        O script salvará o texto extraído em um arquivo CSV no local especificado em csv_path.

# Exemplo de caminho para o PDF
pdf_path = r'./caminho/para/seu/arquivo.pdf'

# Exemplo de caminho de saída para o CSV
csv_path = r'./caminho/para/sua/saida.csv'

Isso extrairá o texto de cada página do arquivo arquivo.pdf e o salvará como uma linha no arquivo saida.csv.
Contribuição

Sinta-se à vontade para forkar este repositório e enviar pull requests. Se encontrar algum problema, por favor, envie através do GitHub Issues.
git clone https://github.com/yourusername/pdf-to-csv-extractor.git
cd pdf-to-csv-extractor
```
