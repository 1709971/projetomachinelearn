## Para esse desafio foi utilizado os seguintes passos:

1. **Criar Espaço de Trabalho do Azure Machine Learning:**
   - Faça login no portal do Azure e crie um novo espaço de trabalho do Azure Machine Learning ou utilize um existente.
   - Configure as configurações, incluindo assinatura, grupo de recursos, nome do espaço de trabalho, região e anote os recursos padrão.

2. **Usar Aprendizado de Máquina Automatizado:**
   - Acesse o Azure Machine Learning studio e navegue até a página de ML Automatizado.
   - Configure um novo trabalho de ML Automatizado:
      - Nome do trabalho: mslearn-bike-automl
      - Nome do experimento: mslearn-bike-rental
      - Descrição: aprendizado de máquina automatizado para previsão de aluguel de bicicletas
      - Tipo de tarefa: Regressão
      - Selecione o conjunto de dados: Use dados históricos de aluguel de bicicletas do URL da web fornecido.
      - Configure as configurações da tarefa, configurações adicionais e opções de computação.
      - Envie o trabalho de treinamento e aguarde a conclusão.

3. **Revisar o Melhor Modelo:**
   - Após a conclusão do trabalho, revise o resumo do melhor modelo e suas métricas de desempenho.
   - Analise gráficos que exibem o desempenho do modelo, incluindo resíduos e valores previstos vs. verdadeiros.

4. **Implantar e Testar o Modelo:**
   - Implante o melhor modelo como um serviço da web usando o Azure Container Instance.
   - Teste o serviço implantado com dados de entrada de exemplo para receber o número previsto de aluguéis.

**Limpeza:**
- Exclua o ponto de extremidade implantado para evitar o uso desnecessário do Azure.
- Opcionalmente, exclua o espaço de trabalho do Azure Machine Learning e os recursos associados para evitar mais cobranças.

Este exercício fornece experiência prática na utilização das capacidades de aprendizado de máquina automatizado dentro do Azure Machine Learning para tarefas de modelagem preditiva.
