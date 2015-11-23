FROM microsoft/aspnet
ADD . /app
WORKDIR /app

EXPOSE 5004

ENTRYPOINT ["cmd.exe", "/k", "SelfHost.exe"]