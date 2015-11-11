
+ https://azure.microsoft.com/en-us/documentation/articles/cache-dotnet-how-to-use-azure-redis-cache/ will be our main guide for creating Azure Redis Cache on Azure.

We will be using the "C#/Cloud/QuickStart/Data Services/Azure Redis Cache" under <b>Azure QuickStart templates</b> in your Visual Studio
( If you don't have Azure QuickStart templates installed, download and install  https://code.msdn.microsoft.com/Azure-Redis-Cache-daad9d96?SRC=VSIDE 
or 
use online search in Visuail Studio samples to look for  "Azure Redis Cache (Visual C#)" and install. Follow the instructions in "Project_Readme.html")

This sample demonstrates the following scenarios:
##1.Connecting to a Redis cache using the StackExchange Redis client ##
2.Storing and retrieving primitive values 
3.Storing and retrieving .NET objects 
4.Retrieving and/or adding cache entries 
5.Removing items from the cache 
6.Storing items with an expiration time 

Running this sample
1.Use the Azure Portal to create a new Redis Cache 
2.Edit app.config and replace the redisCacheName and redisCachePassword with values provided from the portal 
3.Run the sample 

More information
+ Cache Documentation http://azure.microsoft.com/en-us/documentation/services/cache/
+ Create a cache in Azure Redis Cache http://aka.ms/CreateAzureRedisCache
+ Configure .NET cache clients for Azure Redis Cache http://aka.ms/ConfigureAzureRedisCacheClients
+ Windows Azure Web Sites: How Application Strings and Connection Strings Work http://azure.microsoft.com/blog/2013/07/17/windows-azure-web-sites-how-application-strings-and-connection-strings-work/

+ Extra : Use 3rd party web client to see your Redis Cache content : https://redsmin.com
