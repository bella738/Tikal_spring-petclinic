# spring-petclinic
## ci proccess:

# _get the repository_ 

git clone https://github.com/spring-projects/spring-petclinic.git

# _install java_ 

sudo apt-get update

sudo apt install openjdk-8-jdk

# _runnig the program_  

cd spring-petclinic

./mvnw package

java -jar target/*.jar

# _create new repository in github named Tikal_spring-petclinic_

# _set git user configure_

git config user.name "bmd738"

git config user.email bmd738@gmail.com

# _push the repository_

git init

git add

git commit -m "adding"

git pull origin main

git push -u -f origin main

# _creat action_ 

_In Actions tab choose 'java with maven' workflow_


