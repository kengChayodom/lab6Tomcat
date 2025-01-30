![image](https://github.com/user-attachments/assets/e6bc903b-1bbb-4d1c-9fa0-2acf3d5ae8fb)# lab6Tomcat

1.sudo apt-get update
Update the package index
![image](https://github.com/user-attachments/assets/4ce4b0d1-5c4e-4624-82c2-0247946e3c53)

2.download java sudo apt-get install openjdk-8-jdk -y
![image](https://github.com/user-attachments/assets/b66a41f0-0115-46b9-8326-e583292e32f6)

3. check java ersion java -version
   ![image](https://github.com/user-attachments/assets/0229b6a0-9f67-44ec-984e-5683bd5607cb)

4.download tomcat wget https://dlcdn.apache.org/tomcat/tomcat-10/v10.1.34/bin/apache-tomcat-10.1.34-fulldocs.tar.gz
![image](https://github.com/user-attachments/assets/fb44b3a4-6760-4477-a2b0-12b6c1977ec2)

5. extract file  tar -xvzf apache-tomcat-10.1.34-fulldocs.tar.gz
![image](https://github.com/user-attachments/assets/5f62016e-aabe-4366-b195-c7d0af49acc9)

6.Move the extracted directory to /opt.  sudo mv apache-tomcat-10.1.34-fulldocs.tar.gz /opt/tomcat
![image](https://github.com/user-attachments/assets/7bf63d43-e02c-4753-ab6d-2a688b9110e7)

7.Grant permissions to the Tomcat directory. sudo chmod -R 755 /opt/tomcat
![image](https://github.com/user-attachments/assets/ad2b1880-605d-4111-be69-2caf3d8f2356)

8.Navigate to the bin directory of Tomcat
![image](https://github.com/user-attachments/assets/7a883ff1-eb1f-4052-8413-c5d6dfc2f429)
