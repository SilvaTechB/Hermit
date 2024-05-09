FROM quay.io/hermit/hermit-ser:latest

RUN git clone https://github.com/SilvaTechB/Hermit /root/Hermit
WORKDIR /root/hermit-md/
RUN yarn install --network-concurrency 1
CMD ["node", "index.js", "--max_old_space_size=2560"]
