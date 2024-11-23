Avaliador de Redações com Processamento de Linguagem Natural (PLN)
Este projeto é um Avaliador de Redações desenvolvido em Python que utiliza técnicas de Processamento de Linguagem Natural (PLN) para analisar redações de vestibulares. Ele avalia a qualidade do texto em quatro critérios principais: coesão, coerência, ortografia e argumentação.

🚀 Funcionalidades
- Coesão: Avalia o uso de conectivos para verificar se o texto está bem conectado.
- Coerência: Usa análise de sentimentos para identificar possíveis inconsistências entre as frases.
- Ortografia: Identifica possíveis erros ortográficos no texto.
- Argumentação: Verifica a presença de termos que indicam uma argumentação sólida.
🛠️ Tecnologias Utilizadas
- Python
- spaCy: Para análise linguística e identificação de erros ortográficos.
- Transformers (Hugging Face): Para análise de sentimentos usando o modelo BERT em português.
- Regex: Para manipulação e segmentação de texto.
📋 Pré-requisitos
Certifique-se de ter o Python instalado na sua máquina. Este projeto foi desenvolvido com Python 3.10+.

Instalar dependências
Execute os seguintes comandos no terminal para instalar as bibliotecas necessárias:

bash
Copiar código
pip install spacy transformers

Baixe o modelo de linguagem para português do spaCy:

bash
Copiar código
python -m spacy download pt_core_news_sm


📂 Estrutura do Código
Funções principais:
avaliar_coesao: Analisa conectivos textuais.
avaliar_coerencia: Verifica consistência no sentimento entre frases.
avaliar_ortografia: Detecta erros ortográficos.
avaliar_argumentacao: Identifica termos argumentativos.
Função principal:
avaliar_redacao: Faz a análise completa da redação.

📈 Melhorias Futuras
Avaliar a estrutura da redação (introdução, desenvolvimento e conclusão).
Implementar correção automática de erros ortográficos.
Integrar um sistema de feedback detalhado para cada critério.

🤝 Contribuindo
Sinta-se à vontade para abrir issues ou enviar pull requests para melhorar este projeto.

Desenvolvido com ❤️ e curiosidade por [ANISTON]. 🚀
