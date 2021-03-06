![CodaLab logo](codalab/apps/web/static/img/codalab-logo-fullcolor-positive.png) [![Circle CI](https://circleci.com/gh/codalab/codalab-competitions.svg?style=shield)](https://circleci.com/gh/codalab/codalab-competitions)



## What is CodaLab?

CodaLab is an open-source web-based platform that enables researchers, developers, and data scientists to collaborate, with the goal of advancing research fields where machine learning and advanced computation is used.  CodaLab helps to solve many common problems in the arena of data-oriented research through its online community where people can share worksheets and participate in competitions.

To see Codalab Competition's in action, visit [competitions.codalab.org](https://competitions.codalab.org/).

## Documentation

- [CodaLab Wiki](https://github.com/codalab/codalab/wiki)

## Community

The CodaLab community forum is hosted on Google Groups.
- [CodaLab Competitions Google Groups Forum](https://groups.google.com/forum/#!forum/codalab-competitions)


## Quick installation (for Linux!)

_To participate in competitions, or even organize your own competition, **you don't need to install anything**, you just need to sign in an instance of the platform (e.g. [this one](https://competitions.codalab.org/)). 
If you wish to configure your own instance of CodaLab competitions, here are the instructions:_

Install docker and add your user to the docker group, if you haven't already

```
$ wget -qO- https://get.docker.com/ | sh
$ sudo usermod -aG docker $USER
```

Clone this repo and get the default environment setup
```
$ git clone https://github.com/codalab/codalab-competitions
$ cd codalab-competitions
$ cp .env_sample .env
$ pip install docker-compose
$ docker-compose up -d
```

Now you should be able to access http://localhost/

**More details on how to configure your own instance:**
- [Configure Codalab from scratch](https://github.com/codalab/codalab-competitions/wiki/Setup-Local-Competitions#user-content-get-the-source-code)
- [Set up data storage](https://github.com/codalab/codalab-competitions/wiki/Storage)
