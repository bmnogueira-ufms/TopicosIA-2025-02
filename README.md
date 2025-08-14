# Tópicos em Inteligência Artificial (2025/2)

> Repositório da disciplina de graduação da FACOM/UFMS focada em **Modelos de Linguagem (LLMs)**: fundamentos, prática e aplicações.

[![Abrir no Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bmnogueira-ufms/TopicosIA-2025-02)  
---

## Sumário
- [Visão geral](#visão-geral)
- [Ementa e objetivos](#ementa-e-objetivos)
- [Pré-requisitos](#pré-requisitos)
- [Estrutura do repositório](#estrutura-do-repositório)
- [Como usar (Colab ou local)](#como-usar-colab-ou-local)
  - [Google Colab (recomendado)](#google-colab-recomendado)
  - [Ambiente local (venv)](#ambiente-local-venv)
- [Licença](#licença)
- [Contato](#contato)

---

## Visão geral
Esta disciplina apresenta **modelos de linguagem** desde representações clássicas (Bag-of-Words e n-gramas) até **Transformers** e **LLMs** modernos. A abordagem é **mão na massa**: cada aula traz um *notebook* explicativo, código e exercícios.

- **Docente:** Prof. Bruno Nogueira (FACOM/UFMS)  
- **Semestre:** 2025/2  
- **Linguagem:** Python  
- **Principais libs:** scikit-learn, PyTorch, Hugging Face (Transformers/Datasets), LangChain (quando aplicável)

---

## Ementa e objetivos
**Ementa (resumo):**
- Introdução a modelos de linguagem em IA  
- Arquiteturas: RNNs, LSTMs, **Transformers**  
- **LLMs** (GPT e similares): uso e limites  
- Pré-treinamento, *fine-tuning*, *prompting* e **RAG**  
- Aplicações: geração, tradução, sumarização, sentimento  
- Ética: viés, interpretabilidade, impacto social

**Ao final, você será capaz de:**
1. Explicar e comparar representações textuais (BoW, n-gramas, **embeddings**).  
2. Implementar e avaliar modelos clássicos e neurais para PLN.  
3. Operar *pipelines* com **Transformers/LLMs**, *prompting* e **RAG**.  
4. Discutir implicações éticas e limitações de LLMs.

---

## Pré-requisitos
- Programação em **Python** (básico/intermediário).  
- Noções de **Álgebra Linear**, **Probabilidade/Estatística** e **Aprendizado de Máquina**.  
- Familiaridade com Jupyter/Google Colab.

---

## Estrutura do repositório
```bash
.
├── aulas/           # Notebooks da disciplina (.ipynb)
├── images/          # Figuras usadas nos notebooks/README
├── .gitignore
├── readme.md
└── requirements.txt # Dependências via pip
```

---

## Como usar (Colab ou local)

### Google Colab (recomendado)
Opção 1 — Abrir direto pelo *badge* no topo.  
Opção 2 — Clonar o repositório dentro do Colab:

    # Em uma célula do Colab:
    !git clone https://github.com/bmnogueira-ufms/TopicosIA-2025-02
    %cd TopicosIA-2025-02

    # Instalar as dependências do projeto:
    !pip install -r requirements.txt

Após clonar, caminhos relativos (ex.: `images/figura.png`) funcionam normalmente.  
Para exibir uma imagem no notebook: `![Evolução](images/evolucao_modelos.png)`.

### Ambiente local (venv)
1) **Clone** o repositório:

    git clone https://github.com/bmnogueira-ufms/TopicosIA-2025-02
    cd TopicosIA-2025-02

2) **Crie e ative** um ambiente virtual:

    python -m venv .venv
    # Linux/macOS
    source .venv/bin/activate
    # Windows (PowerShell)
    .venv\Scripts\Activate.ps1

3) **Instale** as dependências:

    pip install --upgrade pip
    pip install -r requirements.txt

4) **Execute** o Jupyter:

    jupyter lab   # ou: jupyter notebook

---

## Licença
- **Código**: MIT  
- **Conteúdo (textos/imagens da disciplina)**: CC BY-NC 4.0

---

## Contato
**Prof. Bruno Nogueira — FACOM/UFMS**  
E-mail: bruno.nogueira@ufms.br