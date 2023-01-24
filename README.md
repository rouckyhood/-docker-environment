<p align="center">
  <a href="#"><img src="https://readme-typing-svg.herokuapp.com?center=true&vCenter=true&lines=Docker+environment;"></a>
</p>
<p align="center">
    Deploy a docker environment with Portainer and Traefik easily !
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
