FROM naskio/n8n-python:latest-debian
FROM mcr.microsoft.com/playwright:v1.34.0-jammy

RUN cd /usr/lib/node_modules/n8n && npm install n8n-nodes-changed
RUN cd /usr/lib/node_modules/n8n && npm install n8n-nodes-updates
RUN cd /usr/lib/node_modules/n8n && npm install n8n-nodes-influxdb
RUN apt install rclone nano htop chrony -y
