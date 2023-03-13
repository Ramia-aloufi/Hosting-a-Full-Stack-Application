# Hosting a Full Stack Application
 provided by Udacity to be hosted into AWS with Pipeline using CircleCI. 
#Getting Started
 ### Clone the repo
git clone https://github.com/Ramia-aloufi/Hosting-a-Full-Stack-Application.git
### go to project folder
cd Hosting-a-Full-Stack-Application

### install dependenscies
npm run frontend:install
npm run backend:install

###  Enviromental Variables Set up

 POSTGRES_HOST=""
 POSTGRES_USERNAME=""
 POSTGRES_PASSWORD=""
 POSTGRES_DB=""
 DB_PORT=5432



PORT = 
URL=""

AWS_REGION=""
AWS_PROFILE=""
AWS_BUCKET=""

JWT_SECRET=""

### build
npm run frontend:build
npm run backend:build

### start
npm run frontend:start
npm run backend:start


## cli 
### uploud to s3
- aws s3 cp --recursive  ./www s3://[s3name]/
### uploud to eb
- new eb =eb init, eb create --single --keyname [keypair] --instance-types t2.medium
- exist eb = npm run backend:deploy
### check RDS connect
psql -h [endpoint] -U [user] [db]





