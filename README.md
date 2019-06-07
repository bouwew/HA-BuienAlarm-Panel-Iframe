I found a nice way to add the visuals from the BuienAlarm website: www.buienalarm.nl as a Panel Iframe to Home Assistant.

1) Download the file buienalarm.html to the directory config/www
2) Add the following to configuration.yaml:
```
panel_iframe:
  regen:
    title: Regen-voorspelling
    icon: mdi:weather-pouring
    url: /local/buienalarm.html
```
Result:
![Screenshot](HA_buienalarm.png)
When this is done, you will see the default welcome-page. Select your city and the prediction will be shown!
