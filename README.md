Installation

```
cd && cd /home/`whoami`/gn_module_monitoring/contrib/

wget https://github.com/LPO-SEP/GNMonitoring-Pelobates-CMR/archive/main.zip
unzip main.zip
rm main.zip
mv ~/GNMonitoring-Pelobates-CMR-main ~/pelobates_cmr
ln -s ~/gn_module_monitoring/contrib/pelobates_cmr ~/geonature/backend/media/monitorings/peloabtes_cmr

source ~/geonature/backend/venv/bin/activate
geonature monitorings install pelobates_cmr
```
