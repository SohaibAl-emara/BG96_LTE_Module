# Manual Installation
```
git clone https://github.com/SohaibAl-emara/BG96_LTE_Module.git
```

## Functions

`sendDataCommOnce` - Function for sending data to module

`sendATCommOnce` - Function for sending at comamand to module

`sendDataComm` - Function for sending data to BG96_AT

`sendATComm` - Function for sending at command to BG96_AT

`saveConfigurations` - Function for save configurations that be done in current session

`getIMEI` - Function for getting IMEI number

`getFirmwareInfo` - Function for getting firmware info

`getHardwareInfo` - Function for getting hardware info

`setGSMBand` - Function for setting GSM Band

`setCATM1Band` - Function for setting Cat.M1 Band

`setNBIoTBand` - Function for setting NB-IoT Band

`getBandConfiguration` - Function for getting current band settings

`setScambleConf` - Function for setting scramble feature configuration 

`setMode` - Function for setting running mode

`getIPAddress` - Function for getting self.ip_address

`setIPAddress` - Function for setting self.ip_address

`getDomainName` - Function for getting self.domain_name

`setDomainName` - Function for setting domain name

`getPort` - Function for getting port

`setPort` - Function for setting port

`getTimeout` - Function for getting timout in ms

`setTimeout` - Function for setting timeout in ms  

#### Network Service Functions

`getSignalQuality` - Fuction for getting signal quality

`getQueryNetworkInfo` - Function for getting network information

`connectToOperator` - Function for connecting to base station of operator

#### SMS Functions

`sendSMS` - Function for sending SMS

#### GNSS Functions

`turnOnGNSS` - Function for turning on GNSS

`turnOffGNSS` - Function for turning of GNSS

`getLatitude` - Function for getting latitude

`getLongitude` - Function for getting longitude

`getSpeedMph` - Function for getting speed in MPH	

`getSpeedKph` - Function for getting speed in KPH

`getFixedLocation` - Function for getting fixed location 

#### TCP & UDP Protocols Functions

`activateContext` - Function for configurating and activating TCP context 

`deactivateContext` - Function for deactivating TCP context 

`connectToServerTCP` - Function for connecting to server via TCP (just buffer access mode is supported for now)

`sendDataTCP` - Fuction for sending data via tcp (just buffer access mode is supported for now)

`sendDataIFTTT` - Function for sending data to IFTTT

`sendDataThingspeak` - Function for sending data to Thingspeak

`startUDPService` - Function for connecting to server via UDP

`sendDataUDP` - Fuction for sending data via udp

