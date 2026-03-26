# Convenções do Projeto

Este documento detalha os padrões de escrita, estilo e código adotados neste repositório para garantir a consistência e o rigor acadêmico.

## 1. Escrita Matemática (LaTeX)

Utilizamos a notação padrão de Álgebra Linear:

- **Escalares:** Letras minúsculas em itálico ($a, b, c$).
- **Vetores:** Letras minúsculas em negrito ($\mathbf{u}, \mathbf{v}, \mathbf{x}, \mathbf{b}$).
- **Matrizes:** Letras maiúsculas em itálico ($A, B, M$).
- **Espaços Vetoriais:** Letras maiúsculas em estilo quadro-negro ($\mathbb{R}^n, \mathbb{V}$).
- **Equações em Destaque:** Devem ser centralizadas usando cifrões duplos:
  $$Ax = b$$

## 2. Padrões de Código Python

Seguimos as práticas recomendadas para computação científica:

- **Bibliotecas:** 
  - NumPy como `np`
  - SymPy como `sp`
  - Matplotlib.pyplot como `plt`
- **Tipagem:** Sempre que possível, definir `dtype=float` em matrizes NumPy para evitar erros de truncamento em divisões.
- **Comentários:** Devem ser em português e focar na explicação do "porquê" (a lógica matemática) e não apenas no "como" (a sintaxe).

## 3. Estrutura dos Notebooks

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
7. **Rodapé de Navegação (Próximo Passo):** Bloco visual contendo uma mensagem de transição e um link direto para o próximo notebook da série, mantendo a consistência visual com o `Notebook 00`.

## 4. Visual Visualização

- **Gráficos:** Usar `plt.grid(True, linestyle='--')` para facilitar a leitura de coordenadas.
- **Eixos:** Sempre rotular os eixos e incluir legendas quando houver mais de um elemento gráfico.
- **Cores:** Usar padrões de cores distintos para vetores diferentes (ex: azul para entrada, vermelho para solução).
