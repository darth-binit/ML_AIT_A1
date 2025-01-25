## Streamlit Cloud Deployment 
You can login to ```https://mlaita1-7vhm5vwxtrkjarfsmcne9q.streamlit.app``` to view this web application. Please refresh the page if any error occurs or some charts don't load...

## Through Docker 
Also you pull the docker image as i have pushed the image through github central repository. You can use the below command to pull out the image and run it in your local machine
```docker pull ghcr.io/darth-binit/my-streamlit-app:latest```

#Note: *I have not used docker-compuse yaml file as my streamlit app is a standalone application, requiring only one container hence the docker file is sufficient. Since this app doesn't rely on other containers like database or etc. docker-compose is unnecessary.*

