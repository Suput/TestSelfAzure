FROM mcr.microsoft.com/dotnet/core/aspnet:2.2
WORKDIR /app
COPY Suput.TestSelfAzure/testdocker .
ENTRYPOINT ["dotnet", "testdocker.dll"]