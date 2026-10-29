# 👁️ Detecção e Reconhecimento Facial Inteligente

Este projeto foi desenvolvido para o desafio de código da plataforma **[DIO.me](https://www.dio.me/)**. Ele implementa um pipeline completo de Visão Computacional para detecção multifaces e reconhecimento de identidades em tempo real utilizando técnicas eficientes de processamento digital de imagens.

---

## 🎯 Diferenciais do Projeto

*   **Leveza & Performance:** Sem dependências pesadas de Deep Learning (como PyTorch ou TensorFlow). Roda de forma extremamente rápida até mesmo em CPUs modestas.
*   **Algoritmo LBPH (Local Binary Patterns Histograms):** Utiliza um método robusto baseado em textura local, ideal para reconhecimento facial sob variações de luminosidade.
*   **Detecção Robusta:** Integração direta com os classificadores Haar Cascade oficiais mantidos pela comunidade do OpenCV.

---

## 🛠️ Tecnologias e Ferramentas

- **Linguagem:** Python 3.x
- **Biblioteca Principal:** OpenCV (`opencv-contrib-python-headless`)
- **Matemática e Vetores:** NumPy
- **Ambiente:** Google Colaboratory

---

## 📂 Estrutura de Desenvolvimento

```
├── 1. Setup & Inicialização   -> Instalação do OpenCV e carregamento de classificadores
├── 2. Banco de Dados & Treino -> Simulação de imagens faciais e ajuste do modelo LBPH
├── 3. Função de Inferência     -> Processamento de frames, detecção e classificação real-time
└── 4. Validação Prática       -> Testes estruturados com imagens de amostragem padrão (Lena)
```

---

## 🚀 Como Executar o Projeto

1. Importe o notebook para o seu ambiente do **Google Colab**.
2. Execute a célula inicial para preparar o ambiente e instalar o OpenCV completo.
3. Execute os passos subsequentes para treinar o classificador com as feições geométricas simuladas.
4. Faça o upload de uma imagem própria ou utilize a imagem de teste padrão para ver o resultado do reconhecimento com as *bounding boxes* coloridas.

---

### 🧑‍💻 Autor

Desenvolvido por **Jefferson Santos**
*   [LinkedIn](https://www.linkedin.com/in/jefferson-pereira-ribeiro-santos-aba5a31b6/)
*   [GitHub](https://github.com/Mr-Jeffrey33)
