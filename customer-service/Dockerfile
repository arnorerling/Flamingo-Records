FROM mcr.microsoft.com/dotnet/core/sdk:2.2

LABEL maintainer="Arnor Erling Einarsson & Emil Newel & Magnús Freyr Sveinsson"

COPY . /app
WORKDIR /app
RUN dotnet restore
RUN dotnet build

ENV ASPNETCORE_URLS http://+:80
ENTRYPOINT [ "dotnet", "run", "--project", "./customer-service"]
