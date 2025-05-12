# 📘 README - Projeto: Cadeias de Markov

## 🧾 Descrição do Projeto

Este projeto implementa e analisa **Cadeias de Markov discretas** com foco em:

* Visualização de dados,
* Simulação de trajetórias,
* Estudo da convergência.

O trabalho foi desenvolvido como parte de um exercício académico para consolidar conceitos de **probabilidade**, **álgebra linear** e **processos estocásticos** usando Python e Jupyter Notebook.

---

## 📚 Conceitos Aplicados

* **Matriz de Transição**: Estrutura fundamental de uma cadeia de Markov.
* **Propagação de Estados**: Distribuição de probabilidades após `k` passos.
* **Simulação Aleatória**: Geração de trajetórias segundo a matriz de transição.
* **Convergência e Estado Estável**: Análise de quantos passos são necessários para atingir uma distribuição limite.
* **Comparação Teórica x Experimental**: Verificação da consistência entre simulações e previsões teóricas.

---

## 🛠️ Tecnologias Utilizadas

* **Python 3.x**
* **Jupyter Notebook**
* **Bibliotecas**:

  * `NumPy` — Cálculo matricial e vetorial
  * `Matplotlib` — Gráficos e visualização de dados

---

## 📁 Estrutura do Projeto

```
Asignment/
│
├── Assignment0.ipynb        # Notebook principal com implementação e explicações
├── README.md               # Este arquivo
├── requirements.txt        # Dependências (NumPy, Matplotlib)
├── img/                    # Pasta de saída com gráficos gerados
│   ├── qsn3.png            # Evolução da distribuição por tempo
│   ├── qsn4c.png           # Passos necessários para convergência
│   ├── qsn4c_semilogy.png  # Gráfico em escala logarítmica
│   ├── qsn5.png            # Simulações de trajetórias
│   ├── qsn6.png            # Estado médio ao longo do tempo
│   └── qsn7.png            # Comparação entre teoria e simulação
```

---

## ⚙️ Como Executar

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/seu-usuario/Cadeias_de_Markov.git
   cd Cadeias_de_Markov
   ```

2. **Instale as dependências:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Abra o Jupyter Notebook:**

   ```bash
   jupyter notebook Assignment.ipynb
   ```

---

## ✅ Tarefas Implementadas

1. **Matriz de Transição** – Geração da matriz com regras específicas.
2. **Propagação** – Evolução da distribuição inicial por multiplicação matricial.
3. **Visualização** – Gráficos da distribuição de probabilidades em diferentes momentos.
4. **Convergência** – Cálculo dos passos necessários para atingir 50% de probabilidade no estado final.
5. **Amostragem Aleatória** – Simulação de trajetórias da cadeia.
6. **Estado Médio** – Evolução do valor médio dos estados ao longo do tempo.
7. **Comparação Teórica vs. Simulada** – Verificação de consistência entre a simulação e a teoria.

---

## 📌 Observações

* Os gráficos são **gerados automaticamente** ao executar o notebook e salvos em `img/`.
* As funções são vetorizadas com `NumPy`, **evitando laços `for` sempre que possível**.
* Cada questão é **testada e comentada** no próprio notebook.

---

## 📄 Licença

Distribuído sob a licença MIT. Veja [LICENSE](LICENSE) para mais informações.

