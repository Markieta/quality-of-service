# quality-of-service
Quality of Service daemon to monitor private network traffic and toggle download clients.

Ensure Docker is enabled on boot and started:

```
sudo systemctl enable docker.service
sudo systemctl start docker.service
```
Install, enable, and run qos:

```
sudo ./install
sudo systemctl enable qos.service
sudo systemctl start qos.service
```
