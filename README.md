# Semantic Kernel Hands Onlab

Welcome to the SemanticKernel Hands-On Lab! This repository provides practical hands on lab through notebooks to help you get experience with Semantic Kernel, a powerful tool for building intelligent applications.

## Semantic Kernel C# Notebooks

The current folder contains a few C# Jupyter Notebooks that demonstrate how to get started with
the Semantic Kernel. The notebooks are organized in order of increasing complexity.

To run the notebooks, we recommend the following steps:

- [Install .NET 8](https://dotnet.microsoft.com/download/dotnet/8.0)
- [Install Visual Studio Code (VS Code)](https://code.visualstudio.com)
- Launch VS Code and [install the "Polyglot" extension](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.dotnet-interactive-vscode).
  Min version required: v1.0.4606021 (Dec 2023).

The steps above should be sufficient, you can now **open all the C# notebooks in VS Code**.

VS Code screenshot example:

![image](https://user-images.githubusercontent.com/371009/216761942-1861635c-b4b7-4059-8ecf-590d93fe6300.png)

## Set your OpenAI API key

To start using these notebooks, be sure to add the appropriate API keys to `config/settings.json`.

You can create the file manually or you'll be asked during the first exercice

For Azure OpenAI:

```json
{
  "type": "azure",
  "model": "...", // Azure OpenAI Deployment Name
  "endpoint": "...", // Azure OpenAI endpoint
  "apikey": "..." // Azure OpenAI key
}
```

For OpenAI:

```json
{
  "type": "openai",
  "model": "gpt-3.5-turbo", // OpenAI model name
  "apikey": "...", // OpenAI API Key
  "org": "" // only for OpenAI accounts with multiple orgs
}
```

If you need an Azure OpenAI key, go [here](https://learn.microsoft.com/en-us/azure/cognitive-services/openai/quickstart?pivots=rest-api).
If you need an OpenAI key, go [here](https://platform.openai.com/account/api-keys)
