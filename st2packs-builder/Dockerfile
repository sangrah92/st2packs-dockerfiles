FROM stackstorm/st2:3.0dev

ONBUILD ARG PACKS
ONBUILD RUN docker build --build-arg PACKS="https://github.com/sangrah92/pack_actions.git" -t ishan2411/st2packs:latest .
