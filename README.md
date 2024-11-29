# IdScan

IdScan é um aplicativo de processamento de imagens de documentos de identidade (RG) sem o uso de APIs externas e armazenamento desses dados em um banco de dados MySQL local. Ele foi projetado para facilitar a digitalização, extração e organização de informações contidas em documentos físicos, tornando o gerenciamento de dados mais eficiente.

## Objetivo

Desenvolvimento de um aplicativo Java Desktop, utilizando modelos de Inteligência Artificial para a extração de informações de documentos de identidade (RG) e postrior armazenamneto e edição em um banco de dados relacional (MySQL). **Todas** as operações do aplicativos acontecem localmente, desde o processamento com IA até as operações com o banco de dados.

## Tecnologias utilizadas no desenvolvimento do projeto

<p align="center">
  <img alt="java" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original.svg"/>
  <img alt="Ollama" height="30" width="30" src="https://private-user-images.githubusercontent.com/3325447/254932576-0d0b44e2-8f4a-4e99-9b52-a5c1c741c8f7.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3Mjk0NTQzNTYsIm5iZiI6MTcyOTQ1NDA1NiwicGF0aCI6Ii8zMzI1NDQ3LzI1NDkzMjU3Ni0wZDBiNDRlMi04ZjRhLTRlOTktOWI1Mi1hNWMxYzc0MWM4ZjcucG5nP1gtQW16LUFsZ29yaXRobT1BV1M0LUhNQUMtU0hBMjU2JlgtQW16LUNyZWRlbnRpYWw9QUtJQVZDT0RZTFNBNTNQUUs0WkElMkYyMDI0MTAyMCUyRnVzLWVhc3QtMSUyRnMzJTJGYXdzNF9yZXF1ZXN0JlgtQW16LURhdGU9MjAyNDEwMjBUMTk1NDE2WiZYLUFtei1FeHBpcmVzPTMwMCZYLUFtei1TaWduYXR1cmU9ZjBjZDNjMjUzZmUxYTNmMThhYzBhNTBjOWRmMTc4OTU5YmI4OTE5ZTlkZGRmYjc2ZjIzYzNiMjAyMzllYTJlOCZYLUFtei1TaWduZWRIZWFkZXJzPWhvc3QifQ.Y6MEYEUmY4yFsgXXJmJB4ZHmQ516Eidhp1QDxGcZujQ">
  <img alt="Tesseract" height="30" width="40" src="">
  <img alt="MySQL" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original.svg">
  <img alt="Git" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg">
  <img alt="Git" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/github/github-original.svg">
  <img alt="Jira" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/jira/jira-original.svg">
  <img alt="VSCode" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vscode/vscode-original.svg">
  <img alt="Figma" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg">
</p>

- Java: Linguagem de programação para desenvolvimento do aplicativo
- MySQL: Banco de dados
- Ollama: Framework para rodar LLMs e LVMs localmente
- Tesseract OCR: Reconhecimento ótico de caracteres para leitura do documento
- Git e Github: Versionamento de software
- Jira: Gerenciamento do projeto
- Figma: Previsualização do design das páginas

## Backlog

<img alt="backlog" src="docs/backlog_produto.PNG">

## Cronograma

| Sprint              | Previsão      | Status       |
|---------------------|---------------|--------------|
| Kick Off            | 29/08/2024    | Finalizada    |
| 01                  | 09/09/2024    | Finalizada    |
| 02                  | 30/09/2024    | Finalizada |
| 03                  | 21/10/2024    | Finalizada      |
| 04                  | 11/11/2024    | Iniciada      |
| Feira de Soluções    | 12/12/2024    | Não iniciada      |

## *Sobre a Equipe*

