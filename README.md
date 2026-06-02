# 🎮 Análise de Vendas de Videogames - Loja Ice

## 📌 Descrição do Projeto
Este projeto foi desenvolvido para a **Ice**, uma loja online internacional de videogames. O objetivo comercial é analisar dados históricos de vendas (desde os anos 80 até 2016), avaliações de usuários e de especialistas, gêneros e plataformas para identificar padrões determinantes de sucesso. 

Estes insights são fundamentais para identificar potenciais grandes sucessos de mercado e embasar o planejamento das campanhas publicitárias e de aquisição de estoque para o ano de 2017.

## 🎯 Objetivos
- Realizar a limpeza e o pré-processamento de dados reais (tratamento de valores ausentes, conversão de tipos de dados).
- Executar uma **Análise Exploratória de Dados (EDA)** para entender o ciclo de vida das plataformas (ex: tempo médio de vida de uma geração de consoles).
- Construir perfis de consumo detalhados para as regiões da **América do Norte (NA)**, **Europa (EU)** e **Japão (JP)**.
- Realizar **Testes de Hipóteses Estatísticas** (Teste T) para validar diferenças nas avaliações entre plataformas (Xbox One vs. PC) e entre gêneros (Ação vs. Esportes).

## 🛠️ Ferramentas e Tecnologias Utilizadas
- **Linguagem:** Python
- **Manipulação de Dados:** Pandas, NumPy
- **Visualização de Dados:** Matplotlib, Seaborn
- **Estatística:** SciPy (Testes de Hipótese)
- **Ambiente:** Jupyter Notebook

## 📈 Principais Insights de Negócio
1. **Liderança de Plataformas:** O PlayStation 4 (PS4) foi identificado como a plataforma de maior potencial e crescimento global para campanhas futuras.
2. **Impacto das Avaliações:** Descobriu-se que a avaliação dos críticos profissionais tem uma correlação positiva moderada com as vendas, enquanto a avaliação do público em geral não impacta as vendas de forma estatisticamente significativa.
3. **Diferenças Culturais no Consumo:**
   - *Ocidente (NA e EU):* O mercado é dominado por consoles de mesa (PS4/Xbox) e o gênero preferido é **Ação e Tiro (Shooter)**, com forte preferência por jogos de classificação "Mature" (Adultos).
   - *Japão:* Mercado único e dominado por consoles portáteis (Nintendo 3DS). O gênero preferido esmagadoramente é o **RPG**, e as classificações ocidentais (ESRB) têm pouca relevância na região.

## 📂 Como executar o projeto
1. Clone este repositório:
   ```bash
   git clone [https://github.com/SeuUsuario/video-games-data-analysis.git](https://github.com/SeuUsuario/video-games-data-analysis.git)
