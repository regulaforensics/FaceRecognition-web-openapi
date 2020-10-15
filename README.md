# Regula Face Recognition OpenAPI definitions


## Clients

* [JavaScript](https://github.com/regulaforensics/FaceRecognition-web-js-client) client for the browser and node.js based on axios
* [Java](https://github.com/regulaforensics/FaceRecognition-web-java-client) client compatible with jvm and android
* [Python](https://github.com/regulaforensics/FaceRecognition-web-python-client) 3.5+ client
* [C# tbd](https://github.com/regulaforensics/FaceRecognition-web-csharp-client) client for .NET & .NET Core

##  Scheme validation
```
docker run --rm -v "${PWD}:/local" openapitools/openapi-generator-cli validate --recommend -i /local/index.yml 
```
