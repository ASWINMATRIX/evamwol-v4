FROM fusuf/whatsasena:latest

RUN git clone https://github.com/ASWINMATRIX/evamwol-v4 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --ignore-engines
RUN git clone https://github.com/ASWINMATRIX/media

CMD ["node", "bot.js"]
