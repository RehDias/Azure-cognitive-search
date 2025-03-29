# Estudo sobre Busca Cognitiva - Dio

## Introdução

A **busca cognitiva** é uma tecnologia que aprimora a pesquisa de informações em grandes volumes de dados, utilizando recursos de **inteligência artificial** para melhorar a indexação e a recuperação de documentos.

A **Dio (Digital Innovation One)** realizou um estudo prático sobre **Azure AI Search**, uma ferramenta da Microsoft que permite criar soluções de busca enriquecidas com IA.

---

## 📌 Passo a Passo para Configurar uma Pesquisa Cognitiva

### 1️⃣ Criar um Recurso do Azure AI Search

1. Acesse o [Portal do Azure](https://portal.azure.com/).
2. Procure por **"Azure AI Search"** e clique em **Criar**.
3. Configure:
   - **Nome do recurso**: Escolha um nome único.
   - **Região**: Escolha a mais próxima.
   - **Camada de Preço**: Selecione conforme sua necessidade.
4. Clique em **Revisar + Criar** e aguarde a implantação.

### 2️⃣ Criar um Recurso do Azure AI Services

1. No Portal do Azure, clique em **Criar um recurso** e procure por **Azure AI Services**.
2. Configure:
   - **Grupo de Recursos**: O mesmo do Azure AI Search.
   - **Região**: A mesma escolhida anteriormente.
   - **Camada de Preço**: Standard S0.
3. Clique em **Revisar + Criar** e finalize a criação.

### 3️⃣ Criar uma Conta de Armazenamento

1. No Portal do Azure, clique em **Criar um recurso** e procure por **Storage Account**.
2. Defina:
   - **Nome**: Um nome único para a conta.
   - **Região**: A mesma utilizada nos recursos anteriores.
3. Conclua a criação do recurso.

### 4️⃣ Fazer Upload de Documentos para o Azure Storage

1. Utilize os arquivos disponibilizados no [exercício](https://aka.ms/mslearn-coffee-reviews).
2. No portal, acesse **Storage Accounts** > **Containers** > **Criar um novo contêiner**.
3. Faça o upload dos documentos de análise de reviews de café.

### 5️⃣ Indexar os Documentos no Azure AI Search

1. No recurso **Azure AI Search**, acesse **Data Sources** e crie uma nova fonte de dados.
2. Configure a conexão com o **Storage Account** e selecione os documentos enviados.
3. Crie um **Índice** para armazenar os dados extraídos.
4. Configure **Habilidades Cognitivas**, se necessário (ex.: extração de entidades, sentimentos, OCR).
5. Salve e execute o processo de indexação.

### 6️⃣ Consultar o Índice Criado

1. No portal do Azure, acesse **Explorador de Pesquisa**.
2. Execute consultas para validar os dados indexados.
3. Ajuste as configurações para otimizar a pesquisa.

## Exemplo: 
<div align="center">
  <img src="https://github.com/user-attachments/assets/fe1c8fb7-a6dc-498a-973c-8f83a5497d09" alt="exemplo1" width=45% />&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://github.com/user-attachments/assets/f5509c56-b4c5-408c-9089-22985e621858" alt="exemplo2" width=45% />
</div>

### 7️⃣ Revisar o Knowledge Store

1. No **Knowledge Store**, visualize os dados enriquecidos por IA.
2. Os dados podem estar armazenados como projeções ou tabelas, facilitando a análise.
3. Explore os resultados para entender como os insights foram gerados.<br>

## Exemplo:

<div align="center">
  <img src="https://github.com/user-attachments/assets/1ff1ea64-38c0-4714-a5e8-cd6d767a76c5" alt="exemplo2" width=50% height=300px />&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://github.com/user-attachments/assets/f12850ae-31df-4d7c-ace2-3dccc4e68e6e" alt="exemplo2" width=45%  />
</div>

---

## 🚀 Possibilidades e Ferramentas que se Beneficiam

O **Azure AI Search** é ideal para diversas aplicações, incluindo:

- **E-commerce**: Melhor pesquisa e recomendações de produtos.
- **Atendimento ao Cliente**: Base de conhecimento inteligente.
- **Saúde**: Indexação de prontuários eletrônicos.
- **Educação**: Busca aprimorada em bibliotecas digitais.
- **Mídia**: Organização e recuperação de arquivos multimídia.

---

## 📊 Insights e Aprendizados

✅ **Automatização eficiente**: A IA melhora a indexação e recuperação de dados. <br>
✅ **Escalabilidade**: O Azure AI Search se adapta a grandes volumes de dados. <br>
✅ **Integração com IA**: Insights aprimorados com análise semântica e extração de entidades. <br>
✅ **Fácil implementação**: Processo intuitivo com opção de personalização avançada. <br>
✅ **Melhoria na experiência do usuário**: Pesquisas mais precisas e relevantes. <br>

---

## 🔗 Referências

- [Microsoft AI Fundamentals - Azure AI Search](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html)
- [Documentação Oficial do Azure AI Search](https://learn.microsoft.com/pt-br/azure/search/)

Este estudo mostrou como a **busca cognitiva** pode transformar a pesquisa de informações, trazendo mais inteligência e eficiência para aplicações modernas! 🚀

