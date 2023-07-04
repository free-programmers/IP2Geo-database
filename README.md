# IP2Geo-database
ip2geo.ir database


this repo contains:
    
    - List of all DNS Servers in the world
    - List of all countries in the world
    - List of the IPv4 range of all countries
    - List of the IPv6 range of all countries

  
total IPV4 range: 3,141,352

total IPV6 range: 3,141,352

total country info: 250

total country DNS-Server: 250



# info-helper:

# IPV4-IPV6 :

0.0 a record example:
```json

   {
  "country-code": "KW",
  "start-range": "281473851349248",
  "end-range": "281473851349503",
  "public-key": "8a22d77e-3ef5-4b73-b9dc-0b3af31aaa39",
  "country-name": "Kuwait",
  "state-name": "Al Jahra'",
  "city-name": "Al Jahra'",
  "lat": "29.337478",
  "long": "47.658204",
  "zip-code": "00020",
  "timezone": "+03:00"
}

```

- Country Code: KW (The two-letter country code representing Kuwait)
- Start Range: 281473851349248 (The starting range of the IP address in integer format)
- End Range: 281473851349503 (The ending range of the IP address in integer format)
- Public Key: 8a22d77e-3ef5-4b73-b9dc-0b3af31aaa39 (A unique identifier for the record)
- Country Name: Kuwait (The name of the country)
- State Name: Al Jahra' (The name of the state or province where the IP address belongs)
- City Name: Al Jahra' (The name of the city where the IP address belongs)
- Latitude: 29.337478 (The latitude coordinate of the country)
- Longitude: 47.658204 (The longitude coordinate of the country)
- Zip Code: 00020 (The postal code of the city where the IP address belongs)
- Timezone: +03:00 (The time zone of the country)



---


# DNS SERVER

0.0 a record example:

```json
{
  "IP": "185.161.112.33",
  "NAME": "fw1.parvazsys.ir.",
  "AS_NUMBER": 50057,
  "AS_ORG": "Parvaz System Information Technology Company (Ltd)",
  "CITY": "",
  "VERSION": "9.11.3-1ubuntu1.15-Ubuntu",
  "ERROR": "",
  "DNSSEC": false,
  "RELIABILITY": 0.8578199052132701,
  "CHECKED_AT": "2021-05-03T22:25:03.43704Z",
  "CREATED_AT": "2021-03-04T05:42:19.283962Z",
  "PUBLIC-KEY": "3b3c1b34-8b05-4e02-b646-acfd6156b79d",
  "COUNTRY_CODE": "IR",
  "X-PROVIDE": "https://ip2geo.ir"
}
```

- IP: DNS server IPV4(185.161.112.33)
- Name: fw1.parvazsys.ir.
- AS Number: 50057
- AS Organization: Parvaz System Information Technology Company (Ltd)
- City: Not specified
- Version: 9.11.3-1ubuntu1.15-Ubuntu
- Error: No error reported
- DNSSEC: False (DNS Security Extensions not enabled)
- Reliability: between 0 to 1 (0.8578199052132701)
- Checked At: 2021-05-03T22:25:03.43704Z utc time that this record checked
- Created At: 2021-03-04T05:42:19.283962Z utc time that this record Created 
- Public Key: 3b3c1b34-8b05-4e02-b646-acfd6156b79d  (A unique identifier for the record)
- Country Code: IR (The two-letter country code representing Iran)
- X-Provide: https://ip2geo.ir (web site that provide this data)

