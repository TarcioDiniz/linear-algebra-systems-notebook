# Sistemas Lineares: Teoria, Geometria e Aplicações com Python

Este repositório contém uma série de notebooks Jupyter dedicados ao estudo de **Sistemas Lineares**, combinando o rigor acadêmico da álgebra linear com visualizações geométricas intuitivas e implementação prática em Python.

### ✍️ Créditos e Reconhecimento

Gostaria de dar os devidos créditos aos modelos de LLM **Gemini**, **ChatGPT** e **Junie**, que foram fundamentais para planejar e estruturar todo o conteúdo deste projeto. A colaboração destas inteligências artificiais permitiu um desenvolvimento ágil e metodológico, garantindo a organização e a profundidade pedagógica aqui apresentadas.

---

## 🏛️ Estrutura do Repositório

O projeto está organizado para facilitar a navegação e o estudo progressivo:

- `notebooks/`: Contém os notebooks Jupyter da série, numerados de 00 a 11.
- `assets/`: Imagens ou diagramas utilizados nos notebooks.
- `references/`: Bibliografia detalhada e links úteis. Veja o [README de referências](./references/README.md).
- `docs/`: Documentação complementar e **convenções de escrita** (`docs/conventions.md`).

---

## 📚 Tutorial Passo a Passo (Roadmap)

A série foi projetada para ser seguida na ordem numérica, transformando conceitos abstratos em ferramentas práticas e visualizáveis.

| Ordem | Tutorial | Tópico Principal |
| :--- | :--- | :--- |
| 00 | [**Introdução e Roadmap**](./notebooks/00_introducao_e_roadmap.ipynb) | Visão geral, motivação e guia de estudo. |
| 01 | [**Conceitos Básicos e Visualização 2D**](./notebooks/01_conceitos_basicos_e_visualizacao_2d.ipynb) | Definições e forma $Ax=b$. |
| 02 | [**Matrizes e Operações**](./notebooks/02_matrizes_e_operacoes.ipynb) | Manipulação matricial com NumPy e SymPy. |
| 03 | [**Eliminação de Gauss e Gauss-Jordan**](./notebooks/03_eliminacao_gauss_e_gauss_jordan.ipynb) | Algoritmos de escalonamento (RREF). |
| 04 | [**Sistemas e Rouché-Capelli**](./notebooks/04_sistemas_e_rouche_capelli.ipynb) | Classificação de sistemas e Teorema de R-C. |
| 05 | [**Espaços e Subespaços**](./notebooks/05_espacos_e_subespacos.ipynb) | Definição formal e axiomas. |
| 06 | [**Combinação Linear e Span**](./notebooks/06_combinacao_linear_e_span.ipynb) | Espaço coluna e subespaço gerado. |
| 07 | [**Independência Linear**](./notebooks/07_independencia_linear.ipynb) | Conceito de LI e LD. |
| 08 | [**Base e Dimensão**](./notebooks/08_base_e_dimensao.ipynb) | O esqueleto do espaço vetorial. |
| 09 | [**Transformações Lineares**](./notebooks/09_transformacoes_lineares.ipynb) | Matrizes como funções. |
| 10 | [**Aplicações Práticas**](./notebooks/10_aplicacoes_praticas.ipynb) | Casos reais: Tráfego e Interpolação. |
| 11 | [**Conclusão e Exercícios**](./notebooks/11_conclusao_e_exercicios.ipynb) | Consolidação do aprendizado. |

---

## 🛠️ Instalação e Execução

Este projeto utiliza o gerenciador de pacotes moderno [**uv**](https://github.com/astral-sh/uv).

### 1. Pré-requisitos
- Python instalado (gerenciado automaticamente pelo `uv`).
- Instale o `uv` se ainda não tiver:
  ```powershell
  powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
  ```

### 2. Configurando o Ambiente
Clone o repositório e execute o comando abaixo na raiz do projeto:
```bash
# Cria o ambiente virtual e instala as dependências
uv sync
```

### 3. Rodando os Notebooks
Para abrir os notebooks no VS Code ou Jupyter:
```bash
# Ativa o ambiente virtual (opcional, o VS Code reconhece automaticamente)
uv run jupyter lab
```
Ou simplesmente abra os arquivos `.ipynb` no seu editor favorito e selecione o kernel criado pelo `uv`.

---

## 📝 Convenções e Padrões

Para manter a consistência acadêmica, adotamos padrões rigorosos de notação e escrita.
O arquivo principal de diretrizes pode ser encontrado em: **[`docs/conventions.md`](./docs/conventions.md)**.

Alguns pontos principais:
1. **Notação de Matrizes:** Letras maiúsculas em itálico ($A$).
2. **Notação de Vetores:** Letras minúsculas em negrito ($\mathbf{x}$).
3. **Citações:** Padrão autor-data (ex: BOLDRINI, 1980).

---

## 🎓 Referências Principais

Consulte a lista completa em [`references/README.md`](./references/README.md).

- **BOLDRINI, José Luiz et al.** *Álgebra Linear*.
- **STRANG, Gilbert.** *Introduction to Linear Algebra*.
- **ANTON, Howard; RORRES, Chris.** *Álgebra Linear com Aplicações*.