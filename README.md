Make use of the limited (basic) stuff Nest Home has to offer by google auth.

Since i don't have a nest developer account i cannot tell the difference between them, i can only guess based on the repository of the original integration.

Many thanks for RedDragon who initiated this and had it working in the first place, i only modified the code trying to get more info out of google-nest. Still working on that, i'll keep you posted when there is any progress.

Can anyone please try the Nest Camera, i don't have one.

Validated test shows it will work with more than one thermostat in your account, it uses the info from the Nest site.
Therefor it should work with the camera also, but i want confirmation for that.
It should also work with Nest E-learning thermostat.

All it does for now is change the heat, turn on/off the heat en turn on/off eco-mode.

![png](https://github.com/Puch-tdi/Nest-for-Hass-Google-auth/blob/master/nest-wheel.png)

![png](https://github.com/Puch-tdi/Nest-for-Hass-Google-auth/blob/master/nest-card.png)

![png](https://github.com/Puch-tdi/Nest-for-Hass-Google-auth/blob/master/card-therm.png)


<pre>
# Example configuration.yaml entry
nesthome:
  issue_token: "https://accounts.google.com/o/oauth2/iframerpc....."
  cookie: "OCAK=......"
  region: eu

climate:
  - platform: nesthome
    scan_interval: 10

camera:
  - platform: nesthome

sensor:
  - platform: nesthome
</pre>
