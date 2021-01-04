Hello,

Github repository link: https://github.com/pkowalicki/nd9990-c3-microservices-exercises/tree/master
Default branch: master
Branches dev and feature/feed-and-user are left and were used for development.

Microservices are in the following directories
project/udagram-api-feed
project/udagram-api-user
project/udagram-proxy
project/udagram-frontend

(project/udagram-api left for reference as monolith app).

Travis build config is in the root of the repository (.travis.yml).

Screenshots are stored in project/screenshots and are groupd per topic.

API requests were made to proxy pod from within the EC2 node. You can verify the proxy pod IP in proxy pod details screenshots and the requests to feed and user services (through proxy) in the appropriate screens as well. Logs include both proxy and appropriate backend service pod logs.

Let me know in case of any questions.

Thanks,
Przemek
przemekkowalicki@gmail.com