## Steps to Setup

**1. Clone the repository** 

```bash
git clone https://github.com/BodduSatya/SpringBoot-FileUpload.git
```

**2. Specify the file uploads directory**

Open `src/main/resources/application.properties` file and change the property `file.upload-dir` to the path where you want the uploaded files to be stored.

```
file.upload-dir=./uploads
```

**2. Run the app using maven**

```bash
cd spring-boot-file-upload-download
mvn spring-boot:run
```

That's it! The application can be accessed at `http://localhost:8080`.

You may also package the application in the form of a jar and then run the jar file like so -

```bash
mvn clean package
java -jar target/file-demo-0.0.1-SNAPSHOT.jar
```
![image](https://user-images.githubusercontent.com/24984593/145667259-ae150d59-6523-49d4-9a7a-16273b3ada24.png)
![image](https://user-images.githubusercontent.com/24984593/145667282-1bc85e44-cbd2-497c-b08d-c35b83eb3ddf.png)
![image](https://user-images.githubusercontent.com/24984593/145667292-4fbb1abf-39b2-44e3-8937-19d5d4d2df7f.png)
![image](https://user-images.githubusercontent.com/24984593/145667300-18652c8a-402f-4415-98e0-60a9dbf31497.png)
![image](https://user-images.githubusercontent.com/24984593/145667323-1935bc7b-b50e-4850-8159-5a1a470d0d25.png)
![Untitled](https://user-images.githubusercontent.com/24984593/145667539-5c929168-3a7c-415a-ab60-15e26bbc37b3.png)
![image](https://user-images.githubusercontent.com/24984593/145667467-d8ea04a8-f12c-4200-b26d-47a40d385b0d.png)

