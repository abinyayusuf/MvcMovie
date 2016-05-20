FROM microsoft/dotnet:latest

ENV http_proxy "http://169.254.237.75:3128"
ENV https_proxy "http://169.254.237.75:3128"

COPY . /app
WORKDIR /app
RUN ["dotnet", "restore"]

<<<<<<< HEAD
EXPOSE 5000
=======
EXPOSE 5004
>>>>>>> 02f986a94da47abc307d014b9e7e7073e00a21c6
ENTRYPOINT ["dotnet", "run"]
