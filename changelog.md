### petits changements dans le projet

  les config wifi doit etre dans la micro sd:
    {
        "ssid" : "Mon_Super_Nom",
        "pswd" : "Mon_Super_MDP"
    }

### petits changements hardware

- [x] adafruit leds [link](https://www.adafruit.com/product/1138?length=4)
- [x] adafruit esp32 (wifi) [link](https://www.adafruit.com/product/3405)
- [x] adafruit SD->micro sd (8 GB SDHC)[link](https://www.adafruit.com/product/1294)
- [ ] microship ~PIC32MX340F512H~ [link](https://www.microchip.com/wwwproducts/en/PIC32MX340F512H)
      pour le moment il a ete remplace par le esp32.
      pour une question de simplicité car le esp32 inclut le chip wifi par defaut.

## le Software 
   Actuellement en beta 1.2, pas de feautures en partuculier.
- [ ] ajouter une API pour rendre le projet modulaire 
  
## partie physique 
  le principe a ete base sur le projet [Lixie](https://hackaday.io/project/18633-lixie-an-led-alternative-to-the-nixie-tube)

> le time out do projet est fixe pour le 10/08/2019  
