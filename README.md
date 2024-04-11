<!-- ABOUT THE PROJECT -->
## About best403unlocker

I had so many challenge in choosing the best DNS sni proxy server thats fits my internet service provider so I develope an script that tests the speed of the DNSs so I won't waste my time on finding the best DNS server  

      
![output](https://github.com/ArmanTaheriGhaleTaki/speed-test-dns/assets/88885103/d83c954e-5f3c-434e-ae4b-f119d69a4220)    



<!-- GETTING STARTED -->
## Getting Started
you can use this script with **docker** 

## docker
you only need **docker** installed and you can edit variables in  [.env](https://github.com/ArmanTaheriGhaleTaki/best403unlocker/blob/main/.env) for your needs.
 

  ```sh
  git clone https://github.com/ArmanTaheriGhaleTaki/best403unlocker/ && cd best403unlocker && docker build -t speedtestdns . && docker run --env-file .env speedtestdns
  ```    
or you can use built image uploaded in dockerhub      
  *for that case you need to use [.env](https://github.com/ArmanTaheriGhaleTaki/best403unlocker/blob/main/.env) at run time*
  ```sh
  wget -c https://raw.githubusercontent.com/ArmanTaheriGhaleTaki/best403unlocker/main/.env && docker run --env-file .env armantaherighaletaki/best403unlocker 
  ```   

<!-- CONTACT -->
## Contact

my social media - [@armondy🙄](https://twitter.com/taherighaletaki) - armantahery1381@gmail.com

Project Link:  [best403unlocker](https://github.com/ArmanTaheriGhaleTaki/best403unlocker) 




