# NMEA-parser
gets data from NMEA source and parses GLL and VTG messages.

GLL - Geographic Latitude and Longitude

  $GPGLL,4916.45,N,12311.12,W,225444,A,*1D

Where:

  GLL          Geographic position, Latitude and Longitude

  4916.46,N    Latitude 49 deg. 16.45 min. North

  12311.12,W   Longitude 123 deg. 11.12 min. West

  225444       Fix taken at 22:54:44 UTC

  A            Data Active or V (void)

  *iD          checksum data


VTG - Velocity made good.

  $GPVTG,054.7,T,034.4,M,005.5,N,010.2,K*48

where:

  VTG          Track made good and ground speed

  054.7,T      True track made good (degrees)

  034.4,M      Magnetic track made good

  005.5,N      Ground speed, knots

  010.2,K      Ground speed, Kilometers per hour

  *48          Checksum
