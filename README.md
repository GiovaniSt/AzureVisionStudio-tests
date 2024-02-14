# Reading text in Azure Vision Studio

In this exercise I've used Azure AI service to explore the optical character recognition capabilities of Azure AI Vision. Using Vision Studio to experiment with extracting text from images, without having to write any code.

A common computer vision challenge is to detect and interpret text embedded within an image. This is known as optical character recognition (OCR). In this exercise I used an Azure AI services resource, which includes Azure AI Vision services. Vision Studio is used to try out OCR with different types of images.

1) First I created an Azure AI services resource at [Azure portal](https://portal.azure.com).
2) In create a resource button, search for Azure AI services. Select create an Azure AI services plan. Then I've configured it with the following settings:
- Subscription: Your Azure subscription.
- Resource group: Select or create a resource group with a unique name.
- Region: East US.
- Name: Enter a unique name.
- Pricing tier: Standard S0.

3) Next, connect the Azure AI services resource provisioned above to [Vision Studio](https://portal.vision.cognitive.azure.com).
- On the Vision Studio home page, view all resources under the Getting started with Vision heading.
<img src="https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/media/analyze-images-vision/vision-resources.png">

- On the Select a resource to work with page, select the resource created as default resource.
<img src="https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/media/analyze-images-vision/default-resource.png">

4) On the Getting started with Vision landing page > Optical character recognition > Extract text from images tile.