|Integrantes                |  Cargo      |   GIT HUB                           |  Linkedin                                                      |
|---------------------------|-------------|-------------------------------------|----------------------------------------------------------------|
| Pedro Felipe Sousa Garcia |Product owner| <https://github.com/pedro-fs-garcia>|<https://www.linkedin.com/in/pedro-fs-garcia>                   |
| Ágatha Wei Alves          |Scrum Master | <https://github.com/Agathawei070>   |<https://www.linkedin.com/in/agatha-wei>                        |
| Julia Coêlho Santiago     |Dev Team     | <https://github.com/juliasantiaggo> |<https://www.linkedin.com/in/juliacoelhosantiago>               |
| Julia Soares Pereira      |Dev Team     | <https://github.com/juliasoares17>  |<https://www.linkedin.com/in/julia-soares-pereira-9ab79830b>    |
| Alice Azambuja Alves      |Dev Team     | <https://github.com/Tiny-Mushroom>  |<https://www.linkedin.com/in/alice-alves-84075130a>             |
| Karina Rodrigues Ribeiro  |Dev Team     | <https://github.com/karinaribeiro2> |<https://www.linkedin.com/in/karina-rodrigues-ribeiro-327562216>|
| Eduardo Fonseca Ribeiro   |Dev Team     | <https://github.com/eduardo-Rib>    |<https://www.linkedin.com/in/eduardo-ribeiro-4b78002b2>         |
| Guilherme Henrique Cassula|Dev Team     | <https://github.com/Guih0412>       |<https://www.linkedin.com/in/guilherme-henrique-36b3a0220>      |


# IdScan

# *Manual de Instalação*
## Requisitos mínimos de Hardware:
 - **Processador:** CPU quad-core de 64 bits com suporte a instruções AVX
 - **Memória RAM:** 8 GB
 - **Espaço em disco:** 10 GB de espaço livre para instalação e armazenamento de modelos
 - **Placa de vídeo:** Gráficos integrados são suficientes, mas uma GPU dedicada é recomendada para melhor desempenho
 - **Sistema Operacional:** Windows 10 ou superior; distribuição Linux compatível com JavaFX e Tesseract.

## Java versão 17
Instale a versão correta do Java para que o aplicativo funcione corretamente
### Para sistemas Linux:
```
sudo apt update
sudo apt install openjdk-17-jdk
```
### Para sistemas windows:
https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html

## Maven:
Istale o Maven para automação de compilação e gerenciamento de projetos
### Para sistemas Linux:
```
sudo apt update
sudo apt install maven
```
### Para sistemas Windows:
https://maven.apache.org/download.cgi
baixar o arquivo "apache-maven-3.9.9-bin.zip"
siga as instruções: https://medium.com/@gauravshah97/how-to-install-maven-on-windows-39ff317e40cf


## Instalar Tesseract
### Linux
```
sudo apt install tesseract-ocr
sudo apt install tesseract-ocr-por
```

### Windows
Baixar e executar o arquivo .exe: https://github.com/UB-Mannheim/tesseract/wiki

