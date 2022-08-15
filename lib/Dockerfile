FROM quay.io/shefin/alexa:md
RUN git clone https://github.com/shefin-x3/wa-bot-md.git /5hefin/Alexa/
WORKDIR /5hefin/Alexa
RUN yarn install --network-concurrency 1
CMD ["node", "index.js"]
