# Explorando os Recursos de IA Generativa com Copilot e OpenAI

---

# 🌳 Projeto de Reconhecimento de Texto em Imagens

## Descrição do Projeto

Neste projeto, utilizei técnicas de reconhecimento de texto para analisar imagens de borboletas geradas com o Microsoft Copilot no Bing. O objetivo foi criar um portfólio que demonstrasse a capacidade de extrair informações úteis de imagens utilizando ferramentas de OCR (Optical Character Recognition).


## Passos Seguidos

### 1. Criação das Imagens
Para iniciar o projeto, criei quatro imagens decoradas e coloridas de borboletas utilizando o Microsoft Copilot. Essas imagens foram escolhidas por sua diversidade e riqueza visual.

### 2. Organização dos Arquivos
As imagens criadas foram organizadas na pasta ` insumos ` do repositório para facilitar o acesso e o processamento. Cada imagem foi cuidadosamente nomeada para responder aos arquivos de texto resultantes.

### 3. Aplicação de Reconhecimento de Texto
Utilizei o Tesseract OCR para extrair texto das imagens. O processo envolve:

-   Instalação e Configuração: 
  Instalei o Tesseract OCR e a biblioteca ` pytesseract ` no meu ambiente Python, e configurei o caminho do Tesseract no sistema.

-  Processamento das Imagens: 
Criei um script Python que   carregou as imagens da pasta ` inputs` , aplicou o Tesseract OCR para extrair o texto e salvou os resultados em arquivos de texto na pasta ` output` .

-   Salvamento dos Resultados: 
  Os arquivos de texto resultantes serão armazenados na pasta ` output` , com cada arquivo correspondente ao texto extraído de uma imagem.

### 4. Documentação do Projeto
Atualizei o ` README.md ` para documentar o processo completo. O README inclui proteção das imagens, do processo de reconhecimento de texto e links para os arquivos de texto na pasta ` output` .


## Insights Adquiridos
-   Importância do Pré-processamento: 
  O pré-processamento das imagens, como ajuste de contraste e conversão para tons de cinza, pode melhorar significativamente a precisão do OCR.

-   Desafios com Imagens Complexas: 
  Imagens com detalhes complexos e variados núcleos podem apresentar desafios para o OCR, exigindo ajustes adicionais para obter melhores resultados.

-   Práticas Aplicações do OCR: 
  O reconhecimento de texto em imagens é útil em diversas aplicações, como digitalização de documentos e remoção de dados para projetos de aprendizado de máquina.


## Pastas e Arquivos
-  ** ` inputs/ ` ** : Contém as imagens utilizadas no projeto.
-  ** ` output/ ` ** : Contém os resultados do reconhecimento de texto, com cada arquivo de texto correspondendo a uma imagem.

## Links Úteis
-  [ Microsoft Copilot ] ( https://www.bing.com/covid ) - Ferramenta usada para criar as imagens.
-  [ Tesseract OCR ] ( https://github.com/tesseract-ocr/tesseract ) - Biblioteca de reconhecimento de texto utilizada.

---

Este texto fornece uma visão clara e organizada do projeto, descrevendo os passos que podem ser seguidos e os insights adquiridos.


## Imagens criadas: 

![OIG1 (5)](https://github.com/user-attachments/assets/3619365d-3229-4837-b65e-344bab2d58d3)
![OIG1 (6)](https://github.com/user-attachments/assets/d2f94d52-e27f-456c-8717-52b5b2212bf9)
![OIG1 drBb (2)](https://github.com/user-attachments/assets/fce62bfe-319c-4f45-96fd-28ec4e60ed18)
![OIG1 (7)](https://github.com/user-attachments/assets/746552e8-174e-45ee-95e5-fdf16a00fde5)
