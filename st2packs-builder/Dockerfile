FROM stackstorm/st2:3.0dev

ONBUILD ARG PACKS
ONBUILD RUN docker build --build-arg PACKS="https://PRIVATE-TOKEN:cqTqq9q12WDZJLkLztGU@scm.dimensiondata.com/vnext/StackStorm-Packs/ntt_itsm.git" -t stackstorm/custompack9:latest .

