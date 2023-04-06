FROM nodered/node-red:latest-minimal
#USER root
#RUN apk add -U --no-cache alpine-sdk python python3
#USER node-red
RUN npm install --no-optional node-red-contrib-prometheus-exporter \
        node-red-node-openweathermap \
        node-red-dashboard
#RUN npm audit fix --force
