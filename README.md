# amp-map

### IPEDS In Order from Slowest to Fastest:

Neither AMP nor CloudFront:

- IPEDS BR Alpha – 7.13 seconds
- IPEDS Production – 4.97 seconds

Only AMP:

- IPEDS BR Alpha + AMP – 4.09 seconds
- IPEDS BR Alpha + AMP + AMP CDN – 3.23 seconds

AMP + CloudFront:

- IPEDS BR Beta + AMP + CloudFront – 3.05 seconds
- IPEDS BR Beta + AMP + AMP CDN + CloudFront – 2.79 seconds

Only CloudFront:

- IPEDS BR Beta + CloudFront – 760 *milliseconds*

### Pingdom Screenshots, In Order from Slowest to Fastest:

IPEDS BR Alpha – 7.13 seconds:

![alt text](http://beta.blueraster.io/dev-summit/screenshots/ipeds-alpha.png "IPEDS Alpha")

IPEDS Production – 4.97 seconds:

![alt text](http://beta.blueraster.io/dev-summit/screenshots/ipeds-prod.png "IPEDS Alpha")

IPEDS BR Alpha + AMP – 4.09 seconds:

![alt text](http://beta.blueraster.io/dev-summit/screenshots/ipeds-amp-alpha.png "IPEDS Alpha")

IPEDS BR Alpha + AMP + AMP CDN – 3.23 seconds:

![alt text](http://beta.blueraster.io/dev-summit/screenshots/ipeds-amp-cdn-alpha.png "IPEDS Alpha")

IPEDS BR Beta + AMP + CloudFront – 3.05 seconds:

![alt text](http://beta.blueraster.io/dev-summit/screenshots/ipeds-amp-cloudfront.png "IPEDS Alpha")

IPEDS BR Beta + AMP + AMP CDN + CloudFront – 2.79 seconds:

![alt text](http://beta.blueraster.io/dev-summit/screenshots/ipeds-amp-cdn-cloudfront.png "IPEDS Alpha")

IPEDS BR Beta + CloudFront – 760 *milliseconds*:

![alt text](http://beta.blueraster.io/dev-summit/screenshots/ipeds-cloudfront.png "IPEDS Alpha")
