### Nodejs as docker utility
Steps on how to use this utility
 - build an image by running this command:
  ```
   docker build -t node_js_util:latest .
  ```
 - go to your project directory
 - run or install nodejs dependencies by using this command
  
 ```
    ##create new reactjs or vuejs project:
    docker run -it --rm -v ./:/app node_js_util:latest create vite@latest . 
 ```
  