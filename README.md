# Regressão com Redes Neurais Artificiais (RNA)

As **Redes Neurais Artificiais (RNAs)** também podem ser utilizadas para **regressão**, onde o objetivo é prever **valores contínuos** ao invés de categorias. Esse tipo de tarefa é conhecido como **regressão univariada**, quando há **uma única variável de saída** (target).

Essas redes são capazes de modelar relações complexas entre variáveis de entrada e uma saída numérica, mesmo em cenários com dados não lineares ou alta dimensionalidade.

### Por que usar RNA para regressão?

- Lida com **relações não-lineares** entre variáveis
- Pode ser usada com qualquer número de entradas
- Flexível em problemas onde outros modelos falham (como regressão linear)
- Ideal para prever valores como preço, temperatura, consumo etc.

### Funcionamento Intuitivo

Imagine que você deseja prever o **preço de um carro** com base em seu ano, potência, e quilometragem. A RNA aprende com os dados anteriores e estima o valor com base no que aprendeu.

---

## 📂 Estrutura dos Notebooks

### 1. `RNA2_Regressao_Unitaria_Automoveis_Orlando.ipynb`
**📌 Tarefa:** Prever o preço de automóveis com base em características  
**📚 Dataset:** Atributos de veículos (ano, motor, km, etc.)  
**🔍 Destaques:**
- Rede com uma única saída contínua
- Métrica de erro médio absoluto (MAE) e quadrático (MSE)
- Visualização do valor previsto vs. real

### 2. `RNA2_Regressao_Unitaria_Validacao_Cruzada_Orlando.ipynb`
**📌 Tarefa:** Avaliação da RNA com validação cruzada  
**📚 Dataset:** Mesmo conjunto com divisão em folds  
**🔍 Destaques:**
- Avaliação com `KFold` para melhor robustez
- Cálculo de média e desvio dos erros
- Análise gráfica da performance

---

## 📈 Métricas e Avaliação

As RNAs de regressão foram avaliadas com:

- **MAE (Erro Médio Absoluto)**
- **MSE (Erro Quadrático Médio)**
- **RMSE (Raiz do Erro Quadrático Médio)**
- **R² (Coeficiente de Determinação)**
- **Gráficos de dispersão e linhas de tendência**

---

## ⚙️ Técnicas Utilizadas

- Funções de ativação ReLU e linear
- Otimizadores como Adam
- Normalização dos dados de entrada
- Validação cruzada com `KFold`
"""