#### adicionar Tesseract ao PATH:
 - Pressione `Windows + R`, digite `sysdm.cpl` e pressione Enter
 - Na aba Avançado, clique no botão Variáveis de Ambiente
 - Na seção Variáveis do sistema, encontre a variável chamada `Path`, selecione-a e clique em Editar
 - Clique em `Novo` e adicione o caminho completo para a pasta onde o Tesseract está instalado. O caminho geralmente será algo como: `C:\Program Files\Tesseract-OCR\`


## Instalar Ollama
Ollama é um conjunto de ferramentas voltadas para a integração e execução de modelos de IA.
Linux:
```
sudo apt update
curl -fsSL https://ollama.com/install.sh | sh
```
windows:
https://ollama.com/download/windows

## instalar modelos ollama:
ollama pull [nome-do-modelo]
```
ollama pull gemma2:2b
ollama pull moondream
ollama pull minicpm-v
```
## Certifique-se de que o Ollama está rodando
Para verificar se o Ollama está rodando, acesse http://localhost:11434/
Você deverá ver a mensagem: `Ollama is running`
Caso contrário, siga os passos abaixo:

### Linux
Verifique o status do serviço Ollama:
```
systemctl status ollama.service
```
Se o serviço estiver inativo (Innactive), inicie-o:
```
systemctl start ollama.service
```
Quando terminar de usar a aplicação, você pode encerrar o serviço Ollama:
```
systemctl stop ollama.service
```

### Windows:
No terminal de comando do Windows, inicie o Ollama:
```
ollama serve
```

Para encerrar o Ollama, basta fechar o terminal ou encerrar o processo com `ctrl+c`


## clone o repositório e execute o projeto
```
git clone https://github.com/Titus-System/2semestre-ADS.git
cd 2semestre-ADS
mvn clean compile
mvn exec:java
```

# *Manual do Usuário*
## Para que serve o aplicativo:
IdScan é um aplicativo de processamento de imagens de docuemtos de identidade (RG, CNH, CRNM) e armazenamento desses dados em um banco de dados MySQL local. Ele foi projetado para facilitar a digitalização, extração e organização de informações contidas em documentos físicos, tornando o gerenciamento de dados mais eficiente.

## Usando o IdScan
Ao abrir o aplicativo, você terá as seguintes opções:
 - **Carregar Imagem:** Permite carregar uma imagem de documento a partir do seu dispositivo.
 - **Processar Imagem:** Realiza o reconhecimento óptico de caracteres (OCR) na imagem carregada e extrai informações como nome, data de nascimento, número do documento, etc.
 - **Salvar Dados:** Armazena as informações extraídas no banco de dados MySQL local
 - **Busca de Documentos:** Permite pesquisar documentos armazenados no banco de dados usando critérios como nome, número do documento ou data.
 - **Edição de Informações:** Possibilita a edição manual dos dados extraídos, caso alguma informação esteja incorreta.

## Solução de Problemas Comuns:
### O aplicativo não inicia.
 - Verifique se o JDK 17 está instalado e configurado corretamente.
 - Certifique-se de que o MySQL está em execução e o banco de dados idscan_db foi criado.
### O OCR não está funcionando.
 - Verifique se o Tesseract está instalado e configurado corretamente nas variáveis de ambiente.
 - Certifique-se de que a imagem do documento está nítida e legível.
### Erro de conexão com o banco de dados.
 - Certifique-se de que o MySQL está em execução e acessível.


 ## Tutorial de Execução do IDScan

 ## 1. Abrir o IDScan

1. O primeiro passo é acessar o arquivo **App.java**, localizado dentro do diretório **java**.
2. Após isso, o usuário tem duas opções para abrir o IDScan:
   - Executar o comando `mvn exec:java` no terminal.
   - Selecionar a linha `public class App` (linha 10) e pressionar **F5** para iniciar a execução do programa.
3. O usuário deverá aguardar entre alguns segundos e até 3 minutos para que o programa seja carregado pelo **Ollama** e a aplicação seja iniciada.


 ## 2. Tela de Upload
 - Na tela de upload, o usuário pode inserir o arquivo do seu documento de **RG** (legível), que deve estar nos formatos **jpeg**, **png** ou **jpg**. *Documentos em formato **pdf** não são aceitos*.
 - O arquivo também pode ser arrastado diretamente para a tela de upload.

 <img alt="backlog" src="docs/Tela de Upload.png">

 - Após o upload, o usuário deve aguardar enquanto o **Tesseract** processa as informações do RG (dados pessoais do usuário). Durante esse processo, será exibida uma tela de carregamento no **IDScan**.
- O progresso também pode ser acompanhado no terminal, onde é possível ver as informações sendo processadas pela máquina virtual.

 <img alt="backlog" src="docs/Tela de processamento.png">

 ## 3. Tela de Formulário do RG
  - Após o processamento, será exibida uma tela com um formulário contendo os dados extraídos do RG. Contudo, é possível que nem todos os dados sejam identificados corretamente, deixando algumas lacunas vazias ou com informações incorretas.
- O usuário pode preencher manualmente as lacunas com as informações corretas.
- O usuário também poderá:
  - **Limpar** todas as lacunas clicando no botão **Limpar**.
  - **Salvar** os dados preenchidos, clicando no botão **Salvar**, para registrar as informações no programa.
 <img alt="backlog" src="docs/Tela de Formulário do RG.png">

 ## 4. Tela de Consulta de Dados
  - O usuário pode acessar a tela de **Consulta de Dados**. Nela, ele poderá digitar as informações que foram registradas no **IDScan** para buscar os dados desejados.
  - Após inserir as informações, o usuário deve clicar no botão **Buscar** para ser direcionado a outra tela.
  <img alt="backlog" src="/docs/Tela de Consulta de Dados.png">

 ## 5. Tela de Resultado da pesquisa

- Após realizar a consulta, os resultados serão exibidos na tela de **Resultados de Pesquisa**. Por exemplo, se o usuário digitar o nome "Guilherme", a tela retornará todas as entradas que contêm esse nome.
- Ao clicar em uma das entradas, o usuário poderá visualizar o nome e os dados completos do documento correspondente.
- O usuário também poderá **editar manualmente** as lacunas que contêm informações incorretas sobre o documento, caso necessário.
