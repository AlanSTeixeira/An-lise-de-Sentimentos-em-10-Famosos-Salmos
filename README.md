# An-lise-de-Sentimentos-em-10-Famosos-Salmos

# Análise de Sentimentos nos Salmos (Português x Inglês)

Este projeto realiza uma análise de sentimentos dos Salmos da Bíblia, utilizando técnicas de **Processamento de Linguagem Natural (NLP)**. A análise foi feita tanto na versão **em português (Almeida Corrigida Fiel)** quanto na **versão em inglês (King James Version)**, permitindo uma comparação entre os sentimentos detectados em cada idioma.

## Objetivos

* Realizar a limpeza e processamento dos textos dos Salmos.
* Identificar e visualizar as palavras mais frequentes.
* Gerar **nuvens de palavras**.
* Aplicar **análise de sentimentos** usando a biblioteca `TextBlob`.
* Comparar os resultados de sentimento entre os textos em português e em inglês.
* Discutir os impactos da tradução nos resultados computacionais.

## Sobre os Dados

Os Salmos em português foram extraídos do site:
[https://www.bibliaonline.com.br/acf/sl](https://www.bibliaonline.com.br/acf/sl)
Os textos foram organizados e salvos em arquivos `.docx` para facilitar o processamento automático.

A versão em inglês dos Salmos utilizada foi a King James Version (KJV), disponível em fontes públicas e também organizada em `.docx`.

## Tecnologias e Bibliotecas

* Python
* Pandas
* Matplotlib & Seaborn
* WordCloud
* NLTK
* TextBlob
* Deep Translator
* docx (python-docx)

## Estrutura do Projeto

```
├── salmos_pt.docx                # Texto completo dos Salmos em português
├── salmos_en.docx                # Texto completo dos Salmos em inglês
├── analise_salmos.py             # Script principal com leitura, pré-processamento e análises
├── comparativo_sentimentos.png   # Gráfico comparativo final (PT x EN)
├── README.md                     # Este arquivo
```

## Etapas do Projeto

1. **Leitura dos arquivos `.docx`**
2. **Separação de cada Salmo individualmente**
3. **Limpeza do texto e remoção de stopwords**
4. **Geração de nuvens de palavras traduzidas**
5. **Análise de sentimentos com `TextBlob`**
6. **Visualização dos resultados com gráficos**
7. **Comparação dos sentimentos nos dois idiomas**

## Principais Insights

* Alguns Salmos considerados positivos por interpretação humana (como o Salmo 1) foram classificados como negativos na versão em português, possivelmente por termos como "ímpios", "perecer", "pecadores", etc.
* A versão em inglês apresentou polaridades mais coerentes com a leitura tradicional dos Salmos.
* Diferenças linguísticas e nuances da tradução impactam fortemente os resultados automatizados de sentimentos.

## Observações

* A análise de sentimentos é feita de forma **automática**, e portanto, **não substitui a interpretação teológica ou literária** dos textos.
* O projeto foi realizado com fins educacionais e de demonstração de técnicas de NLP.

## Autor

Alan da Silva Teixeira
Belford Roxo - RJ
Cientista de Dados | Fisioterapeuta | Apaixonado por tecnologia e linguagem natural
