FROM ymazieres/dotnet:compile

CMD ["sh", "/script/webappScript.sh"]

COPY /script/webappScript.sh /script/webappScript.sh
COPY /src/appweb/ /script/

RUN chmod +x /script/webappScript.sh

EXPOSE 5000

ENV ASPNETCORE_URLS http://+:5000
