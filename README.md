# Final Project - Please Read

Create a single page react app with microservice back end.

aws link: http://3.236.214.178:3000/

To run: (we did not get docker fully running)
* In docker_files
  * docker swarm init
  * docker stack deploy -c docker-compose.yml group2   
* In back_end
  * npm i
  * node ApiServer.js
  * node Gateway.js
  * node ImageProcessor.js
  * node WebSocketServer.js
* In front_end
  * npm i
  * npm start

Things to know:

* Login as admin is email: admin@admin.com, password: admin
* Can login to tester@email.com password: password, to test out two users if needed.
* Image upload only works with PNG files (forgot jpg existed)
* Make sure to click upload on image first before click submit listing
* Inquiries and Listings populate instantly locally, may Need to refresh to see inquiries through the link posted.
