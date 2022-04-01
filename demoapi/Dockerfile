FROM mcr.microsoft.com/dotnet/aspnet:6.0-alpine
COPY bin/Debug/net6.0/publish .
EXPOSE 80
EXPOSE 7137
ENTRYPOINT ["dotnet", "demoapi.dll", "--environment=Development"]