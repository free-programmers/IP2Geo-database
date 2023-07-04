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



---


# DNS SERVER


0.0 a example record:


``` json
{
  "NAME": {
    "common": "United States",
    "official": "United States of America",
    "nativeName": {
      "eng": {
        "official": "United States of America",
        "common": "United States"
      }
    }
  },
  "TLD": [".us"],
  "CCA2": "US",
  "CCN3": "840",
  "CCA3": "USA",
  "CIOC": "USA",
  "INDEPENDENT": true,
  "STATUS": "officially-assigned",
  "UNMEMBER": true,
  "CURRENCIES": { "USD": { "name": "United States dollar", "symbol": "$" } },
  "IDD": {
    "root": "+1",
    "suffixes": [
      "201",
      "202",
      "203",
      "205",
      "206",
      "207",
      "208",
      "209",
      "210",
      "212",
      "213",
      "214",
      "215",
      "216",
      "217",
      "218",
      "219",
      "220",
      "224",
      "225",
      "227",
      "228",
      "229",
      "231",
      "234",
      "239",
      "240",
      "248",
      "251",
      "252",
      "253",
      "254",
      "256",
      "260",
      "262",
      "267",
      "269",
      "270",
      "272",
      "274",
      "276",
      "281",
      "283",
      "301",
      "302",
      "303",
      "304",
      "305",
      "307",
      "308",
      "309",
      "310",
      "312",
      "313",
      "314",
      "315",
      "316",
      "317",
      "318",
      "319",
      "320",
      "321",
      "323",
      "325",
      "327",
      "330",
      "331",
      "334",
      "336",
      "337",
      "339",
      "346",
      "347",
      "351",
      "352",
      "360",
      "361",
      "364",
      "380",
      "385",
      "386",
      "401",
      "402",
      "404",
      "405",
      "406",
      "407",
      "408",
      "409",
      "410",
      "412",
      "413",
      "414",
      "415",
      "417",
      "419",
      "423",
      "424",
      "425",
      "430",
      "432",
      "434",
      "435",
      "440",
      "442",
      "443",
      "447",
      "458",
      "463",
      "464",
      "469",
      "470",
      "475",
      "478",
      "479",
      "480",
      "484",
      "501",
      "502",
      "503",
      "504",
      "505",
      "507",
      "508",
      "509",
      "510",
      "512",
      "513",
      "515",
      "516",
      "517",
      "518",
      "520",
      "530",
      "531",
      "534",
      "539",
      "540",
      "541",
      "551",
      "559",
      "561",
      "562",
      "563",
      "564",
      "567",
      "570",
      "571",
      "573",
      "574",
      "575",
      "580",
      "585",
      "586",
      "601",
      "602",
      "603",
      "605",
      "606",
      "607",
      "608",
      "609",
      "610",
      "612",
      "614",
      "615",
      "616",
      "617",
      "618",
      "619",
      "620",
      "623",
      "626",
      "628",
      "629",
      "630",
      "631",
      "636",
      "641",
      "646",
      "650",
      "651",
      "657",
      "660",
      "661",
      "662",
      "667",
      "669",
      "678",
      "681",
      "682",
      "701",
      "702",
      "703",
      "704",
      "706",
      "707",
      "708",
      "712",
      "713",
      "714",
      "715",
      "716",
      "717",
      "718",
      "719",
      "720",
      "724",
      "725",
      "727",
      "730",
      "731",
      "732",
      "734",
      "737",
      "740",
      "743",
      "747",
      "754",
      "757",
      "760",
      "762",
      "763",
      "765",
      "769",
      "770",
      "772",
      "773",
      "774",
      "775",
      "779",
      "781",
      "785",
      "786",
      "801",
      "802",
      "803",
      "804",
      "805",
      "806",
      "808",
      "810",
      "812",
      "813",
      "814",
      "815",
      "816",
      "817",
      "818",
      "828",
      "830",
      "831",
      "832",
      "843",
      "845",
      "847",
      "848",
      "850",
      "854",
      "856",
      "857",
      "858",
      "859",
      "860",
      "862",
      "863",
      "864",
      "865",
      "870",
      "872",
      "878",
      "901",
      "903",
      "904",
      "906",
      "907",
      "908",
      "909",
      "910",
      "912",
      "913",
      "914",
      "915",
      "916",
      "917",
      "918",
      "919",
      "920",
      "925",
      "928",
      "929",
      "930",
      "931",
      "934",
      "936",
      "937",
      "938",
      "940",
      "941",
      "947",
      "949",
      "951",
      "952",
      "954",
      "956",
      "959",
      "970",
      "971",
      "972",
      "973",
      "975",
      "978",
      "979",
      "980",
      "984",
      "985",
      "989"
    ]
  },
  "CAPITAL": ["Washington, D.C."],
  "ALTSPELLINGS": ["US", "USA", "United States of America"],
  "REGION": "Americas",
  "SUBREGION": "North America",
  "LANGUAGES": { "eng": "English" },
  "TRANSLATIONS": {
    "ara": {
      "official": "\u0627\u0644\u0648\u0644\u0627\u064a\u0627\u062a \u0627\u0644\u0645\u062a\u062d\u062f\u0629 \u0627\u0644\u0627\u0645\u0631\u064a\u0643\u064a\u0629",
      "common": "\u0627\u0644\u0648\u0644\u0627\u064a\u0627\u062a \u0627\u0644\u0645\u062a\u062d\u062f\u0629"
    },
    "bre": {
      "official": "Stado\u00f9-Unanet Amerika",
      "common": "Stado\u00f9-Unanet"
    },
    "ces": {
      "official": "Spojen\u00e9 st\u00e1ty americk\u00e9",
      "common": "Spojen\u00e9 st\u00e1ty"
    },
    "cym": {
      "official": "United States of America",
      "common": "United States"
    },
    "deu": {
      "official": "Vereinigte Staaten von Amerika",
      "common": "Vereinigte Staaten"
    },
    "est": {
      "official": "Ameerika \u00dchendriigid",
      "common": "Ameerika \u00dchendriigid"
    },
    "fin": { "official": "Amerikan yhdysvallat", "common": "Yhdysvallat" },
    "fra": {
      "official": "Les \u00e9tats-unis d'Am\u00e9rique",
      "common": "\u00c9tats-Unis"
    },
    "hrv": {
      "official": "Sjedinjene Dr\u017eave Amerike",
      "common": "Sjedinjene Ameri\u010dke Dr\u017eave"
    },
    "hun": {
      "official": "Amerikai Egyes\u00fclt \u00c1llamok",
      "common": "Amerikai Egyes\u00fclt \u00c1llamok"
    },
    "ita": {
      "official": "Stati Uniti d'America",
      "common": "Stati Uniti d'America"
    },
    "jpn": {
      "official": "\u30a2\u30e1\u30ea\u30ab\u5408\u8846\u56fd",
      "common": "\u30a2\u30e1\u30ea\u30ab\u5408\u8846\u56fd"
    },
    "kor": {
      "official": "\uc544\uba54\ub9ac\uce74 \ud569\uc911\uad6d",
      "common": "\ubbf8\uad6d"
    },
    "nld": {
      "official": "Verenigde Staten van Amerika",
      "common": "Verenigde Staten"
    },
    "per": {
      "official": "\u0627\u06cc\u0627\u0644\u0627\u062a \u0645\u062a\u062d\u062f\u0647 \u0622\u0645\u0631\u06cc\u06a9\u0627",
      "common": "\u0627\u06cc\u0627\u0644\u0627\u062a \u0645\u062a\u062d\u062f\u0647 \u0622\u0645\u0631\u06cc\u06a9\u0627"
    },
    "pol": {
      "official": "Stany Zjednoczone Ameryki",
      "common": "Stany Zjednoczone"
    },
    "por": {
      "official": "Estados Unidos da Am\u00e9rica",
      "common": "Estados Unidos"
    },
    "rus": {
      "official": "\u0421\u043e\u0435\u0434\u0438\u043d\u0435\u043d\u043d\u044b\u0435 \u0428\u0442\u0430\u0442\u044b \u0410\u043c\u0435\u0440\u0438\u043a\u0438",
      "common": "\u0421\u043e\u0435\u0434\u0438\u043d\u0451\u043d\u043d\u044b\u0435 \u0428\u0442\u0430\u0442\u044b \u0410\u043c\u0435\u0440\u0438\u043a\u0438"
    },
    "slk": {
      "official": "Spojen\u00e9 \u0161t\u00e1ty Americk\u00e9",
      "common": "Spojen\u00e9 \u0161t\u00e1ty americk\u00e9"
    },
    "spa": {
      "official": "Estados Unidos de Am\u00e9rica",
      "common": "Estados Unidos"
    },
    "srp": {
      "official": "\u0421\u0458\u0435\u0434\u0438\u045a\u0435\u043d\u0435 \u0410\u043c\u0435\u0440\u0438\u0447\u043a\u0435 \u0414\u0440\u0436\u0430\u0432\u0435",
      "common": "\u0421\u0458\u0435\u0434\u0438\u045a\u0435\u043d\u0435 \u0410\u043c\u0435\u0440\u0438\u0447\u043a\u0435 \u0414\u0440\u0436\u0430\u0432\u0435"
    },
    "swe": { "official": "Amerikas f\u00f6renta stater", "common": "USA" },
    "tur": {
      "official": "Amerika Birle\u015fik Devletleri",
      "common": "Amerika Birle\u015fik Devletleri"
    },
    "urd": {
      "official": "\u0631\u06cc\u0627\u0633\u062a\u06c1\u0627\u0626\u06d2 \u0645\u062a\u062d\u062f\u06c1 \u0627\u0645\u0631\u06cc\u06a9\u0627",
      "common": "\u0631\u06cc\u0627\u0633\u062a\u06c1\u0627\u0626\u06d2 \u0645\u062a\u062d\u062f\u06c1"
    },
    "zho": {
      "official": "\u7f8e\u5229\u575a\u5408\u4f17\u56fd",
      "common": "\u7f8e\u56fd"
    }
  },
  "LATLNG": [38.0, -97.0],
  "LANDLOCKED": false,
  "BORDERS": ["CAN", "MEX"],
  "AREA": 9372610.0,
  "DEMONYMS": {
    "eng": { "f": "American", "m": "American" },
    "fra": { "f": "Am\u00e9ricaine", "m": "Am\u00e9ricain" }
  },
  "FLAG": "\ud83c\uddfa\ud83c\uddf8",
  "MAPS": {
    "googleMaps": "https://goo.gl/maps/e8M246zY4BSjkjAv6",
    "openStreetMaps": "https://www.openstreetmap.org/relation/148838#map=2/20.6/-85.8"
  },
  "POPULATION": 329484123,
  "GINI": { "2018": 41.4 },
  "FIFA": "USA",
  "CAR": { "signs": ["USA"], "side": "right" },
  "TIMEZONES": [
    "UTC-12:00",
    "UTC-11:00",
    "UTC-10:00",
    "UTC-09:00",
    "UTC-08:00",
    "UTC-07:00",
    "UTC-06:00",
    "UTC-05:00",
    "UTC-04:00",
    "UTC+10:00",
    "UTC+12:00"
  ],
  "CONTINENTS": ["North America"],
  "FLAGS": {
    "png": "https://flagcdn.com/w320/us.png",
    "svg": "https://flagcdn.com/us.svg",
    "alt": "The flag of the United States of America is composed of thirteen equal horizontal bands of red alternating with white. A blue rectangle, bearing fifty small five-pointed white stars arranged in nine rows where rows of six stars alternate with rows of five stars, is superimposed in the canton."
  },
  "COATOFARMS": {
    "png": "https://mainfacts.com/media/images/coats_of_arms/us.png",
    "svg": "https://mainfacts.com/media/images/coats_of_arms/us.svg"
  },
  "STARTOFWEEK": "sunday",
  "CAPITALINFO": { "latlng": [38.89, -77.05] },
  "POSTALCODE": { "format": "#####-####", "regex": "^\\d{5}(-\\d{4})?$" },
  "PUBLIC-KEY": "00dc58b0-c233-4c84-950b-61cbe6012973",
  "X-PROVIDE": "https://ip2geo.ir"
}

```

Sure! Here's an explanation of the fields in the record you provided:

1. NAME:
   - "common": The common name of the country is "United States."
   - "official": The official name of the country is "United States of America."
   - "nativeName": The native name of the country in English is the same as the official name ("United States of America").

2. TLD (Top-Level Domain):
   - [".us"]: The internet top-level domain for websites registered in the United States is ".us."

3. CCA2: The two-letter country code for the United States is "US."

4. CCN3: The three-digit country code for the United States is "840."

5. CCA3: The three-letter country code for the United States is "USA."

6. CIOC: The International Olympic Committee (IOC) code for the United States is "USA."

7. INDEPENDENT: It indicates that the United States is an independent country.

8. STATUS: The status of the country is "officially assigned."

9. UNMEMBER: It indicates that the United States is a member of the United Nations.

10. CURRENCIES:
    - USD: The currency used in the United States is the United States dollar (USD).
      - "name": The official name of the currency is "United States dollar."
      - "symbol": The symbol used to represent the currency is "$."

11. IDD (International Direct Dialing):
    - "root": The root international dialing code for making phone calls to the United States is "+1."
    - "suffixes": There are several suffixes or area codes that can be appended after the root code to dial specific regions within the United States, such as "201," "202," "203," "205," "206," and so on.

