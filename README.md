List of countries in json format that includes country dial code, country abbreviation and flag.

## Get Started

-   npm install country-list-json
-   import countries

## Usage

**Get country name**

-   countries.name

**Get arabic country name**

-   countries.name_ar

**Get dial code**

-   countries.dial_code

**Get country code**

-   countries.code

**Get country flag**

-   countries.flag

## Data Example

```
[
  {
      name: "Japan",
	  name_ar: "اليابان"
      dial_code: "+81",
      code: "JP",
      flag: "🇯🇵"
  },
  {
      name: "Russia",
	  name_ar: "روسيا",
      dial_code: "+7",
      code: "RU",
      flag: "🇷🇺"
  },
]
```

## Importing TypeScript types
```
import { CountryListItemType } from 'country-list-json';
```