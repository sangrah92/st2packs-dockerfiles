FROM stackstorm/st2:3.0dev

ONBUILD ARG PACKS
ONBUILD RUN docker build --build-arg PACKS="https://PRIVATE-TOKEN:aEJFW8JRRZuaPt66ZYrt@scm.dimensiondata.com/vnext/StackStorm-Packs/ntt_network_cisco.git https://PRIVATE-TOKEN:aEJFW8JRRZuaPt66ZYrt@scm.dimensiondata.com/vnext/StackStorm-Packs/ntt_network.git" -t stackstorm/custompack2:latest .
  



