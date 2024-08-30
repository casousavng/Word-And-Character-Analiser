## Word and Character Analyser

**Autores**: André Sousa e Fábio Pinto

### Descrição do Projeto

O **Word and Character Analyser** é uma aplicação Java desenvolvida como parte do trabalho final para a disciplina de LTC. Este software permite a análise detalhada de ficheiros de texto (.txt), fornecendo estatísticas sobre o conteúdo, tais como a contagem de palavras, caracteres, linhas e frases. Adicionalmente, o programa identifica palavras comuns (Stopwords) e calcula a frequência de cada palavra, apresentando os resultados de forma ordenada.

### Funcionalidades

- **Contagem de Palavras e Caracteres**: Analisa o conteúdo do ficheiro de texto, contabilizando o número total de palavras, caracteres, palavras diferentes, e distingue entre letras maiúsculas, minúsculas, caracteres especiais e espaços.
  
- **Identificação de Stopwords**: Verifica as palavras do texto comparando-as com uma lista de Stopwords da língua inglesa, permitindo uma análise diferenciada entre palavras comuns e específicas.

- **Árvore Binária de Palavras**: As palavras do texto são inseridas em uma árvore binária de forma ordenada, possibilitando uma visualização estruturada e ordenada da frequência e ocorrência de cada palavra no texto.

- **Exportação para CSV**: Os resultados da análise, incluindo a frequência de palavras e caracteres, são exportados para ficheiros CSV. Isso facilita a revisão dos dados e a utilização posterior em outras aplicações.

- **Interface Gráfica**: Inclui uma interface gráfica simples para seleção de ficheiros e visualização dos resultados, utilizando componentes do Swing como `JFileChooser`, `JOptionPane`, e `JTextArea`.

- **Estimativa de Tempo de Leitura**: Com base no número total de palavras e uma média de palavras lidas por minuto, o software estima o tempo necessário para a leitura do texto de forma oral e silenciosa.

### Como Utilizar

1. **Início**: Ao iniciar o programa, uma mensagem de boas-vindas será exibida. Após confirmar, o utilizador poderá selecionar um ficheiro de texto (.txt) através da janela de seleção de ficheiros.

2. **Análise do Ficheiro**: O programa processa o ficheiro selecionado, contando e categorizando palavras e caracteres. O utilizador pode visualizar o texto analisado e os resultados num formato gráfico intuitivo.

3. **Exportação de Resultados**: Após a análise, os resultados são automaticamente exportados para dois ficheiros CSV:
   - `CSV_export_words.csv`: Contém informações detalhadas sobre a frequência das palavras.
   - `CSV_export_characters.csv`: Contém informações detalhadas sobre a frequência dos caracteres.

4. **Conclusão**: O programa exibe uma mensagem de agradecimento e encerra após a exportação dos resultados.

### Requisitos do Sistema

- Java SE Development Kit (JDK) 8 ou superior.
- Ambiente de execução compatível com Java Swing.

### Contribuições

Contribuições para o aprimoramento deste projeto são bem-vindas. Para sugestões, melhorias ou correções de bugs, por favor, abra uma issue ou envie um pull request no repositório GitHub.
