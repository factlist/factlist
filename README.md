# Factlist


### What is Factlist
Factlist is a community-based fact checking platform that’s shaped by demand and collaboration. As opposed to our current fact checking ecosystem where the capacity is insufficient and the credibility of organizations is questionable, Factlist holds the power of community above all. By simply reporting a link or a picture to the Factlist community, the user becomes the questioner, the investigator, the fact checker and the ultimate decision maker.

### Community
- You can find [our roadmap](https://trello.com/factlist) publicly on Trello 
- Join our [Slack channel](https://join.slack.com/t/factlist/shared_invite/enQtMzAxNTc2MDgyNDQ4LTJlZDNkMzUwODYwOGE0ZGVhZWMxMmM5MjRhNGNiMDMyMDg2YzAwZWQ0MDQ2Mzg3YTUwN2FlYmFjZTQ3NmE1YjE)

### Getting started

Easiest way to run Factlist is to install `docker-compose` which can be found [here](https://docs.docker.com/compose/install/). 

For the rest you can follow these steps:

```bash
git clone https://github.com/factlist/factlist.git factlist
cd factlist
# Requires docker-compose version >= 1.6
docker-compose up -d
```
Now you are able to access Factlist via port `3000` (e.g. [localhost:3000](http://localhost:3000)) on your host.

### Documentation
TODO

### Tech

- Golang
- React JS
- MySQL

### Contributing
See the contributing [guidelines](CONTRIBUTING.md)

### License
All of the codebases are **MIT licensed** unless otherwise specified.

