# Hello world app for Azure Service Fabric

Instead of following all the granular steps in https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-get-started-containers-linux, this project allows you to quickly deploy/install and uninstall a "hello world" app.

```plain
git clone https://github.com/drnic/helloworld-azureservicefabric
cd helloworld-azureservicefabric/mycontainer

sfctl cluster select --endpoint http://EXPLORER:19080/
./install.sh
```

Your application will be running at port 4000 on the same host: http://EXPLORER:4000/
