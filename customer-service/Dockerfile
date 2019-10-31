FROM mcr.microsoft.com/dotnet/core/sdk:2.2

LABEL maintainer="Arnor Erling Einarsson"

COPY . /app
WORKDIR /app
RUN dotnet restore

ENV ASPNETCORE_URLS http://*:80
ENV POSTGRES_DB customer_db
ENV POSTGRES_PASSWORD Abc.12345
ENTRYPOINT [ "dotnet", "run"]
