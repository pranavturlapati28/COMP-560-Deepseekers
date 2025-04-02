# COMP 560 Final Project Abstract  
**Group: DeepSeekers**

We will utilize AI to create a Recipe Generator using images of ingredients. The basic idea is to feed the AI pictures of various ingredients, which a large language model (LLM) and a visual language model will use to generate a recipe containing only those ingredients.

As part of our application, users would take a photo of the ingredients they have, and then the system would create a recipe using that input. It would first use a vision-language model to identify the items in the image. Then it would pass the identified ingredients to a large language model, which would generate an optimal recipe with all the ingredients provided.

This tool would be helpful for people who are new to cooking or those who want to make the most of the ingredients they have on hand.

This application will be built using Python and will rely on tools such as `transformers` and `PyTorch` for AI components, and `OpenCV` for recognizing the images. We can also create a user interface on top of the system to create a seamless user experience while using this tool.
