# learn_linux_by_doing
1.Emmanuel removed duplicates from satelite-temperature-data.csv
cmd used: sort satelite-temperature-data.csv| uniq > satelite-temperature-data.csv
2.Erica moved file top5-highest-temperatures.csv from root directory to analyzed directory
cmd used: mv top5-highest-temperatures.csv analyzed/
3.Claudia deleted a useless file named test-1 from data directory
cmd used: rm -r test-1
4.Hannah extracted top-5 lowest temperature from data directory to analysed directory
cmd used: sort -t, -k3 satelite_temperature_data.csv| head -n 5 > ../analysed/top-5-lowest-temperature
5.Benigne Renamed files in analyzed to [top-5-] format
cmd used: mv top5-lowest-temperatures.csv top-5-lowest-temperatures.csv
6.Benigne Extracted top 5 highest temperature from Data directory to analyzed directory
cmd used: sort -t, -k -r -n satelite_temperature_data.csv | head -n5 > ../analysed/top-5-lowest-temperature
7.hysbiallah extracted data recorded from Rwanda
cmd used: grep "Rwanda" satelite_temperature_data.csv > country-heat_data.csv
