# Sistema-de-Notas-de-Alunos-Array-
**Sistema em Python para controle e análise de notas de alunos com pré-alocação de memória, validação de entradas e busca de estatísticas da turma.**

# 📊 Sistema de Controle de Notas dos Alunos

Um sistema simples em Python para gerenciamento e análise de notas escolares, desenvolvido para demonstrar conceitos fundamentais de lógica de programação e manipulação de vetores (arrays).

---

## 📌 Sobre o Projeto

O projeto consiste em um menu interativo executado no terminal que permite cadastrar notas de alunos (com limite de 50 registros) e obter estatísticas sobre a turma, como média, menor e maior nota.

### 🎯 Funcionalidades
- **Inserção de Notas:** Permite cadastrar notas de 0 a 10 com validação de entrada de dados.
- **Cálculo da Média:** Processa e exibe a média geral das notas cadastradas.
- **Busca por Extremos:** Identifica e exibe a menor e a maior nota da turma.
- **Tratamento de Erros:** Evita exceções por entradas inválidas de texto ou números fora da faixa permitida.
- **Estrutura de Menu:** Execução contínua até que o usuário opte por encerrar o programa.

---

## 🛠️ Conceitos e Tecnologias Utilizadas

- **Linguagem:** Python 3.10+
- **Estrutura de Dados:** Vetor pré-alocado fixo com `None` para simular alocação de memória estática.
- **Estruturas de Controle:** 
  - Estrutura condicional avançada com `match/case` (Python 3.10+).
  - Laços de repetição `while` para o fluxo principal e navegação no array.
- **Funções:** Modularização para exibição do menu, inserção de dados e busca de valores mínimos/máximos.
- **Tratamento de Exceções:** Uso de `try/except` para prevenir erros com `ValueError`.

---

## 🚀 Como Executar o Projeto

### Pré-requisitos
Ter o **Python 3.10** ou superior instalado na sua máquina.

### Passo a passo
1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/seu-usuario/nome-do-seu-repositorio.git](https://github.com/seu-usuario/nome-do-seu-repositorio.git)
