# nttdataent-cricket-info
This repo contains the code for consuming the rest endpoint for live cricket updates

Below are the essential 5 end points/ services the application should have 
1. Get the current score
    http://localhost:8081/getscore
2. Get current over
    http://localhost:8082/get-over
3. Get the total score for a batsman using id
    http://localhost:8083/get-score/id
4. Get total score card including each batsman contribution
    http://localhost:8084/get-score/all
5. Get total wickets taken by each bowler
    http://localhost:8085/get-wickets/all