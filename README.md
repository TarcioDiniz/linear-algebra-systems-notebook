# Sistemas Lineares: Teoria, Geometria e Aplicações com Python

Este repositório contém uma série de notebooks Jupyter dedicados ao estudo de **Sistemas Lineares**, combinando o rigor acadêmico da álgebra linear com visualizações geométricas intuitivas e implementação prática em Python.

---

## 🏛️ Estrutura do Repositório

O projeto está organizado para facilitar a navegação e o estudo progressivo:

- `notebooks/`: Contém os notebooks Jupyter da série, numerados de 00 a 15.
- `assets/`: Imagens, diagramas e outros recursos visuais utilizados nos notebooks.
- `references/`: Material de apoio, bibliografia e links externos.
- `docs/`: Documentação complementar e guias de convenção.

---

## 📚 Tutorial Passo a Passo (Roadmap)

A série foi projetada para ser seguida na ordem numérica, transformando conceitos abstratos em ferramentas práticas e visualizáveis.

| Ordem | Tutorial | Tópico Principal |
| :--- | :--- | :--- |
| 00 | [**Introdução e Roadmap**](./notebooks/00_introducao_e_roadmap.ipynb) | Visão geral, motivação e guia de estudo. |
| 01 | [**Conceitos Básicos**](./notebooks/01_conceitos_basicos_e_visualizacao_2d.ipynb) | Definições, forma $Ax=b$ e visualização 2D. |
| 02 | [**Matriz Aumentada**](./notebooks/02_matriz_aumentada_e_representacao.ipynb) | Representação matricial e Teorema de Rouché-Capelli. |
| 03 | [**Métodos de Resolução**](./notebooks/03_metodos_resolucao_gauss_jordan.ipynb) | Algoritmos de Gauss e Gauss-Jordan (RREF). |
| 04 | [**Espaços Vetoriais**](./notebooks/04_espacos_vetoriais.ipynb) | Definição formal, axiomas e vetores em NumPy. |
| 05 | [**Subespaço**](./notebooks/05_subespaco.ipynb) | Condições espaciais, o vetor nulo e *Nullspace*. |
| 06 | [**Combinação Linear**](./notebooks/06_combinacao_linear.ipynb) | Combinando vetores e resolvendo sistemas com Python. |
| 07 | [**Subespaço Gerado**](./notebooks/07_subespaco_gerado.ipynb) | Span, espaço coluna em SymPy e visualização geométrica. |
| 08 | [**LI e LD**](./notebooks/08_li_e_ld.ipynb) | Extraindo vetores independentes (RREF) e matrizes. |
| 09 | [**Base**](./notebooks/09_base.ipynb) | O esqueleto do espaço: Dimensão e mudanças de base. |
| 10 | [**Geometria 3D**](./notebooks/10_geometria_3d_e_independencia_linear.ipynb) | Visualização 3D, Vetores LI/LD e Posto. |
| 11 | [**Transformações Lineares**](./notebooks/11_transformacoes_lineares_e_matrizes.ipynb) | Matrizes como funções: Núcleo e Imagem. |
| 12 | [**Aplicação: Tráfego**](./notebooks/12_aplicacao_fluxo_trafego.ipynb) | Modelagem de redes viárias urbanas reais. |
| 13 | [**Aplicação: Interpolação**](./notebooks/13_aplicacao_interpolacao_polinomial.ipynb) | Ajuste de curvas via Matriz de Vandermonde. |
| 14 | [**Prática: Exercícios**](./notebooks/14_pratica_exercicios_resolvidos.ipynb) | Consolidação: Resolução manual vs. computacional. |
| 15 | [**Conclusão**](./notebooks/15_conclusao_e_proximos_passos.ipynb) | Síntese final e transição para novos horizontes. |

---

## 🛠️ Tecnologias e Bibliotecas

Este projeto utiliza o ecossistema científico do Python:

- **NumPy:** Computação numérica e álgebra linear de alto desempenho.
- **SymPy:** Matemática simbólica (resoluções exatas e manipulação algébrica).
- **Matplotlib & Seaborn:** Visualizações 2D e 3D.
- **NetworkX:** Modelagem de redes (utilizado na aplicação de tráfego).

### Instalação

O projeto utiliza o gerenciador de pacotes `uv`. Para configurar o ambiente e instalar as dependências:

```bash
# Instala as dependências e cria o ambiente virtual
uv sync
```

---

## 📝 Convenções de Escrita

Para manter a consistência acadêmica, adotamos as seguintes convenções:

1. **Notação de Matrizes:** Letras maiúsculas em itálico ($A, B$).
2. **Notação de Vetores:** Letras minúsculas em negrito ($\mathbf{x}, \mathbf{b}$).
3. **Equações:** Centralizadas usando blocos LaTeX ($$Ax=b$$).
4. **Comentários de Código:** Em português, explicando a lógica matemática por trás da implementação.

---

## 🎓 Referências Principais

- STRANG, Gilbert. *Introduction to Linear Algebra*. 5th ed. Wellesley-Cambridge Press, 2016.
- ANTON, Howard; RORRES, Chris. *Álgebra Linear com Aplicações*. 10ª ed. Bookman, 2012.
- LAY, David C. *Linear Algebra and Its Applications*. 4th ed. Pearson, 2012.