A console app to analyze .PDF invoice files using Azure AI Document Intelligence services. The project uses Azure AI Form Recognizer's Document Analysis to return relevant analytics about the selected invoice .PDF file.

Written in C#, using Visual Studio 2022.

**Must use your own Azure API key and endpoint for the code to function properly.

Build Usage:

1. Download Visual Studio 2022
2. Pull repository
3. Install the required package using NuGet package manager in VS (Azure.AI.FormRecognizer)
4. Build and run

*Example output using the following invoice .PDF:
https://raw.githubusercontent.com/Azure-Samples/cognitive-services-REST-api-samples/master/curl/form-recognizer/sample-invoice.pdf


![Output](https://github.com/Biltoa/AIDocumentAnalysis/assets/86389078/675642d7-f6a1-42a2-8f74-8b653b58d9da)
