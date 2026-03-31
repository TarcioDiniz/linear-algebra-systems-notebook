# Convenções do Projeto

Este documento detalha os padrões de escrita, estilo e código adotados neste repositório para garantir a consistência e o rigor acadêmico, com base em bibliografia clássica de Álgebra Linear.

## 1. Escrita Técnica e Acadêmica

Para garantir um tom profissional e rigoroso, as seguintes diretrizes devem ser seguidas:

- **Tom de Voz:** Deve ser impessoal, técnico e didático. Evite termos coloquiais ou excessivamente informais.
  - **Não utilize:** "A Mágica", "peso morto", "esticar flechas", "mundo menor", "o coração da álgebra".
  - **Utilize:** "Propriedade fundamental", "vetor redundante", "transformação geométrica", "subespaço vetorial", "alicerce teórico".
- **Objetividade:** Vá direto ao ponto matemático. Explicações devem focar na definição formal e na interpretação geométrica rigorosa.
- **Redundância:** Não repita o mesmo conceito em diferentes notebooks. Se um conceito for pré-requisito, utilize links de navegação.
- **Citação Acadêmica:** Sempre que uma definição, teorema ou propriedade for baseada em referência bibliográfica, utilize o padrão autor-data ao final da afirmação (ex: (BOLDRINI et al., 1980)).

## 2. Escrita Matemática (LaTeX)

Utilizamos a notação padrão de Álgebra Linear:

- **Escalares:** Letras minúsculas em itálico ($a, b, c$).
- **Vetores:** Letras minúsculas em negrito ($\mathbf{u}, \mathbf{v}, \mathbf{x}, \mathbf{b}$).
- **Matrizes:** Letras maiúsculas em itálico ($A, B, M$).
- **Espaços Vetoriais:** Letras maiúsculas em estilo quadro-negro ($\mathbb{R}^n, \mathbb{V}$).
- **Equações em Destaque:** Devem ser centralizadas usando cifrões duplos:
  $$
  Ax = b
  $$

## 3. Padrões de Código Python

Seguimos as práticas recomendadas para computação científica:

- **Bibliotecas:** 
  - NumPy como `np`
  - Pandas como `pd`
  - SymPy como `sp`
  - Matplotlib.pyplot como `plt`
  - Seaborn como `sns`
- **Tipagem:** Sempre que possível, definir `dtype=float` em matrizes NumPy para evitar erros de truncamento em divisões.
- **Comentários:** Devem ser em português e focar na explicação do "porquê" (a lógica matemática), e não apenas no "como" (a sintaxe).

## 4. Estrutura dos Notebooks

Cada notebook deve seguir rigorosamente a seguinte estrutura:

1. **Cabeçalho Acadêmico:** 
   - Logo da universidade (`uepb_logo.png`) centralizado.
   - Nome da instituição: **Universidade Estadual da Paraíba (UEPB)**.
   - Identificação da série e dos autores (**Tarcio e Djonthas**).
2. **Metadados de Navegação:** Título do notebook, link para pré-requisitos e indicação do próximo passo.
3. **Objetivo:** Breve descrição do propósito pedagógico do notebook.
4. **Seções Teóricas:** Explicação dos conceitos com notação LaTeX padronizada.
5. **Exemplos Práticos:** Implementação em Python (NumPy/SymPy).
6. **Visualização:** Gráficos intuitivos para interpretação geométrica.
7. **Rodapé de Navegação (Próximo Passo):** Bloco visual contendo uma mensagem de transição e um link direto para o próximo notebook da série.

## 5. Ordem Didática dos Notebooks

A sequência de estudo é organizada para evitar repetições e garantir a construção lógica do conhecimento:

1. `00_introducao_e_roadmap.ipynb`
2. `01_conceitos_basicos_e_visualizacao_2d.ipynb`
3. `02_matrizes_e_operacoes.ipynb`
4. `03_eliminacao_gauss_e_gauss_jordan.ipynb`
5. `04_sistemas_e_rouche_capelli.ipynb`
6. `05_espacos_e_subespacos.ipynb`
7. `06_combinacao_linear_e_span.ipynb`
8. `07_independencia_linear.ipynb`
9. `08_base_e_dimensao.ipynb`
10. `09_transformacoes_lineares.ipynb`
11. `10_aplicacoes_praticas.ipynb`
12. `11_conclusao_e_exercicios.ipynb`

## 6. Visualização

- **Gráficos:** Usar `plt.grid(True, linestyle='--')` para facilitar a leitura de coordenadas.
- **Eixos:** Sempre rotular os eixos e incluir legendas quando houver mais de um elemento gráfico.
- **Cores:** Utilizar cores distintas para elementos diferentes (ex: azul para entrada, vermelho para solução).

## 7. Tabelas e Exibição de Dados

Para garantir uma apresentação visual superior e didática:

- **Tabelas em Markdown:** Devem ser escritas utilizando **HTML** bruto (`<table>`, `<thead>`, `<tr>`, `<th>`, `<td>`), garantindo melhor controle visual.
- **Exibição de Matrizes:**
  - Utilizar **SymPy** (`sp.Matrix`).
  - Não utilizar `print()`. Permitir renderização automática em LaTeX.
- **Tabelas e DataFrames:**
  - Utilizar **Pandas** apenas para dados não matemáticos.
  - Para matrizes matemáticas, utilizar `sp.Matrix`.

## 8. Citações e Referências Bibliográficas

Para manter o rigor acadêmico, as citações devem seguir o padrão **autor-data (ABNT NBR 10520)**.

### 8.1 Diretrizes

- **Títulos:** Não devem conter autores.
  - Correto: `### 2.1 Definição de Espaço Vetorial`

- **Uso de Citações:**
  - Inserir de forma discreta ao final de definições, teoremas ou explicações:
    - `(BOLDRINI et al., 1980)`
    - `(LAY, 2016)`

- **Blocos Teóricos:**