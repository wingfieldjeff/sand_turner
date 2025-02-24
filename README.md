![](https://github.com/wingfieldjeff/sand_turner/blob/main/images/sand_turner.jpg)
# Supplies
-  1x Arduino Nano (Or any Arduino compatible microcontroller)
-  4x [608 (8mm x 22mm x 7mm) bearings](https://www.amazon.com/%EF%BC%BB10-Pack%EF%BC%BD-608-Ball-Bearings/dp/B08XVFSZTF?crid=18RL5GU4B9PTV&dib=eyJ2IjoiMSJ9.cDCFSSZO25t7JZQqLsFiI4dI0ch9in_r_OramH59qAMDkM7iz472v4pCSNwHxceKOlWN6lrhS-S3-c7zDlWrzALVI8nVhPOd6Fa7yleE2Vdofb463KyvANPwt1lPdTnG6uYLQ-TWrz4YTMHC9Cw7WXNmF9wLj0HDfWaJCWHdM_h3HKbwu2uW6kkAq0ciH7CSyEwkodNRCZ4lFlgkRi-Qe2x5uM8qYUpilbw3_zqmPFk.7qmof2PuQ6S6J2oQgvPp_-Io_poqOTDvoRdeU5JWmds&dib_tag=se&keywords=bearings&qid=1740413160&sprefix=bearingf%2Caps%2C151&sr=8-11&th=1)
-  1x  [28BYJ-48 Stepper Motor](https://www.amazon.com/ELEGOO-28BYJ-48-ULN2003-Stepper-Arduino/dp/B01CP18J4A?crid=2ELA3TY34RIJK&dib=eyJ2IjoiMSJ9.6bwZgnYtcN_NH0492YUVI0YuwQASAQpiRezWZMpccTs6E90iUkInCfoSVWh9slRMTybzi_XU6aC-7NHUmJrIhy7P4vslPeScOM04TV8BCAoRL4q_keTYwpyv_RV1yoCVIjH4EqDFLPiv1qkgfSJsvyFHVajqPetA9HQChSZqDDBaCl9LtIX6Rzv7nynXy1wRR0Fc4DeAqEjz8CbCV3WWdFYQu1t5gec_ZYzX06L9kcU.bmW1JHCv_KybTVJHVBBSQ9g1H2hp9jqPmkZiaO5DmBg&dib_tag=se&keywords=stepper+motor&qid=1740411662&sprefix=stepper+%2Caps%2C166&sr=8-4)
-  1x  [ULN2003 Stepper Driver](https://www.amazon.com/ELEGOO-28BYJ-48-ULN2003-Stepper-Arduino/dp/B01CP18J4A?crid=2ELA3TY34RIJK&dib=eyJ2IjoiMSJ9.6bwZgnYtcN_NH0492YUVI0YuwQASAQpiRezWZMpccTs6E90iUkInCfoSVWh9slRMTybzi_XU6aC-7NHUmJrIhy7P4vslPeScOM04TV8BCAoRL4q_keTYwpyv_RV1yoCVIjH4EqDFLPiv1qkgfSJsvyFHVajqPetA9HQChSZqDDBaCl9LtIX6Rzv7nynXy1wRR0Fc4DeAqEjz8CbCV3WWdFYQu1t5gec_ZYzX06L9kcU.bmW1JHCv_KybTVJHVBBSQ9g1H2hp9jqPmkZiaO5DmBg&dib_tag=se&keywords=stepper+motor&qid=1740411662&sprefix=stepper+%2Caps%2C166&sr=8-4)
-  1x [USBc Female breakout](https://www.amazon.com/Cermant-Breakout-Serial-Connector-Converter/dp/B0CB2VFJ54?crid=HJYWZ321WYWR&dib=eyJ2IjoiMSJ9.V0VvXGB7bPvgM5eOvKUKrYrQ3DMt2lLP7Pa90M8P7QJI9kfU41Muc_pVcJa6PD33tKB-VqXPe3JEiv7mBBosScBQvw0dK7O_nELsT5-RWEH9yMfB2Tlk-f_SlEb563x3Y8Pefhap1BKGiSsEoczuQD_4voyyVRv7lTVhB0DvycwEOw9bnQwHjtlSDciHNPBY6JutgLA-3Y6kUFqyXXaGagM_rVnADJKejgcCQZRmvD8.6PyCiYcuWt2o-6cAf5jU_VWyrftBI-6JRuuEgae9zQM&dib_tag=se&keywords=usb+breakout+board&qid=1740411875&sprefix=usbc+break%2Caps%2C159&sr=8-13)
-  2x M3x12 bolts
-  22 AWG wire
-  CA Glue or m2x5 self tapping screws
-  2x [Silicone rings](https://www.amazon.com/dp/B06XC41JJW?ref_=ppx_hzsearch_conn_dt_b_fed_asin_title_4&th=1) (optional)
-  2x Wago 3 wire connectors (optional) 
-  5v LED strip (optional)
# Printed Parts
- 1x [*Shell Front.stl*](https://github.com/wingfieldjeff/sand_turner/blob/main/cad/Shell%20Front.stl)
- 1x [*Shell Back.stl*](https://github.com/wingfieldjeff/sand_turner/blob/main/cad/Shell%20Back.stl)
- 2x [*pin.stl*](https://github.com/wingfieldjeff/sand_turner/blob/main/cad/pin.stl)
- 2x [*roller.stl*](https://github.com/wingfieldjeff/sand_turner/blob/main/cad/roller.stl)
# Assembly 
1. Print the above parts.
2. Place the bearing in the slots in the front shell. They should be a friction fit and this is easiest to do with the shell horizontal.
3. If using the silicone rings, place them on the rollers
4. Place the rollers between the bearings and pass the pins through.
5. On the driven roller (the side with motor mounting holes), peal back the silicone ring (if used) and place either CA Glue or a self tapping m2 screw in the locking hole to secure it to the pin.
6. Flash [sand_disk.ino](https://github.com/wingfieldjeff/sand_turner/blob/main/sand_disk.ino) to your arduino.
7. Wire as shown here:![](https://github.com/wingfieldjeff/sand_turner/blob/main/images/wiring.jpg) diagram here (found): ![](https://newbiely.com/images/tutorial/arduino-nano-uln2003-28byj-48-stepper-wiring-diagram.jpg)
8. Attach the stepper motor with the m3 bolts. They are simply strewed into the plastic. m3 nuts can be used as spacers but are not strictly necessary .
9. (optionally) solder your LEDs to ground and D6 on the arduino.
10. Attach the usbc 5v breakout to the back shell with double sided tape or hot glue
11. Close the shell halves. I left plenty of room for even very messy wiring.
     
