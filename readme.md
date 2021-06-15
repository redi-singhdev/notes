
## to dos 

in my deriviatives i need same day of week compare of first of month compare too not just t-1



# tech bites:

## xml diff

http://www.inf.unibz.it/~nutt/Teaching/XMLDM1112/XMLDM1112Coursework/WangEtAl-ICDE2003.pdf


## data inguestion theory
https://www.xplenty.com/blog/data-ingestion-layer-framework-pipeline/




---
---




# architecture:

## ingestion tools
Uber open src, which is inspired by Linkedin gobblin

main article : https://eng.uber.com/marmaray-hadoop-ingestion-open-source/
code and some doc: https://github.com/uber/marmaray
goblin: https://github.com/apache/gobblin
design
![image](https://user-images.githubusercontent.com/1906471/121627180-e3996580-ca44-11eb-9c08-e753502f38d7.png)





## data pipeline

https://www.youtube.com/watch?v=VtzvF17ysbc

## big data arcitecture

![image](https://user-images.githubusercontent.com/1906471/121799345-927ea280-cbf9-11eb-9579-85bf7b20a1d3.png)


## netflix

https://www.youtube.com/watch?v=nMyuCdqzpZc


![image](https://user-images.githubusercontent.com/1906471/121797926-43cd0a80-cbf1-11eb-8087-d26fd45a8df2.png)


### pull vs push/notify 
![image](https://user-images.githubusercontent.com/1906471/121798078-36fce680-cbf2-11eb-9dd2-6ce73d879cf8.png)


![image](https://user-images.githubusercontent.com/1906471/121798091-4aa84d00-cbf2-11eb-96f0-37f2e5648b11.png)




### z-score
![image](https://user-images.githubusercontent.com/1906471/121738436-35370400-cac8-11eb-869d-afe8d07f9841.png)

https://www.statisticshowto.com/probability-and-statistics/z-score/

https://www.youtube.com/watch?v=16vAjsnazEM&feature=emb_imp_woyt





## linkedin talk on gobblin

https://www.youtube.com/watch?v=BQ7aONetKl4

### grayed out  in following are non gobblin specific, reset is gobblin specific 

![image](https://user-images.githubusercontent.com/1906471/121797852-de791980-cbf0-11eb-95df-20d7078a1d04.png)


![image](https://user-images.githubusercontent.com/1906471/121798311-87287880-cbf3-11eb-8768-bd86e4479e5e.png)


![image](https://user-images.githubusercontent.com/1906471/121798321-9efffc80-cbf3-11eb-8314-1d7c47661574.png)


![image](https://user-images.githubusercontent.com/1906471/121798334-ade6af00-cbf3-11eb-8b84-29b928a3c627.png)


![image](https://user-images.githubusercontent.com/1906471/121798360-cf479b00-cbf3-11eb-968d-4198d51d5855.png)


![image](https://user-images.githubusercontent.com/1906471/121798399-0f0e8280-cbf4-11eb-863b-b1d738edb157.png)


![image](https://user-images.githubusercontent.com/1906471/121798408-2188bc00-cbf4-11eb-83bf-656e10ed3fdc.png)

### one spec multiple env

![image](https://user-images.githubusercontent.com/1906471/121798873-be4c5900-cbf6-11eb-8481-03762138a50c.png)




## gobblin architecture

https://gobblin.apache.org/docs/Gobblin-Architecture/

![image](https://user-images.githubusercontent.com/1906471/121798680-b4762600-cbf5-11eb-875a-6f24c787aa86.png)

![image](https://user-images.githubusercontent.com/1906471/121798704-d2438b00-cbf5-11eb-8d1f-1e44454b2590.png)



## tolerance engine using ML


https://www.ustream.tv/channel/JUMjvCF2ucj


![image](https://user-images.githubusercontent.com/1906471/121798586-331e9380-cbf5-11eb-9f53-e7a3cdd46dfa.png)








# code notes


## MS Architecture

https://docs.microsoft.com/en-us/dotnet/architecture/modern-web-apps-azure/architectural-principles#explicit-dependencies


##  dotnet core code middleware

https://github.com/dotnet/aspnetcore/blob/52eff90fbcfca39b7eb58baad597df6a99a542b0/src/Http/Http.Abstractions/src/IMiddlewareFactory.cs

https://github.com/dotnet/aspnetcore/blob/52eff90fbcfca39b7eb58baad597df6a99a542b0/src/Http/Http.Abstractions/src/IMiddleware.cs


## gobblin task

https://github.com/apache/gobblin/blob/096562c634c3c8dac63fddd607b5132d9363522f/gobblin-runtime/src/main/java/org/apache/gobblin/runtime/task/TaskIFace.java#L29


## azure ingest data --

https://docs.microsoft.com/en-us/azure/data-explorer/net-sdk-ingest-data


## azure ingest documentation on github

https://github.com/MicrosoftDocs/dataexplorer-docs/blob/a7c4c051a1c956aa8a2cfa511bf590a7f373243e/data-explorer/kusto/api/netfx/kusto-ingest-client-reference.md

on web:  https://docs.microsoft.com/en-us/azure/data-explorer/kusto/api/netfx/kusto-ingest-client-reference

vid tutorial : https://www.youtube.com/watch?v=upU_Desx4XM


![image](https://user-images.githubusercontent.com/1906471/121837587-fc538680-cca3-11eb-855e-e006a4471b78.png)



![image](https://user-images.githubusercontent.com/1906471/121837665-2b69f800-cca4-11eb-8fe0-d6d26b307195.png)



![image](https://user-images.githubusercontent.com/1906471/121837802-88fe4480-cca4-11eb-993b-ee31fbd109ab.png)




# main documentation:

doc entry point : https://docs.microsoft.com/en-us/azure/data-explorer/ingest-sample-data

col map doc  : https://docs.microsoft.com/en-us/azure/data-explorer/kusto/management/mappings

advance col map: https://docs.microsoft.com/en-us/azure/data-explorer/net-sdk-ingest-data

ingest client: https://docs.microsoft.com/en-us/azure/data-explorer/kusto/api/netfx/kusto-ingest-client-reference

ingest code sample : https://docs.microsoft.com/en-us/azure/data-explorer/kusto/api/netfx/kusto-ingest-client-examples

typescript sample code: https://www.npmjs.com/package/azure-kusto-ingest



github code ref? : https://github.com/search?q=IKustoIngestClient&type=code

more: https://github.com/MicrosoftDocs/dataexplorer-docs/blob/a7c4c051a1c956aa8a2cfa511bf590a7f373243e/data-explorer/kusto/api/netfx/kusto-ingest-client-reference.md


kusto supporte files : https://docs.microsoft.com/en-us/azure/data-explorer/ingestion-supported-formats






### extra

https://engineering.linkedin.com/blog/2021/fastingest-low-latency-gobblin



# main main main --- all sdk interface definations

https://docs.microsoft.com/en-us/azure/data-explorer/kusto/api/netfx/kusto-ingest-client-reference



