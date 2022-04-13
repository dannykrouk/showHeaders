# showHeaders

showHeaders is a page that is designed to allow you to see details about the HTTP headers, client, and server.  It can be useful when troubleshooting reverse proxy issues with ArcGIS Enterprise

To use it with IIS, place the .aspx page in an IIS virtual directory (where aspx pages will execute).  Then, navigate to the page in a browser.

To use it with Tomcat, place the .jsp page in a Tomcat virtual directory (where jsp pages will execute).  Then, navigate to the page in a browser.

Although it is not technically supported, the .jsp page can be used with the OEM'ed Tomcat inside of Portal for ArcGIS or ArcGIS for Server.  With Portal, you may place it next to the arcgisuris.xml page (framework/webapps/rootapp).  Then, you can navigate to it with https://<f.q.d.n>:7443/showHeaders.jsp.  With Server, you may place it in the "arcgis" app (framework/webapps/arcgis).  Then, you can navigate to it with https://f.q.d.n:6443/arcgis/showHeaders.jsp. 
