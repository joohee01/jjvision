## 전주 비전대 project
# DHT senser install
```
git clone https://github.com/adafruit_Python_DHT.git
cd Adafruit_Python_DHT
sudo python setup.py install
```
- run
```
python AdafruitDHT .py 11 4
## InfluxDB Installation < Influx = 파일을 생성 (공간 확보)>
# 1.Repository의 GPG key를 더하기
```
curl -sL https:/repos.influxdata.com/influxdb.key | sudo apt-key add -
```
# 2.Repository를 더하기
```
echo "deb https://repos.infulxdata.com/debin stretch stable" | sudo tee /etc/pat/sources.list.d/influxdb.list
```

