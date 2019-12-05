Step:1
sudo docker-compose -f k_gateway.yml up --build

Step:2
curl localhost:8001 [to check if the kong api is running]

Note:
if you run step 1 and 2,kong api will be runnnig on port 8001,i have tested it,and you will find the screenshots
in the repository itself