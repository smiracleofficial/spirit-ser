FROM SPlRlT-YT/raganork:test

RUN git clone https://github.com/SPlRlT-YT/spirit-ser/ /skl/raganork
WORKDIR /skl/raganork 
ENV TZ = Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "raganork.js"]
