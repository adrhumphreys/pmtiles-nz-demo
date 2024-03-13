-48.458352,-195.908203,-32.620870,-178.945313

./pmtiles extract \
 https://build.protomaps.com/20240215.pmtiles \
 nz4.pmtiles \
 --bbox=-164.3,-48.53,179.47,-33.44 \
 --maxzoom=5

./pmtiles extract \
 https://build.protomaps.com/20240215.pmtiles \
 ./mappy/public/nz8.pmtiles \
 --bbox=-164.3022811413,-48.5259267771,179.4717793027,-33.4370910536 \
 --maxzoom=12

// Region file worked better
./pmtiles extract \
 https://build.protomaps.com/20240215.pmtiles \
 ./mappy/public/nz8.pmtiles \
 --region=REGION.geojson \
 --maxzoom=12

// Good one
./pmtiles extract \
 https://build.protomaps.com/20240215.pmtiles \
 ./mappy/public/nz9.pmtiles \
 --bbox=164.3022811413,-48.5259267771,179.4717793027,-33.4370910536 \
 --maxzoom=12

166.509144322, -46.641235447, 178.517093541, -34.4506617165
