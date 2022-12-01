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