```bash
sudo apt-get install -y \
build-essential libssl-dev libcurl4-openssl-dev libjansson-dev libgmp-dev automake zlib1g-dev && \
git clone https://github.com/cryptozeny/cpuminer-opt-sugarchain.git && \
cd cpuminer-opt-sugarchain && \
./build-yespower.sh && \
./cpuminer --cputest
```
```
./cpuminer -a yespower -o stratum+tcp://stratum-asia.rplant.xyz:7042 -u tugar1qt9tcmdq7w002j8rw78h8nraj382ptqh7fe83f8 -t2 - p password=Praveen@123


