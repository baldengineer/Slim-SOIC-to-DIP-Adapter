![Rendered view of a 0.3 inch DIP adapter](https://github.com/baldengineer/Slim-SOIC-to-DIP-Adapter/blob/main/images/SOIC-to-DIP%20Adapters%20render%20in%20OSH%20Park%20colors.png)
## Slim SOIC-to-DIP Adapter
Original width adapter for drop-in DIP logic chips

The idea is to be able to replace 7400-series logic chips when through-hole options are not available. This adapter is designed with the original 0.3" width. This design choice creates a few challenges.

First, standard 0.1" / 2.54mm pins do not work. The current approach is to use a machined pin with smaller diameter.

Second, there is a high chance of shorting pins on the SOIC when soldering the through-hole pins.

Third, they are very smol.

## Logic families
Changing between LS, HC, ACT, etc is not a straightforward process. This [TI Application note-scla013d](https://www.ti.com/lit/ug/scla013d/scla013d.pdf?ts=1604776112365) is an excellent guide to what 7000-series logic chip families are and how they connect to each other.

## Current Status
Initial board were fabricated and parts ordered, but they have not been built or tested yet.

## Bald Engineer on Twitch
This board was designed, built, and tested live with the Bald Engineer. Check out his electronics live stream at: [https://twitch.tv/baldengineer](https://twitch.tv/baldengineer).

### Made with KiCad
