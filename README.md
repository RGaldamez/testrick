# testrick
testing deploy with meteorjs


Using MongoLab + meteorjs + heroku to deploy a js app online

Steps:

1. Make a repository in github
2. clone it 

3. Make db in mlab
4. make user admin in mlab db

5.make herokuapp
6.change next settings:
  add:
     MONGO_URL: with mongo url db from mlab
     ROOT_URL:with app domain name
     
7. Add buildpack: (current buildpack) https://github.com/kevinseguin/heroku-buildpack-meteor.git

8. Deploy.
