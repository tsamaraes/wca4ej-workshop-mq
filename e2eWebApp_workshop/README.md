
# watsonx Code Assistant General Code Demo
An end-to-end full stack web app demo. The user fixes a bug in the Java backend. Once the backend passes all tests, then the user uses WCA to generate a front end in HTML, JS, and CSS. 

## Demo documents:
- [Video](https://ibm.seismic.com/app?ContentId=e60211c5-cf0b-4fde-98b1-c722c5194999#/doccenter/f6bc8873-d580-4ee8-a903-c4e0d3a7eee9/doc/%252Fdd85c941b1-5f54-2314-ce72-b98c4c0974c2%252FdfOTRiYmU4NTQtNWY4NC03Y2QyLWZjYWUtOGIxYmFmZjkyZThk%252CPT0%253D%252CRGVtbw%253D%253D%252Flf35353ae8-aa0b-4130-82cc-81bf3814e31e//?mode=view&parentPath=sessionStorage)
- [Script](https://ibm.box.com/s/052e6gy9rrxi3s9j3empyp2zzbto8fef)
- [Instructions](https://ibm.box.com/s/qhbvk0lz4kje6d641ei51z76ipsql7t0)
- [Owner Contact](https://ibm.enterprise.slack.com/user/@U03GGPKCRBN)


## Set Up Guide
Ensure that the Java version you use in the backend folder is Java 11. If is not, install Java 11 and set it as the current version. 

#### How to use and install Java 11 (mac):
1. cd backend
2. brew install openjdk@11
3. brew link --force --overwrite openjdk@11
4. export JAVA_HOME=$(/usr/libexec/java_home -v 11)

#### How to test the backend:
1. cd backend
2. ./gradlew test

#### How to run the backend server:
1. cd backend
2. ./gradlew bootRun

#### How to run the frontend server:
1. cd frontend
2. npm install -g http-server
3. http-server .
4. Launch available server (for me is http://127.0.0.1:8081)
5. After each change, clear browser cache and reload page


## Source
This was based off of the [open source Article spring boot repo](https://github.com/gothinkster/spring-boot-realworld-example-app).
