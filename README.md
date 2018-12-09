# operator-sdk-jetbrain-goland-debugging
To be albe to run and debug your operator locally not by using `operator-sdk up local` command 
but straight from ( in my case ) JetBrain's GoLang IDE, do the following 
1. Export env var `KUBERNETES_CONFIG=/path/to/your/kube/config/file`
2. Export env var `WATCH_NAMESPACE=default` (or any other namespace you like to wath) 
3. Run main.go file from `cmd` dir 


![alt text](https://raw.githubusercontent.com/Dimss/operator-sdk-jetbrain-goland-debugging/master/debug-operator-with-jetbrain-goland.png)
