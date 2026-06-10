[Costco Scraper](https://apify.com/newpo/costco-scraper?fpr=data)

This actor scrapes products on Costco. Data points include

- Product Name
- Specs
- Descriptions
- Images
- Services and Warranty
- and more (see output example)!

## Input Parameters

- URLs
Use any product listing pages or search pages e.g. [https://www.costco.com/televisions.html](https://www.costco.com/televisions.html)
- maxPages
Number of pages you'd like to scrape.

## Data Output

A dataset will be created from each run (go to `Storage` on the sidebar). It looks like `costco-details-1676441778724`. The trailing numbers are the unix timestamp the actor started.

## How much does it cost to scrape Costco?

I haven't tested it yet but it uses minimal resources so I'd say 10,000 products for around $1~$2. I'll update this once I have more accurate data.

## Sample Output

```
[{
  "product": [
    {
      "pricePerUnit": "",
      "unitOfMeasure": "Price Per :",
      "catentry": "2887933",
      "isScheduledDeliverable": "false",
      "limitOneQuantity": false,
      "priceInCartOnly": false,
      "isSinglePriced": true,
      "membershipRequired": false,
      "isGroceryItem": false,
      "isDependentProductConfigured": false,
      "isComingSoon": false
    }
  ],
  "products": [
    [
      {
        "isLocInvItem": "true",
        "pricePerUnit": "",
        "unitOfMeasure": "Price Per :",
        "unpriced": false,
        "single": true,
        "catentry": "2887934",
        "partNumber": "9755800",
        "programType": "3rdPartyDelivery,LocationControlledInventory,InWarehouse,WarehouseDelivery,Standard",
        "manufacturerPartNumber": "9755800 ",
        "defaultShipModeId": "32651",
        "vendorModelNumber": "",
        "price": "",
        "productName": "LG 55&#034; Class - UQ8000 Series - 4K UHD LED LCD TV",
        "productUrl": "https://www.costco.com/lg-55%22-class---uq8000-series---4k-uhd-led-lcd-tv.product.9755800.html",
        "listPrice": "LTEuMA==",
        "date": "",
        "date2": "",
        "type": "0",
        "message": "0",
        "zipcodeAvailabilityMessage": "0",
        "zipcodeAvailabilityResponseCode": "success",
        "inventory": "IN_STOCK",
        "minQty": "1",
        "maxQty": "3",
        "ordinal": "4794.0",
        "itemSequence": "",
        "img_url": "https://images.costco-static.com/ImageDelivery/imageService?profileId=12026540&amp;imageId=9755800-847__1&amp;recipeName=300",
        "plainPackaging": "2",
        "eddVendorName": "EDD:Calendar",
        "liveEDD": "true",
        "options": [],
        "itemLimitOneQty": "false",
        "isDependentProductConfigured": "false",
        "feeRegions": [],
        "feeOptions": [],
        "regionPrices": []
      }
    ]
  ],
  "options": [
    []
  ],
  "partNumber": "100970919",
  "id": "100970919",
  "vsku": "100970919",
  "psku": "9755800",
  "name": "LG 55\" Class - UQ8000 Series - 4K UHD LED LCD TV",
  "price": "",
  "priceMin": "369.99",
  "priceMax": "369.99",
  "priceVaries": "true",
  "available": "In stock",
  "categories": [
    "Electronics",
    "TVs",
    "55 inch TVs"
  ],
  "storeid": "US",
  "productId": "100970919",
  "specs": [
    {
      "name": "Brand",
      "value": "LG"
    },
    {
      "name": "Compatible with",
      "value": "Alexa"
    },
    {
      "name": "Compatible with",
      "value": "Apple AirPlay 2"
    },
    {
      "name": "Compatible with",
      "value": "Apple HomeKit"
    },
    {
      "name": "Compatible with",
      "value": "Google Assistant"
    },
    {
      "name": "Dimensions (with stand)",
      "value": "9.1 in. x 30.6 in. x 48.6 in."
    },
    {
      "name": "Dimensions (without stand)",
      "value": "2.3 in. x 28.1 in. x 48.6 in."
    },
    {
      "name": "Display Type",
      "value": "Direct Lit LED-LCD"
    },
    {
      "name": "High Dynamic Range (HDR)",
      "value": "HDR10"
    },
    {
      "name": "High Dynamic Range (HDR)",
      "value": "HLG"
    },
    {
      "name": "Inputs - HDMI 1",
      "value": "HDMI 2.0"
    },
    {
      "name": "Inputs - HDMI 2",
      "value": "HDMI 2.0 eARC"
    },
    {
      "name": "Model",
      "value": "LG 55UQ8000AUB"
    },
    {
      "name": "Motion Technology",
      "value": "TruMotion 120"
    },
    {
      "name": "Native Refresh Rate",
      "value": "60Hz"
    },
    {
      "name": "Number of Digital Optical Audio Inputs",
      "value": "1"
    },
    {
      "name": "Number of HDMI Inputs",
      "value": "2"
    },
    {
      "name": "Number of USB Ports",
      "value": "1"
    },
    {
      "name": "Resolution",
      "value": "3840 x 2160"
    },
    {
      "name": "Screen Size Class",
      "value": "55 in."
    },
    {
      "name": "Screen Type",
      "value": "Flat"
    },
    {
      "name": "Smart TV Platform",
      "value": "webOS"
    },
    {
      "name": "Speaker Output",
      "value": "20 W"
    },
    {
      "name": "VESA Mounting Standard",
      "value": "300x300"
    },
    {
      "name": "Warranty Coverage",
      "value": "2 Years"
    },
    {
      "name": "Weight - with Stand",
      "value": "31.3 lb."
    },
    {
      "name": "Weight - without Stand",
      "value": "30.9 lb."
    },
    {
      "name": "Wireless Standard",
      "value": "802.11ac"
    }
  ],
  "images": [],
  "services": [
    "2nd Year Warranty",
    "Free Technical Support",
    "90 Day Return Policy"
  ],
  "description": {},
  "ratings": {
    "reviewSummary": {
      "numReviews": 2768,
      "primaryRating": {
        "distribution": [
          {
            "key": 5,
            "count": 1936
          },
          {
            "key": 4,
            "count": 464
          },
          {
            "key": 3,
            "count": 137
          },
          {
            "key": 2,
            "count": 67
          },
          {
            "key": 1,
            "count": 164
          }
        ],
        "average": 4.4238,
        "missing": 0,
        "ratingRange": 5
      },
      "recommended": {
        "distribution": [
          {
            "count": 721,
            "key": true
          },
          {
            "count": 175,
            "key": false
          }
        ],
        "missing": 1872
      }
    },
    "questionSummary": {
      "numQuestions": 0,
      "numAnswers": 0
    }
  }
}]
```