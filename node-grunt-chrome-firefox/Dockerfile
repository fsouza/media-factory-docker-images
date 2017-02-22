FROM bwilhelm/node-grunt-chrome-firefox:0.1.2
RUN  curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | apt-key add -
RUN  echo "deb http://dl.yarnpkg.com/debian/ stable main" | tee /etc/apt/sources.list.d/yarn.list
RUN  apt-get update && apt-get install -y yarn && rm -rf /var/cache/apt
