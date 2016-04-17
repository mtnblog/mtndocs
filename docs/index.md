# Welcome to MTNBlog's API Documentation

We're currently in the middle of building out our api so keep checking back or subscribe for updates.

## Using MTNBlog's API

Lorem voluptate amet pariatur in nam cupiditate porro! Quas labore beatae repellendus expedita aliquid dolor blanditiis. Blanditiis fugit commodi dolore enim corporis! Consequuntur quo nemo beatae voluptatibus inventore qui veniam?

## Authentication

Amet adipisci placeat nobis saepe perferendis cum molestias. Veniam sit omnis porro sed explicabo. Debitis rem nihil delectus voluptatem voluptatum molestiae. Nobis temporibus provident quas iusto molestias. Velit iste iste.

## GET [/api/mountains]

Returns a list of mountains.

    [
        {
            "mountainRange": "Alps",
            "name": "Matterhorn",
            "imageS": "http://i.imgur.com/ZgjyET2.jpg",
            "imageL": "http://i.imgur.com/7bMqZqj.jpg",
            "photoCreditsName": "Sam Ferrara",
            "photoCreditsUrl": "http://samferrara.ch",
            "latitude": 45.976389,
            "longitude": 7.658333,
            "elevationM": 4478,
            "elevationFt": 14692
        },
        {
            "mountainRange": "Patagonia",
            "name": "Fitz Roy",
            "imageS": "http://i.imgur.com/wOpLBcU.jpg",
            "imageL": "http://i.imgur.com/NrZEiun.jpg",
            "photoCreditsName": "Greg Boratyn",
            "photoCreditsUrl": "http://www.eveningphotography.com/",
            "latitude": -49.271278,
            "longitude": -73.043222,
            "elevationM": 3405,
            "elevationFt": 11171
        },
        ...
    ]

Parameters

| Parameter  | How to use | Description |
|------------|------------|-------------|
| API Key    | ?key=x     |             |

## GET [/api/mountain/{id}]

Returns a single mountain.

    {
        "mountainRange": "Alps",
        "name": "Matterhorn",
        "imageS": "http://i.imgur.com/ZgjyET2.jpg",
        "imageL": "http://i.imgur.com/7bMqZqj.jpg",
        "photoCreditsName": "Sam Ferrara",
        "photoCreditsUrl": "http://samferrara.ch",
        "latitude": 45.976389,
        "longitude": 7.658333,
        "elevationM": 4478,
        "elevationFt": 14692
    }

