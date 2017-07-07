# docker-frr
The docker image for [frr](https://github.com/FRRouting/frr).

## Usage
* docker run --name frr --rm satoshifujimoto/docker-frr bgpd -u root -g root &
* docker exec -it frr telnet localhost bgpd
  * The password is default ("zebra").
