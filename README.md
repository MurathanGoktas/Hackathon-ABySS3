# Hackathon-ABySS3

Paired Sentinel Sequences Extraction Class for ABySS3-Hackathon on 6th of May.

#Install
```
https://github.com/MurathanGoktas/Hackathon-ABySS3.git
cd Hackathon-ABySS3/src
g++ SentinelBloomFilterConstructor.cpp -o indexlr -I../b/ -std=c++11 -pthread
```

#Run
```
indexlr -k K -w W -r counting_bf_path [-a min_mx] [-b max_mx] [--id] [--bx] [--pos] [--seq]
```
*Example:*
```
indexlr -k16 -w32 -a8 -b32 -r ./counting_bf.bf  -o sentinels_k16w32a8b32.txt ./celegans_ONT-40x.chr3.fa
```
