# Strapi application

A quick description of your strapi application
# strapio-poc

# Connect to Mongo Databse
mongodb+srv://vivo:vivo@cluster0.yfuk7.mongodb.net/vivo?retryWrites=true&w=majority

# User to login on Strapio
User:
leonanmattos@gmail.com

Password:
Vivo@123

# API

# API - Get plans
curl --request GET \
  --url http://localhost:1337/plans

# API - Create Plans
  curl --request POST \
  --url http://localhost:1337/plans \
  --header 'Content-Type: application/json' \
  --data '{
	"code": "1234",
	"description": "teste 123",
	"size": 10,
	"active": true
}'

