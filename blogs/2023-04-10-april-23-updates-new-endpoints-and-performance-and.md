---
title: "April ’23 Updates: New Endpoints and Performance and Usability Improvements"
url: "https://aerodatabox.com/april-23-updates/"
date: "2023-04-10"
feed_url: "https://aerodatabox.com/news/rss.xml"
---
Search airports by IP geolocation and Search airports by location endpoints now have query-string style counter-parts. If you’re on the most recent pricing plans, we recommend:using /airports/search/location?lat={lat}&lon={lon}&radiusKm={radiusKm}&limit={limit} instead of /airports/search/location/{lat}/{lon}/km/{radiusKm}/{limit} (documentation)using /airports/search/ip?q={ip}&radiusKm={radiusKm}&limit={limit} instead of /airports/search/ip/{ip}/km/{radiusKm}/{limit} (documentation)New endpoint added: Solar and day time at the airportGET /airports/{codeType}/{code}/time/solar/*It produces cer
