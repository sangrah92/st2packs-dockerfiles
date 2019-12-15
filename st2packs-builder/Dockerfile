FROM stackstorm/st2:3.0dev

ONBUILD ARG PACKS
ONBUILD RUN docker build --build-arg PACKS="https://PRIVATE-TOKEN:MmKTAxwMd-ssFj23mbYz@scm.dimensiondata.com/vnext/StackStorm-Packs/ntt_ivr.git https://PRIVATE-TOKEN:MmKTAxwMd-ssFj23mbYz@scm.dimensiondata.com/vnext/StackStorm-Packs/ntt_emr.git https://PRIVATE-TOKEN:MmKTAxwMd-ssFj23mbYz@scm.dimensiondata.com/vnext/StackStorm-Packs/ntt_insite_msen.git" -t stackstorm/custompack7:latest .

