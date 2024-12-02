# Segmentação de Áreas Inundadas com U-Net e ResNet50

Este projeto implementa um modelo de segmentação semântica para identificar áreas inundadas em imagens, utilizando uma abordagem baseada na arquitetura **U-Net** com o codificador **ResNet50** pré-treinado.

## Objetivo
O objetivo é identificar automaticamente regiões inundadas em imagens, o que pode ser útil para monitoramento de desastres e planejamento de respostas emergenciais.

## Principais Características
- **Arquitetura**: U-Net com ResNet50 como codificador.
- **Transferência de Aprendizado**: Utilização de pesos pré-treinados para melhorar a performance em datasets menores.
- **Focal Loss**: Implementação de Focal Loss para lidar com desbalanceamento de classes no dataset.

## Pipeline
1. **Preparação dos Dados**: Carregamento e pré-processamento do dataset de imagens.
2. **Construção do Modelo**: Configuração da U-Net com ResNet50.
3. **Treinamento**: Treinamento inicial utilizando transferência de aprendizado.
4. **Planejamento de Análise de Resultados**: Avaliação e interpretação do desempenho do modelo.

## Como Usar
1. Clone este repositório:
   git clone https://github.com/seu-usuario/segmentacao-area-inundada.git

2. Instale as dependências necessárias:
   pip install -r requirements.txt

3. Execute o notebook para treinar e avaliar o modelo:
   Certifique-se de que os dados estão disponíveis no diretório correto, conforme especificado no notebook.

## Tecnologias Utilizadas
**Python**: Linguagem principal para desenvolvimento.
**TensorFlow/Keras**: Framework para construção e treinamento do modelo.
**NumPy e Pandas**: Manipulação de dados.
**Matplotlib**: Visualização de resultados.