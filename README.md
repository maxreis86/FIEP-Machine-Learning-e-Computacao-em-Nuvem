# FIEP-Machine-Learning-e-Computacao-em-Nuvem

### Bootcamp 3 (Sistemas Inteligentes) do curso de Pós-Graduação em Engenharia de Dados e Inteligência Artificial nas Faculdades da Industria

Ao final de curso você estará apto(a) a desenvolver e implementar um modelo de Machine Learning usando as ferramentas disponíveis na Azure. Vamos começar 🚀

## Criar uma conta na Azure

1. Use esse link para criar sua conta e incluir um método de pagamento
[azure.microsoft.com/pt-br/free](https://azure.microsoft.com/pt-br/free/)<br>
Você receberá um crédito de 200 dólares para produtos e serviços do Azure
2. Se você já tem uma conta na Azure, pode logar com sua conta
3. Ao logar na conta clique na opção [Criar um grupo de recursos](https://portal.azure.com/?quickstart=true#create/Microsoft.ResourceGroup) e preencha os dados abaixo
4. Assinatura: Azure subscription 1
5. Grupo de recursos: FIEP-ML
6. Região: (South America) Brazil South
7. Depois clique em "Revisar + criar"
8. Clique em "Criar"

## Azure Machine Learning

1. Agora vamos criar um ambiente para machine learning
2. No conto superior direito clique em "Criar um recurso"
3. No campo de busca, procure por Azure Machine Learning
4. Ao abrir o recurso de Azure Machine Learning, no camplo "Plano" deixe selecionado "Azure Machine Learning" e clique em "Criar"
5. Assinatura: Azure subscription 1
6. Grupo de recursos: FIEP-ML
7. Nome do workspace: FIEP-AZURE-ML-1
8. Região: Brazil South
9. Deixe os demais campos como estão
10. Clique em "Examinar + criar"
11. Clique em "Criar"
12. Quando aparecer a mensagem "A implantação foi concluída", clique em "Ir para o recurso"
13. E depois clique em "Iniciar o estúdio"
14. Após abrir o estúdio clique em "Compute" no canto inferior esquerdo
15. Clique em "New" e na tela seguinte preencha com os dados abaixo
16. Compute name: fiep-cpu
17. Location: brazilsouth
18. Virtual machine type: CPU
19. Virtual machine size: select from all options
20. Name: Standard_A1_v2
21. Depois clique em "Create"
22. Após iniciar a clique em "Terminal"
23. Digite o comando: git clone https://github.com/maxreis86/FIEP-Machine-Learning-e-Computacao-em-Nuvem.git
24. Clique novamente em "Compute" no canto inferior esquerdo
25. Em "Applications", clique em JupyterLab
24. Na aba "File Browser" abra a pasta FIEP-Machine-Learning-e-Computacao-em-Nuvem e depois aula_01_titanic_h2o_automl
25. Execute os códigos nos arquivos 1_Data_Prep.ipynb, 2_Fast_Machine_Learning.ipynb e 3_Explaining_Model.ipynb. Para executar esses códigos escolha o Kernel "Python 3.8 - AzureML" no canto superior direito da tela

## CPU vs GPU
1. [H2O AutoML](https://www.kaggle.com/code/maxreis/fiep-digit-recognizer-c-h2o-automl)
2. [Keras](https://www.kaggle.com/code/maxreis/fiep-digit-recognizer-c-keras)
3. [PyTorch](https://www.kaggle.com/code/maxreis/fiep-digit-recognizer-c-pytorch)


# Avaliação Final

A nota final será composta pelas três atividades abaixo que devem ser entreges até o dia **28/12**
Para entender com mais detalhes o que precisa ser entrege veja esse [vídeo](https://sesisenaiprorg-my.sharepoint.com/:v:/g/personal/maxuel_reis3819_sesisenaipr_org_br/EYeK1RbqLixMitaq24EjbnEBdagu8aiMq7ztyiqyijp73Q?e=opYNCA) com uma explicação.

1. Executar os códigos 1_Data_Prep.ipynb, 2_Fast_Machine_Learning.ipynb e 3_Explaining_Model.ipynb disponíveis [aqui](https://github.com/maxreis86/FIEP-Machine-Learning-e-Computacao-em-Nuvem/tree/main/aula_02_titanic_kmeans). Fazer as análises dos outputs gerados no código 3_Explaining_Model.ipynb. Criar um documento no Google Docs e escrever as características principais de cada Cluster. Pode incluir as gráficos utilizados na sua análise. Para ajudar no entendimento, veja o vídeo dessa aula nesse link [aqui](https://sesisenaiprorg-my.sharepoint.com/personal/maxuel_reis3819_sesisenaipr_org_br/_layouts/15/stream.aspx?id=%2Fpersonal%2Fmaxuel%5Freis3819%5Fsesisenaipr%5Forg%5Fbr%2FDocuments%2FRecordings%2FFIEP%2D20221202%5F210226%2DGrava%C3%A7%C3%A3o%20de%20Reuni%C3%A3o%2Emp4&ga=1)
2. Fazer o deploy do código [cluster_model.py](https://github.com/maxreis86/FIEP-Machine-Learning-e-Computacao-em-Nuvem/blob/main/aula_02_titanic_kmeans/kmeans_function/cluster_model.py) usando Azure Functions conforme explicado na aula do dia 08/12 disponível [aqui](https://sesisenaiprorg-my.sharepoint.com/personal/maxuel_reis3819_sesisenaipr_org_br/_layouts/15/stream.aspx?id=%2Fpersonal%2Fmaxuel%5Freis3819%5Fsesisenaipr%5Forg%5Fbr%2FDocuments%2FRecordings%2FFIEP%20Machine%20Learning%20e%20Computacao%20em%20Nuvem%2D20221208%5F211336%2DGrava%C3%A7%C3%A3o%20de%20Reuni%C3%A3o%2Emp4&ga=1). Incluir o print do Portal Azure mostrando a função implementada com sucesso.
3. Criar um fork, executar e realizar um submit na competição [Digit Recognizer](https://www.kaggle.com/competitions/digit-recognizer) do Kaggle para os códigos [FIEP - Digit Recognizer c/ H2O AutoML](https://www.kaggle.com/code/maxreis/fiep-digit-recognizer-c-h2o-automl), [FIEP - Digit Recognizer c/ Keras](https://www.kaggle.com/code/maxreis/fiep-digit-recognizer-c-keras) e [FIEP - Digit Recognizer c/ PyTorch](https://www.kaggle.com/code/maxreis/fiep-digit-recognizer-c-pytorch) conforme a explicação da aula disponível [aqui](https://sesisenaiprorg-my.sharepoint.com/:v:/g/personal/maxuel_reis3819_sesisenaipr_org_br/EZ8C7god7r9GidE6kh6BTpgByjPbFXZbKxMicaFKkmbP-w?e=r4pNhy). Incluir os links dois seus três código no mesmo documento do Google Docs usado nas atividades anteriores.

Me enviem o documento por e-mail (maxreis86@gmail.com) ou por Whatsapp.

# ATENÇÃO: NÃO esqueça de remover seu cartão de crédito da sua conta na Azure, porque você começará a ser cobrado após 30 dias da data de criação da conta.
