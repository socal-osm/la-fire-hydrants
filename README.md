# Los Angeles fire hydrant import
Proposed import of all fire hydrants inside the city or county of Los Angeles.

A quick run at Overpass Turbo shows 644 in Los Angeles and northern Orange County.

![overpass](https://cloud.githubusercontent.com/assets/695934/17114221/d0a86dae-5262-11e6-81bd-01dd303537a0.png)

Tagging: `emergency=fire_hydrant`

[OSM Wiki page](http://wiki.openstreetmap.org/wiki/Tag:emergency%3Dfire_hydrant)

The county and city have fire hydrant shapefiles:
- [Los Angeles County](http://egis3.lacounty.gov/dataportal/2012/05/23/los-angeles-county-fire-hydrant-layer/) 100,000+
- [City of Los Angeles](http://geohub.lacity.org/datasets/39e5c79ddd8a4eada40340f6ceb08fae_0) 57,000+

## Next steps:

1. ~~Reach out to LAFD and request a shapefile of all fire hydrants~~
2. Compare that file with what's currently in OSM
3. Develop import strategy (what size chunks?)
4. Import!
5. Review
6. Celebrate!
