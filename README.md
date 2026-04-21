# 💻 Hardware Market Analysis - Laptop Prices

## 🛠️ Desafio Técnico: Data Engineering & Power Query
Neste segundo projeto, o foco foi o tratamento de dados complexos e "sujos" de hardware. O maior desafio foi a normalização de colunas de texto que misturavam capacidades de armazenamento em GB e TB com descrições de hardware (SSD, HDD, Hybrid).

### Tecnologias Aplicadas:
* **Power Query:** * Utilização de **Coluna de Exemplos** para extração inteligente de dados.
    * Normalização de escalas (Conversão de 1.0TB para 1000GB).
    * Resolução de erros de conversão de tipo (Data Type Casting).
* **Análise Estatística:**
    * Identificação de outliers de preço através de distribuição e perfil de coluna.
    * Criação da métrica de negócio: **Custo por GB ($/GB)**.

### 📊 Conclusões do Dashboard:
* Máquinas de categoria **Gaming** possuem o maior custo por GB, mas apresentam a melhor correlação entre preço e memória RAM.
* Identificamos marcas premium que mantêm preços elevados mesmo em capacidades de armazenamento reduzidas, caracterizando nichos de mercado específicos.
