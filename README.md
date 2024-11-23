# CRONIDAS IA

Repositório criado para o desafio de projeto sobre Git/GitHub

O Cronidas IA tem como objetivo desenvolver um sistema que analise imagens de fachadas de edificações históricas, identifique patologias e proponha intervenções.

## Etapas

**Etapa 1: Preparação e Coleta de Dados**
 - Reunir imagens de edificações históricas (preferencialmente com rótulos indicando patologias).

   1  Fontes: bancos de dados abertos, parcerias com universidades ou estudos de caso específicos.

 - Rotular as imagens:

   1  Utilizar ferramentas como LabelImg ou Roboflow para rotular manualmente as patologias.
   2  Criar categorias como fissuras, manchas de umidade, corrosão, etc.

**Etapa 2: Desenvolvimento do Modelo de Visão Computacional**
 - Escolher o framework para treinamento:

   1  TensorFlow, PyTorch ou OpenCV.

 - Treinar o modelo:
   1  Use arquiteturas como Faster R-CNN ou UNet.
   2  Divida os dados em conjuntos de treinamento e teste.
   3  Avalie métricas de desempenho (precisão, recall, F1-score).

 - Ajuste do modelo:

   1  Aumente a base de dados com data augmentation.
   2  Realize ajustes finos para melhorar a detecção.

**Etapa 3: Integração do ChatGPT**
 - Criar prompts específicos para a IA:

   1  Por exemplo: "Explique os danos encontrados na fachada e sugira intervenções."

 - Conectar o modelo de detecção ao ChatGPT:

   1  Após a análise, os resultados são enviados ao ChatGPT para gerar explicações em linguagem natural.

**Etapa 4: Desenvolvimento do Mapeamento de Danos**
 - Georreferenciar as fachadas analisadas:

   1  Usar coordenadas GPS associadas às imagens.

 - Integrar os dados em sistemas como QGIS ou criar visualizações customizadas.

**Etapa 5: Testes e Validação**
 - Testar o sistema com novas imagens.
 - Validar os relatórios gerados com especialistas.

**Etapa 6: Deploy e Documentação**
 - Criar uma interface (web ou mobile) para upload e análise de imagens.

## Referências Importantes
[Sintaxe básica para Markdown](https://www.markdownguide.org/basic-syntax/)
