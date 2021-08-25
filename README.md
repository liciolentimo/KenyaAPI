# \[ 🚧 Work in progress 👷‍♀️⛏👷🔧️🚧 \] Kenya API

The Kenya API is a REST API that acts a collection of common facts about Kenya.

## Endpoints

| Request | Endpoint | Description |
| ----------- | ----------- | ----------- |
| **GET** | `https://fenhazoihvagwabwzakm.supabase.co/rest/v1/counties` | Get all counties |
| **GET** | `https://fenhazoihvagwabwzakm.supabase.co/rest/v1/counties?select=county` | Get individual county |
| **GET** | `https://fenhazoihvagwabwzakm.supabase.co/rest/v1/general` | General info |

## Examples

```
[
  {
    "name": "Kenya",
    "capital": "Nairobi",
    "president": "Uhuru Kenyatta",
    "independence": 1963
  }
]
```
```
{
    "id": 25,
    "county": "Samburu",
    "headquarters": "Maralal",
    "area": "21,000km2",
    "population": "310,327",
    "governor": "Moses Kasaine Lenolkulal",
    "website": "https://www.samburu.go.ke"
  },
  ```

## Authorization

The authorization is by *Bearer token*
Kindly get in touch via *lentimo@gmail.com* or [Twitter](https://twitter.com/liciolentimo) to request API key
