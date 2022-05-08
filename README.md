# sampling data

download file
```
wget https://github.com/labusiam/dataset/raw/main/weather_data.xlsx
```

ubah menjadi CSV
```
in2csv weather_data.xlsx --sheet "weather_2014">weather_2014.csv

in2csv weather_data.xlsx --sheet "weather_2015">weather_2015.csv
```

gabungkan csv
```
csvstack weather_2014.csv weather_2015.csv > weather.csv

```

hapus file
```
rm weather_data.xlsx
```