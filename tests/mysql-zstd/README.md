# Test Description

test mysql zstd compression

## Source
 mysql \
--password=root \
--host=172.18.0.3 \
--port=3306 \
 --compression-algorithms=zstd  \
 --user root \
 --database sentinel-flow \
 --compress \
 --ssl-mode=DISABLED
