FROM mcr.microsoft.com/dotnet/samples:aspnetapp
USER root
RUN apk update 
RUN apk add openrc
RUN apk add telegraf
RUN rc-update add telegraf
ENV ASPNETCORE_HTTP_PORTS 8080
EXPOSE 8080
