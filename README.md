## Streamlit Cloud Deployment 
You can login to https://mlaita1-7vhm5vwxtrkjarfsmcne9q.streamlit.app to view this web application. Please refresh the page if any error occurs or else some charts don't load... 

## Through Docker 
You can use the below command to pull the Docker image and run it on your local machine: machine

```docker pull ghcr.io/darth-binit/my-streamlit-app:latest```

Please login to your github by using  **docker login ghcr.io**  use your username and PAT(personal access token) and then run the above given pull comand.
oh no wait...!! I just made the package (image) public so no need for authentication Yay...

**Note**: *I have not used docker-compuse yaml file as my streamlit app is a standalone application, requiring only one container hence the docker file is sufficient. Since this app doesn't rely on other containers like database or etc. docker-compose is unnecessary.*

