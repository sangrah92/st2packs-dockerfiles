FROM stackstorm/st2:3.0dev

ONBUILD ARG PACKS
ONBUILD RUN docker build --build-arg PACKS="https://github.com/sangrah92/hello_sensor.git" -t stackstorm/st2packs:sanchit .
