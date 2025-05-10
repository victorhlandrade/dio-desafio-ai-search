# 🧪 Laboratório 11: Explorando um Índice do Azure AI Search (UI)
Este laboratório prático simula um cenário na empresa fictícia Fourth Coffee, onde você é encarregado de construir uma solução de knowledge mining para extrair insights de avaliações de clientes utilizando o Azure AI Search.

# 🎯 Objetivos do Laboratório
* Criar recursos do Azure necessários para a solução.

* Carregar documentos de avaliações de clientes em um armazenamento blob.

* Enriquecer os dados com habilidades de IA (AI Skills).

* Indexar os documentos usando o Azure AI Search.

* Consultar o índice criado.

* Revisar os resultados salvos no Knowledge Store.

# 🛠️ Recursos do Azure Utilizados
* Azure AI Search: Gerencia o processo de indexação e consulta dos dados.

* Azure AI Services: Fornece habilidades de IA para enriquecer os dados durante a indexação.

* Conta de Armazenamento (Blob Storage): Armazena os documentos de avaliações de clientes.

⚠️ Importante: Os recursos do Azure AI Search e Azure AI Services devem estar na mesma região para funcionarem corretamente.


# 📂 Etapas do Laboratório
* Criar Recursos do Azure:

* Azure AI Search: Criar um serviço com nome único, grupo de recursos e região especificados.

* Azure AI Services: Criar um recurso na mesma região e grupo de recursos do AI Search.

* Conta de Armazenamento: Criar uma conta de armazenamento com redundância local (LRS).

* Configurar o Armazenamento:

* Criar um contêiner chamado coffee-reviews com acesso público para leitura.

* Baixar e extrair os arquivos de avaliações de clientes de https://aka.ms/mslearn-coffee-reviews.

* Carregar os arquivos extraídos para o contêiner coffee-reviews.

# Indexar os Documentos:

* No portal do Azure, acessar o recurso do Azure AI Search.

* Utilizar o assistente "Importar dados" para criar um índice e um indexador.

* Configurar o enriquecimento de dados com habilidades de IA, como análise de sentimentos e extração de frases-chave.

# Consultar o Índice:

* Utilizar a interface do portal do Azure para realizar consultas no índice criado.

* Visualizar os resultados e verificar os insights extraídos, como sentimentos e frases-chave.

# Revisar o Knowledge Store:

* Acessar o Knowledge Store para visualizar os dados enriquecidos e estruturados.

* Analisar como os dados foram transformados e armazenados para facilitar consultas futuras.

Este laboratório oferece uma introdução prática ao Azure AI Search, demonstrando como integrar serviços de IA para transformar dados não estruturados em insights acionáveis. É uma excelente oportunidade para entender o processo de knowledge mining e como aplicar habilidades de IA em soluções de busca empresarial.

🔗 Acesse o laboratório completo aqui: https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html

# Observação: Por motivos de subscrição e custos, não consegui realizar a prática com os devidos prints.
