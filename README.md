Assistente Virtual com Inteligência Artificial 

Projeto desenvolvido como parte do laboratório "Construa Seu Assistente Virtual Com Inteligência Artificial" da Digital Innovation One (DIO), utilizando Python e Google Colab.
-----
 1. Documentação do Agente

O que faz: Um assistente virtual especializado em orientar estudantes e profissionais de tecnologia na escolha de ferramentas e práticas de Análise de Dados e Engenharia de Dados.

Para quem serve: Analistas juniores, estudantes e entusiastas de dados.

Comportamento: Didático, objetivo, focado em fatos da base de conhecimento e programado para evitar respostas inventadas (alucinações).

2. Base de Conhecimento (data/)

O assistente utiliza uma base estruturada com problemas comuns e soluções recomendadas, abordando tópicos como:

Processamento de grandes volumes de dados (PySpark / Apache Spark).

Criação de painéis e relatórios rápidos (Streamlit / Power BI).

Coleta e armazenamento de dados em tempo real (IoT).

3. Prompts do Agente (src/)

As instruções de sistema (System Instructions) configuradas no modelo garantem que a IA atue estritamente dentro do contexto fornecido:

"Você é um assistente virtual especialista em Análise de Dados e Engenharia de Dados. Responda às dúvidas da pessoa usuária utilizando estritamente as informações contidas na Base de Conhecimento..."

4. Aplicação Funcional

O projeto foi prototipado de forma prática no Google Colab, utilizando a biblioteca oficial do Google GenAI (google-genai) e o modelo gemini-3.5-flash para processar as interações de forma rápida e estável.

5. Avaliação e Métricas

Testes realizados para validar o funcionamento do assistente:

Pergunta na base: O assistente responde corretamente utilizando os dados estruturados.

Pergunta fora da base: O assistente recusa educadamente e informa que não possui dados suficientes sobre o assunto.

6. Pitch Final

Este protótipo demonstra como criar soluções de IA confiáveis e controladas utilizando bases de conhecimento customizadas, ideal para dar suporte rápido a tomadas de decisão técnicas sem depender de respostas genéricas.
