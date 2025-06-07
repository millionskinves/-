FROM node:lts-buster
RUN git clone https://github.com/millionsknives/𝑫𝑨𝑹𝑲 𝑸𝑼𝑬𝑬𝑵 Λⅈ🌹/root/kingtech
WORKDIR /root/your github name
RUN npm install && npm install -g pm2 || yarn install --network-concurrency 1
COPY . .
EXPOSE 9090
CMD ["npm", "start"]
