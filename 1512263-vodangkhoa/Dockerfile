#Depending on the operating system of the host machines(s) that will build or run the containers, the image specified in the FROM statement may need to be changed.
#For more information, please see https://aka.ms/containercompat

FROM microsoft/dotnet:2.1-aspnetcore-runtime AS base
WORKDIR /app
EXPOSE 60042
EXPOSE 44311

CMD ASPNETCORE_URLS=http://*:$PORT dotnet 1512263-vodangkhoa.dll