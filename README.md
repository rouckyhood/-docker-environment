<p align="center">
  <a href="#"><img src="https://readme-typing-svg.herokuapp.com?center=true&vCenter=true&lines=Docker+environment;"></a>
</p>
<p align="center">
    Deploy a docker environment with Portainer and Traefik easily !
</p>
<p align="center">
    <a href="https://github.com/PAPAMICA/docker-environment#deploy-on-debian--ubuntu"><img src="https://img.shields.io/badge/Deploy_on_Debian-%2341454A.svg?style=for-the-badge&logo=target&logoColor=white"> </a>
    <a href="https://github.com/PAPAMICA/docker-environment#deploy-on-infomaniak-public-cloud-or-openstack"><img src="https://img.shields.io/badge/Deploy_on_Infomaniak_Public_cloud_(openstack)-%2341454A.svg?style=for-the-badge&logo=target&logoColor=white"> </a>
    <br /><br />
    <a href="https://www.docker.com/"><img src="https://img.shields.io/badge/docker-%232496ED.svg?style=for-the-badge&logo=docker&logoColor=white"> </a>
    <a href="https://www.portainer.io/"><img src="https://img.shields.io/badge/portainer-%2313BEF9.svg?style=for-the-badge&logo=portainer&logoColor=white"> </a>
    <a href="https://traefik.io/traefik/"><img src="https://img.shields.io/badge/traefik_proxy-%231F93B1.svg?style=for-the-badge&logo=traefikmesh&logoColor=white"> </a>
    <a href="https://www.debian.org/index.fr.html"><img src="https://img.shields.io/badge/Debian-%23A81D33.svg?style=for-the-badge&logo=debian&logoColor=white"> </a>
    <a href="https://www.infomaniak.com/fr/hebergement/public-cloud"><img src="https://img.shields.io/badge/Openstack-%23ED1944.svg?style=for-the-badge&logo=openstack&logoColor=white"> </a>
    <br />
</p>

## Deploy on Debian / Ubuntu
### Export variables
```bash
export EMAIL=<your_email>
export NDD=<your_domain>
export PASSWORD_TRAEFIK=<your_password>
```

### Use script
```bash
bash -c "$(curl -s https://github.com/rouckyhood/docker-environment/blob/main/install-docker-environment.sh)"
```

### Redirect URL to IP
You need to redirect this URL to server IP:
- traefik.ndd
- portainer.ndd
