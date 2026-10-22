# How to deploy from scratch

1. install docker and git
2. clone this repository (`git@github.com:janrosellcaba/ion-vps.git`)
3. execute `docker compose up -d` inside repository

---

4. create pat (personal access token) in github
5. execute `docker login ghcr.io -u <user> -p <token>` inside repository

---

(for each application)

6. clone repository (wherever you want)
7. execute `docker compose pull` inside repository
8. execute `docker compose up -d` inside repository
