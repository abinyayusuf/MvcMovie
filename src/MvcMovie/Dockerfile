FROM microsoft/aspnet

ENV http_proxy "http://169.254.237.75:3128"
ENV https_proxy "http://169.254.237.75:3128"

COPY . /app
WORKDIR /app
RUN ["dotnet", "restore"]

EXPOSE 5004
ENTRYPOINT ["dotnet", "run"]
