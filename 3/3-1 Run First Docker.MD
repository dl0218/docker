# Run First Docker
     1 Start Up a container
     2 Stop and Clean Up a container
     3 Docker extension of VS Code
--------------------------------------------------------  
#   Status Check:
        service docker status
--------------------------------------------------------         
#   Start Up:
        docker image pull jetty:9.4.31-jre8 
        docker container run jetty:9.4.31-jre8 
        docker container ps
        docker  exec -it {containerID} /bin/bash
        curl localhost:8080
--------------------------------------------------------        
#   Stop and Clean Up:
        docker container stop {containerID}
        docker container ls -a
        docker container rm {containerID}
        docker rmi jetty:9.4.31-jre8
--------------------------------------------------------        
#   Docker extension from VS Code:
    If you install Docker extension in your local:
        A) Uninstall Docker extension from VS Code. 
        B) Close all VS Code windows.
        D) Start VS Code again. Use 'Remote-SSH: Connect to Host..' to connect to remote machine.
        E) Open extension marketplace and install Docker extension on the remote machine.        
