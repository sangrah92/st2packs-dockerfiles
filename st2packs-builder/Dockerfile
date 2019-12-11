FROM stackstorm/st2:3.0dev

ONBUILD ARG PACKS
ONBUILD RUN docker build --build-arg PACKS="https://PRIVATE-TOKEN:xYAf-6WELzmrhodb_3GY@scm.dimensiondata.com/pratik.khairnar/ntt_vmware.git" -t stackstorms/st2packs:latest .
