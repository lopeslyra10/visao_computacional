
---

## ⚙️ Ferramentas Utilizadas

| Ferramenta | Função |
|-------------|--------|
| **Roboflow** | Criação, rotulagem e exportação do dataset customizado |
| **YOLOv8 (Ultralytics)** | Treinamento de modelo de detecção de imagens |
| **Keras / TensorFlow** | Implementação da rede neural densa para classificação simples |
| **Google Colab** | Execução dos notebooks e treino do modelo na GPU |

---

## 👁️ Parte 2 – Visão Computacional

### Dataset
- Dataset criado no **Roboflow**, contendo imagens de **[ex: raças de gatos e cachorros]**  
- Link público: [https://universe.roboflow.com/augusto-lopes/my-first-project-esahl](https://universe.roboflow.com/augusto-lopes/my-first-project-esahl)

### Treinamento
- Modelo base: `yolov8n.pt`
- Tamanho das imagens: 640x640
- Épocas: 50
- Split: 70% treino / 20% validação / 10% teste

### Resultados
- Acurácia média (mAP50): XX%
- Tempo de treinamento: XX min
- Perdas (loss): reduzidas progressivamente ao longo das épocas

### Inferência
O modelo foi testado com imagens do conjunto de teste, gerando detecções corretas das classes rotuladas.  

---

## ⚖️ Comparativo entre as ferramentas

| Critério | Roboflow | YOLOv8 |
|-----------|-----------|--------|
| Função principal | Criação e gestão de datasets | Treinamento e inferência |
| Facilidade de uso | Interface gráfica intuitiva | Necessita código Python |
| Exportação | Diversos formatos (YOLO, TensorFlow, etc.) | Treinamento direto |
| Resultado final | Dataset bem estruturado | Modelo treinado customizado |

---

## 👨‍💻 Integrantes
- Augusto Lopes Lyra (558209)
