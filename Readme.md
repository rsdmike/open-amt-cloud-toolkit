# Open AMT Cloud Toolkit

[![Discord](https://img.shields.io/discord/1063200098680582154?style=for-the-badge&label=Discord&logo=discord&logoColor=white&labelColor=%235865F2&link=https%3A%2F%2Fdiscord.gg%2FDKHeUNEWVH)](https://discord.gg/DKHeUNEWVH)

> Disclaimer: Production viable releases are tagged and listed under 'Releases'. All other check-ins should be considered 'in-development' and should not be used in production

Open Active Management Technology Cloud Toolkit (Open AMT Cloud Toolkit) offers open-source microservices and libraries to streamline Intel AMT integration, simplifying out-of-band management solutions for Intel vPro Platforms.

<br>

**For detailed documentation** about the Open AMT Cloud Toolkit, see the [docs](https://open-amt-cloud-toolkit.github.io/docs).

<br>

## Clone

**Important!** Make sure you clone this repo with the `--recursive` flag since it uses git submodules.

To clone live, in-development code (main branch):

```
git clone --recursive https://github.com/open-amt-cloud-toolkit/open-amt-cloud-toolkit.git
```

Alternatively, for steps to clone and Get Started with one of the tagged releases, [see our documentation](https://open-amt-cloud-toolkit.github.io/docs).

<br>

## Get Started

### There are multiple options to quickly deploy the Open AMT Cloud Toolkit:

<br>

### Local using Docker
The quickest and easiest option is to set up a local stack using Docker*, view our [Documentation Site](https://open-amt-cloud-toolkit.github.io/docs/) and click the Getting Started tab for How-To steps and examples.

<br>

### Cloud using Azure
For more experienced users, deploy the stack on Azure using the 'Deploy to Azure' button below. Note: This requires MPS, RPS, and Sample Web UI images to be built and accessible in a Container Image Registry such as Azure Container Registry (ACR), Docker Hub, or other options.

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fopen-amt-cloud-toolkit%2Fopen-amt-cloud-toolkit%2Fv2.5.0%2FazureDeploy.json)

Optionally, deploy from AzureCLI using the following commands:

``` bash
az group create --name openamt --location eastus
az deployment group create --resource-group openamt --template-file azureDeploy.json
```

Additional deployments, such as Kubernetes via Azure (AKS) or AWS (EKS), can be found in our [Documentation Site](https://open-amt-cloud-toolkit.github.io/docs/).

<br>

## Additional Resources

- For detailed documentation and Getting Started, [visit the docs site](https://open-amt-cloud-toolkit.github.io/docs).

- Find a bug? Or have ideas for new features? [Open a new Issue](https://github.com/open-amt-cloud-toolkit/open-amt-cloud-toolkit/issues).

- Need additional support or want to get the latest news and events about Open AMT? Connect with the team directly through Discord.

    [![Discord Banner 1](https://discordapp.com/api/guilds/1063200098680582154/widget.png?style=banner2)](https://discord.gg/DKHeUNEWVH)
