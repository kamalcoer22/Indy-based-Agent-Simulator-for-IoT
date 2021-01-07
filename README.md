# Run indy based reference agent Simulation for IoT Devices.

## Quick start Instructions

Run this repository by running through [`docker-compose`](https://docs.docker.com/compose/).

```
docker-compose build
docker-compose up
```

### Access the agents in a web browser:

To open an agent instance, in a web browser navigate to:
* `localhost:3000` for Tesla    (Username: tesla, Password: 123)
* `localhost:3001` for Requester-Vehicle    (Username: requester-vehicle, Password: 123)
* `localhost:3002` for Front-Vehicle    (Username: front-vehicle, Password: 123)

If you’re using Docker Machine on a Mac or Windows, use docker-machine ip MACHINE_VM to get the IP address of your Docker host. Then, open http://MACHINE_VM_IP:3000 or 3001 or 3002 in a browser.
