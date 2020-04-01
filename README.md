Make use of the limited (basic) stuff Nest Home has to offer by google auth.

Since i don't have a nest developer account i cannot tell you the difference between them, i can only guess based on the repository of the original integration.

Many thanks for RedDragon who initiated this in the first place, i only modified the code trying to get more info out of google-nest.
Still working on that, i'll keep you posted here when there are changes.
Can anyone please try the Nest Camera, i don't have one.
Validated test show it will work with more than one thermostat in your account, it scrapes the info from the Nest site.
Therefor it should work with the camera also, but i want confirmation for that.
It should also work with Nest E-learning thermostat.

![png](https://github.com/Puch-tdi/Nest-for-Hass-Google-auth/blob/master/nest-wheel.png)

![png](https://github.com/Puch-tdi/Nest-for-Hass-Google-auth/blob/master/nest-card.png)

![png](https://github.com/Puch-tdi/Nest-for-Hass-Google-auth/blob/master/card-therm.png)

Code
<pre>
# Dutch Smart Meter Reader USB
sensor:
  - platform: dsmr
    port: /dev/ttyUSB0
    dsmr_version: 5
</pre>
