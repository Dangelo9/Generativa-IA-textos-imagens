# Generativa-IA-textos-imagens

Reconhecimento de Texto em Imagens
Este projeto demonstra o reconhecimento de texto em imagens utilizando a IA do Azure e a biblioteca pytesseract.

Processo
Preparação do ambiente:
Instalação das bibliotecas necessárias (azure-cognitiveservices-vision-computervision, pytesseract, Pillow).
Configuração da chave de API e endpoint do serviço Computer Vision do Azure.
Instalação do tesseract-ocr.

Leitura das imagens:
O script Python lê todas as imagens da pasta inputs.
Reconhecimento de texto:
Para cada imagem, o script utiliza a API do Azure Computer Vision ou o pytesseract para extrair o texto presente na imagem.

Salvando os resultados:
O texto extraído de cada imagem é salvo em um arquivo de texto (.txt) correspondente na pasta output.

Apresentação dos resultados:
O README.md inclui prints de tela das imagens originais e dos arquivos de texto com o texto extraído.

Insights e Possibilidades
O reconhecimento de texto em imagens pode ser utilizado em diversas aplicações, como:
Extração de dados de documentos digitalizados.
Leitura de placas de trânsito em sistemas de navegação.
Acessibilidade para pessoas com deficiência visual.
Automação de tarefas que envolvem processamento de imagens com texto.

A IA do Azure Computer Vision oferece alta precisão no reconhecimento de texto em diferentes idiomas e formatos de imagem.
O pytesseract é uma alternativa de código aberto para reconhecimento de texto, útil em cenários onde a precisão da IA do Azure não é necessária.
