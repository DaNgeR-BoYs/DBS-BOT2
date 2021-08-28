FROM fusuf/whatsasena:latest

RUN git clone http://github.com/DaNgeR-BoYs/DBS-BOT2 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/DaNgeR-BoYs/DBS-BOT2

CMD ["node", "bot.js"]
