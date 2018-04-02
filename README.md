# docker-jep-java-template







### usage

```
docker run --rm --name jep5 -it -v /root/java:/data dockerhub/docker-jep-java-template -cp custom.jar  Main

```





you may custom you python module by change Docker

```
RUN pip3 install  numpy 
RUN pip3 install  pymc3 
RUN pip3 install six
RUN pip3 install urllib3
RUN pip3 install pandas
RUN pip3 install requests
RUN pip3 install urllib3 	
RUN pip3 install six
RUN pip3 install lxml
RUN pip3 install JPype1==0.6.2
RUN pip3 install jep
RUN pip3 install baostock
RUN pip3 install bs4
RUN pip3 install tushare
RUN pip3 install numpy
```

