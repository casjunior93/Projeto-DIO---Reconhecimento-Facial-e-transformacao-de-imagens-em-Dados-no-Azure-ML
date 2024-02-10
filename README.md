# Trabalhando com Machine Learning na Prática no Azure ML

Passo a passo do projeto Trabalhando com Machine Learning na Prática no Azure ML da DIO.

Links importantes:

[Explore Azure AI Services](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/02-content-safety.html)

[Explore Automated Machine Learning in Azure Machine Learning](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html)

[Fonte dos dados](https://aka.ms/bike-rentals) ou [link direto para os dados](https://raw.githubusercontent.com/MicrosoftLearning/mslearn-ai-fundamentals/main/data/ml/daily-bike-share.csv)

## Passo 1: Criando recurso do Face API no Azure AI Services

Primeiro precisei criar um recurso de Face API dentro Azure Ai Services.

![Img](./img/img1.gif)

Após o recurso ter sido criado, acessei o [Portal de Visão do Azure](https://portal.vision.cognitive.azure.com/gallery/featured). Na página inicial, acessei a aba "Face" e cliquei em "Detect faces in an images".

Na próxima página, em "Try it out", precisei informar o recurso criado anteriormente no Portal do Azure para testar. Sem escolher o recurso, não consegui obter a resposta do teste.

![Img](./img/img2.gif)

Então subi uma foto minha e consegui obter o resultado do teste.

![Img](./img/img3.gif)

Em seguida, tentei fazer um teste usando Python para acessar o serviço, porém não consegui terminar pois é necessário ser cliente ou um dos parceiros gerenciados pela Microsoft. Para ser aprovado, é necessário enviar o seguinte formulário e esperar a aprovação: [http://aka.ms/facerecognition](http://aka.ms/facerecognition).

[Clique aqui](Detecção_de_Faces_com_Face_API.ipynb) para ver o notebook que comecei para testar o Face API com Python.

Saiba mais sobre a limitação de API: [Recursos de Acesso Limitado para os serviços de IA do Azure](https://learn.microsoft.com/pt-br/azure/ai-services/cognitive-services-limited-access)
