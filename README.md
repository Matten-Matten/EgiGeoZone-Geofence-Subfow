![Logo](https://play-lh.googleusercontent.com/Xumisnals5BRF9URTz9cHX2RpDMlQcTjnzvvdj65fYNBQ1us78EnRc5HqA3OelEqMKVu=s80-rw)
# EgiGeoZone Geofence Subflow
`in Nodered`

https://www.egigeozone.de/manual/default.html#Servereinstellungen

---
[-> Beispiel flow](https://github.com/Matten-Matten/EgiGeoZone-Geofence-Subfow/blob/main/bsp_flow.json)

[-> Subflow](https://github.com/Matten-Matten/EgiGeoZone-Geofence-Subfow/blob/main/flow.json)

---

![picture](https://raw.githubusercontent.com/Matten-Matten/EgiGeoZone-Geofence-Subfow/main/pics/empfangen.gif)
![picture](https://raw.githubusercontent.com/Matten-Matten/EgiGeoZone-Geofence-Subfow/main/pics/config.png)

---
![Logo](https://homematic-forum.de/forum/styles/prosilver/theme/images/homematic-logo.png)

Forum: https://homematic-forum.de/forum/viewtopic.php?f=77&t=64273

---

## OUTPUT:

    {
        id:"b1234-0815de-3abc0-8abc-0815ed1dddcf",
        name:"zuHause",
        entry:"1",
        date:"2021-01-05T09:21:27Z",
        latitude:"51.4643171",
        longitude:"8.6991961",
        device:"b1234-0815de-3abc0-8abc-0815ed1dddcf"
    }



---
## INPUT:

Eintrag in EGI Geozone Server bei _URL FHEM Geofancy_ :

http://`mein.dyndns`:`Port`/webhook/geo



- Cloudmatic Redmatic beispiel:

http://`12345`.meine-homematic.de/addons/red/webhook/geo

12345 = eure Cloudmatic ID



- Cloudmatic Nodered beispiel:

http://`12345`.meine-homematic.de:`8001`/webhook/geo

Port 8001 = der Port den ihr in Cloudmatic frei gebt.

http://kb.easy-smarthome.de/CloudMatic_Informationen_-_IP_und_Port_Informationen

---

## Changelog

### 1.0.0 (2021-01-05)
* (Matten-Matten)      `first publication`
