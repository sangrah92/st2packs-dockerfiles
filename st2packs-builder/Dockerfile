FROM stackstorm/st2:3.0dev

ONBUILD ARG PACKS
ONBUILD RUN docker build --build-arg PACKS="https://PRIVATE-TOKEN:PJRdDTTWs7hA_pW8CUC9@scm.dimensiondata.com/vnext/StackStorm-Packs/ntt_voice_cisco.git https://PRIVATE-TOKEN:PJRdDTTWs7hA_pW8CUC9@scm.dimensiondata.com/vnext/StackStorm-Packs/ntt_vnext_sample_pack.git https://PRIVATE-TOKEN:PJRdDTTWs7hA_pW8CUC9@scm.dimensiondata.com/vnext/StackStorm-Packs/ntt_unix.git" -t stackstorm/custompack5:latest .

