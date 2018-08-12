# SmarterLights
weather + time + location + ???? based smart lighting 

# Smart Devices
* Wemo Switch
* motion sensors???
* raspberry pi 0

# Lights:
* living room
* bed1
* bed2

# Scenarios:
* no one home at any time -> TURN OFF ALL
* someone in home, day, light -> DON'T TURN ON
* someone in home, day, dark -> TURN ON IN ROOM
* first person arrives, day, dark -> TURN ON LIVING ROOM

* someone in home, night, -> TURN ON IN ROOM
* person arrives, night -> TURN ON LIVING ROOM


# Overrides:
* Permanent light state (per room) until reset, either manually or in the morning
* commands
  * "LIGHTS ON"
  * "LIGHTS OFF"
  * "RESET"
