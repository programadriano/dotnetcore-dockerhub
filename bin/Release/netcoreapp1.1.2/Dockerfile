FROM microsoft/dotnet:runtime
WORKDIR /dotnetcore
COPY . .
CMD dotnet restore / 
CMD dotnet run
ENTRYPOINT ["dotnet", "dotnetcore.dll"]
