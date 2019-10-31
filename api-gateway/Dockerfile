FROM mcr.microsoft.com/dotnet/core/sdk:2.2

LABEL maintainer="Arnor Erling Einarsson"



COPY . /app
WORKDIR /app
RUN dotnet restore
RUN dotnet build 

ENV ASPNETCORE_URLS=http://*:5000
ENTRYPOINT [ "dotnet", "run"]
