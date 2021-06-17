# spring-petclinic
ci proccess:

//1. get the repository 

git clone https://github.com/spring-projects/spring-petclinic.git

//2. install java 

sudo apt-get update

sudo apt install openjdk-8-jdk

/3. runnig the program  

cd spring-petclinic

./mvnw package

java -jar target/*.jar

/4. create new repository in github named Tikal_spring-petclinic

/5. set git user configure

git config user.name "bmd738"

git config user.email bmd738@gmail.com

/6. push the repository

git init

git add

git commit -m "adding"

git pull origin main

git push -u -f origin main

/7. creat action 

/In Actions tab choose 'java with maven' workflow

good luck!
