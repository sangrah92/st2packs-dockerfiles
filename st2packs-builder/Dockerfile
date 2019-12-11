FROM stackstorm/st2:3.0dev

ONBUILD ARG PACKS
ONBUILD RUN docker build --build-arg PACKS="https://PRIVATE-TOKEN:FWHZ_59xns-N4gF-BwaP@scm.dimensiondata.com/vnext/StackStorm-Packs/ntt_docker.git" -t stackstorms/st2packs:latest .



