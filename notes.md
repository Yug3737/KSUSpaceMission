# APRS Notes - Yug Patel

## Meduim Website
 - Automatic Packet Reporting System
 - Uses Local Radio Frequency network
 - Can be used for Annoucements, Bulletins, Messages, Alerts, Weather and map elements.
 - No internet needed but can connect to APRS-IS to ennhance capbilities.
- For faster movements, beacon faster.

## John Beadles PPT
- Configuration Info Needed
    - SSID
    - Lattitude and Longitude
    - Unproto Address
    - Beacon Comment
    - Beacon Rate
    - Status Text
    - Status Rate
1. SSID
    - Uniquely identifies you.
2. Lattitude and Longitude
    - Latt. goes from 0(equator) - 90(at poles), N/S
    - Longt. from 0 -180, going east from Greenwich England.
3. Unpronto Address Commands
    - lkfdhfkjf
4. Beacon Comment
    - Should be short.
    - How Short?
5. Status Message
    - Can put our CallSign here, if do so need to transmit atleat every 30 mins.
6.

### APRS Hardware
1. Digipeaters - is a station that retransmits the packets that it hears. Each area has a few.
2. Tracker - is an APRS station that is capable of transmitting a packet containing containing location info. Usually small and portable for moving b/w vehicles.
3. Fixed Station - transmits packets but is stationary.  Can be used to monitor other stations or to transmit local info. objects.
4. Internet Gateway relays packets from radio to the internet and vice versa. Maybe combined with Fixed Station or Digipeater. Requires Computer and Internet connection.
5. Mobile Station - usually a tracker semi-permanently fixed in a vehicle. Can have a computer for display.
6. Passive Stations- only listen to APRS packets.

### TNCs 
- Terminal Node Controller is a packet modem.
- One end connects to a radio and other to computer/GPS reciever.
- AGWPE Windows Software can be used.

### GPS Recievers
- Any GPS receiever used for APRS must have data connection and must output NMEA format data.
- External Power vs. Internal Power.
- Consumer grade GPS receivers would be accurate upto 30m.

## Questions to Learn
### What is the APRS-IS ?
- 

### How is data transmitted over different frequencies?
- 

### What is Amateur Radio
- Ham radio can run without cellphone or internet connection.
- Crucial for emergency services.

### What is the AX.25 protocol?
- Amateur X.25 - data link layer protocol

### Basic Working of the GPS
- 3 parts: satellites, ground stations and receivers (you).
-  We are supposed to know where satellites are due to the constant signals they send.
- Ground stations make sure they are actually where we think they are.
- Receiver constantly listen for satellite signals
- Once yo receive signals from 4 or more satellites, they know exactly where you are.
- Each satellite makes 2 rotations daily. And they are arranged such that at any time 4 are visible in the sky.
- The concept of trilateration is used to determine the receiver's location. For 2D trilateration, 3 points of reference are enough (see: https://electronics.howstuffworks.com/gadgets/travel/gps.htm)
- 3d can do with 3 too, but for precise altitude info, use 4 satellites.
- 
### What is Telemetry?
- The process of gathering performance data of a product and relaying it to a remote location for monitoring and analysis.
- 

## Resources
- 