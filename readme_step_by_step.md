# spring-petclinic
ci proccess:
// 1. get the repository 
git clone https://github.com/spring-projects/spring-petclinic.git
// 2. install java 
sudo apt-get update
sudo apt install openjdk-8-jdk
// 3. runnig the program  
cd spring-petclinic
./mvnw package
java -jar target/*.jar
// 4.
