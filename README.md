# InkTime-TSC

Design hardware (PCB) pentru un smartwatch minimalist cu display E-Paper, baterie Li-Po si feedback haptic. 

## Functionalitate Hardware
* **Procesare & RF:** Sistemul este controlat de nRF52840. Antena de 2.4GHz are traseu cu impedanta controlata si via stitching pentru izolare.
* **Display (E-Paper):** Comunica prin SPI. Dispune de un circuit Boost (SMPS) integrat pe placa pentru generarea tensiunilor de actionare a panoului.
* **Alimentare:** Incarcare baterie prin USB-C. Traseele de curent mare sunt scurte si dimensionate corespunzator.
* **Interfata Utilizator:** 3 butoane mecanice (cu pull-up intern pe MCU) si un motor de vibratii comutat printr-un MOSFET (semnal PWM).

## 5. Design Log & Routing
* **Stackup:** PCB in 4 straturi. Stratul Bottom este dedicat planului de masa (GND) continuu pentru a asigura o cale de intoarcere optima a curentilor.
* **Placement & EMI:** Componentele de putere ale sursei in comutatie (E-Paper) sunt grupate strans pentru a minimiza bucla de zgomot.