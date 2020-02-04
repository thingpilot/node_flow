## Nodeflow Release Notes

**v0.4.0** *30/01/2019*
- Added the telemetry formatter for CBOR conversions 
- Changed the error handling in case of eeprom error

**v0.3.1** *13/12/2019*
- Remove Git submodules folders for included libraries
**v0.3.0** *13/12/2019*
- NodeFlow handles most of the communication in the background without much effort needed from the embed programmer.
- start() drives all the application. It handles the different modem and configuration.
- add_record<DataType>(data) for adding variable type records to eeprom
- increment(i) Increment with a value i.
- read_increment(&increment_value) Read current increment value.
        
**v0.1.0-v0.2.0** *09/2019*
- Empty NodeFlow class
- Handles sleeping times/ eeprom driver/ lorawan/ nb-iot communication