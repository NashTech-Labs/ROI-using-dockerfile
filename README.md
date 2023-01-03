# ROI-using-dockerfile
In this techhub you can start your roi calculator using dockerfile
1.Flask-Python Framework
2.Python Libs:
    flask=2.2.2
    openpyxl=3.0.10
    pandas=1.5.0
    gspread=5.5.0
    oauth2client=4.1.3
boto3=1.24.82
3.AWS Resource:
    a.ec2-instance
    b.IAM
    e.vpc
# how to run the Project on docker-env

# Clone the source code from github
* build the docker image 
```
docker build -t roi:latest . 
```
* now run command

```
docker run -p 9999:9999 roi:latest

```
* access the ROI using 
```
http://127.0.0.1:9999
```
