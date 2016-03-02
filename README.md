# cloud-vision-api-experiments
Just trying out the new [Google Cloud Vision API](https://cloud.google.com/vision).

# dependencies
[Jil](https://www.nuget.org/packages/Jil)

# setup
* Open sln in Visual Studio 2015
* Fill in API key
* Run

# output
For this test image...

![Punta Tombo](punta_tombo.jpg)

... the API returns:

```
{
  "responses": [
    {
      "labelAnnotations": [
        {
          "mid": "/m/06npx",
          "description": "sea",
          "score": 0.85361129
        },
        {
          "mid": "/m/01lxd",
          "description": "coast",
          "score": 0.70898777
        },
        {
          "mid": "/m/0gd2v",
          "description": "marine mammal",
          "score": 0.66608769
        },
        {
          "mid": "/m/03qqnt",
          "description": "flightless bird",
          "score": 0.64250052
        },
        {
          "mid": "/m/05z6w",
          "description": "penguin",
          "score": 0.63420784
        },
        {
          "mid": "/m/015p6",
          "description": "bird",
          "score": 0.62039882
        },
        {
          "mid": "/m/099fz",
          "description": "sand",
          "score": 0.529671
        },
        {
          "mid": "/m/01cbzq",
          "description": "rock",
          "score": 0.50134254
        }
      ]
    }
  ]
}
```

Really cool!





