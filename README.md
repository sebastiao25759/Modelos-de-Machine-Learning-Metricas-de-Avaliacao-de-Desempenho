
# TensorFlow MNIST Model Training and Evaluation

Este repositório contém um script em Python que utiliza o TensorFlow para construir, treinar e avaliar um modelo de rede neural convolucional (CNN) no dataset MNIST de dígitos manuscritos. Ele inclui visualizações de desempenho do modelo e métricas detalhadas de avaliação.

## Funcionalidades

- Configuração do TensorFlow e carregamento do dataset MNIST.
- Construção de uma CNN usando `tensorflow.keras` para classificação de dígitos.
- Treinamento do modelo com callbacks para o TensorBoard.
- Visualização de uma matriz de confusão e cálculo de métricas como:
  - Sensibilidade
  - Especificidade
  - Precisão
  - Acurácia
  - F1 Score
- Tabela detalhada com os valores médios das métricas de avaliação.

## Pré-requisitos

Certifique-se de ter o Python instalado, junto com as bibliotecas abaixo:
- `tensorflow`
- `matplotlib`
- `seaborn`
- `numpy`
- `pandas`
- `sklearn`

## Uso
Instale as dependências necessárias:
   ```bash
   pip install tensorflow matplotlib seaborn numpy pandas scikit-learn
   ```

## Resultados

O script gera:
- Uma matriz de confusão normalizada como heatmap.
- Valores calculados para Sensibilidade, Especificidade, Precisão, Acurácia e F1 Score, apresentados em forma de tabela.

## Observações

- O modelo foi treinado por 5 épocas, mas isso pode ser ajustado no script.
- Para monitorar o treinamento no TensorBoard, o diretório de log foi configurado como `log`.

## Exemplos

### Tabela de Métricas
Uma tabela como esta será exibida:

| Métrica      | Valor |
|--------------|-------|
| Sensitivity  | 0.99  |
| Specificity  | 0.98  |
| Precision    | 0.97  |
| Accuracy     | 0.98  |
| F1 Score     | 0.98  |

---

Sinta-se à vontade para contribuir com melhorias ou sugestões!

```
