# dotnet-aspire-demo3

I am learning .NET 8 Aspire from different Video Courses, Books, and Websites.

## Features

Default Sample
Bicep Template
Subscription level deployments

## Few Commands

```powershell
D:\TSA\dotnet-aspire-demo3\Aspiredemo3\Aspiredemo3.AppHost> azd init

#Places the file in the root folder.
dotnet run --project .\Aspiredemo3.AppHost\Aspiredemo3.AppHost.csproj --publisher manifest --output-path ../aspire-manifest.json

azd auth login --scope https://management.azure.com//.default

D:\TSA\dotnet-aspire-demo3\Aspiredemo3\Aspiredemo3.AppHost> azd config set alpha.infraSynth on
D:\TSA\dotnet-aspire-demo3\Aspiredemo3\Aspiredemo3.AppHost> azd config set infrastructure.provider terraform
D:\TSA\dotnet-aspire-demo3\Aspiredemo3\Aspiredemo3.AppHost> azd infra synth

azd up
```
