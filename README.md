# Nixie Clock with Single Tube
Big thanks to <a href="https://www.daliborfarny.com/">Dalibor Farny</a> for sharing desing files for his <a href="https://www.daliborfarny.com/product/blub-clock/">Blub Clock</a> case.

Time can be set using my <a href="https://github.com/StavJi/Nixie_Clock_SW">app</a> or via AT commands interface. To list all possible commands use AT$HELP? and you will get:

1. $HELP:Available commands:
2. AT$HELP
3. AT$DAY - (starts Monday) 1 to 7
4. AT$DATE -  1 to 31
5. AT$MONTH -  1 to 12
6. AT$YEAR -  2000 to 2099
7. AT$SEC -  0 to 59
8. AT$MIN -  0 to 59
9. AT$HOUR -  0 to 23
10. AT$DATE_TIME
11. AT$NIGHT_MODE -  0 to 1

<p float="left">
  <img  src="https://github.com/StavJi/Nixie_Clock_SingleTube/blob/main/Photo/clock_1.JPG"  width=40%/>
  <img  src="https://github.com/StavJi/Nixie_Clock_SingleTube/blob/main/Photo/clock_2.JPG"  width=40%/>
</p>

## TODO
- Add gerbers
- Add TOP and BOT assembly
- Add bluetooth support
- Use Zephyr OS
- Create mobile APP
