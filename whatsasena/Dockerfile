FROM fusuf/whatsasena:latest

RUN git clone https://github.https://github.com/Vyshakappu/Sophia/root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
