# LINQ-commands

### LINQ 101 samples from Try .NET ([source repository](https://github.com/dotnet/try-samples))
#### Getting start with LINQ
1. Install dotnet and dotnet-try tool
   - [link to install dotnet](https://dotnet.microsoft.com/en-us/download)
   - [link for guide for installing dotnet-try tool](https://github.com/dotnet/try/blob/main/DotNetTryLocal.md)
      - make sure to follow the step for installing older version .NET Core 3.0 SDK
      - make sure to use the command line below to install the dotnet-try tool
        ```bash
          dotnet tool install -g --add-source "https://pkgs.dev.azure.com/dnceng/public/_packaging/dotnet-tools/nuget/v3/index.json" Microsoft.dotnet-try
        ```
2. clone the [try-sample repository](https://github.com/dotnet/try-samples)
3. located to the try-sample repository and locate to the 101-linq-samples
   ```bash
    cd <path>/try-sample/101-linq-samples
   ```
   ```bash
    dotnet try
   ```
4. finally it should locate you to a localhost, please hit advanced if the page is blocked
   - you should see
     [linq101](./images/linq101Samples.png)
