# docker-startup-loki-plugin
fix when server starting but docker plugin loki don't start


sudo cp startup-docker-loki.service /etc/systemd/system/
sudo chmod 664 /etc/systemd/system/startup-docker-loki.service
sudo systemctl daemon-reload
sudo systemctl enable startup-docker-loki.service