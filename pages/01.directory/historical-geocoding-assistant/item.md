---
title: 'Historical Geocoding Assistant'
aura:
    pagetype: website
feed:
    limit: 10
metadata:
    'og:url': 'https://tempopedia.org/directory/historical-geocoding-assistant'
    'og:type': website
    'og:title': 'Historical Geocoding Assistant | Tempopedia'
    'og:image': 'https://tempopedia.org/directory/historical-geocoding-assistant/dissinet.cz_apps_hga_(720p).png'
    'og:image:type': image/png
    'og:image:width': '2560'
    'og:image:height': '1440'
    'og:author': Tempopedia
    'twitter:card': summary_large_image
    'twitter:title': 'Historical Geocoding Assistant | Tempopedia'
    'twitter:site': '@tempopedia_org'
    'twitter:creator': '@tempopedia_org'
    'twitter:image': 'https://tempopedia.org/directory/historical-geocoding-assistant/dissinet.cz_apps_hga_(720p).png'
    'article:published_time': '2021-05-19T14:34:10+00:00'
    'article:modified_time': '2021-05-19T14:34:20+00:00'
    'article:author': Tempopedia
media_order: dissinet.cz_apps_hga_(720p).png
---

Geocodes historical places in Google Sheets

===

! Website: http://dissinet.cz/apps/hga/
! Repository: https://github.com/adammertel/historical-geocoding-assistant
! Price: Free
! License: Open Source
! Skill level: 🏋️‍♀️ Trained end-user

## Description

The “Historical Geocoding Assistant” is an open-source browser-based application for assigning geographic coordinates in a more convenient and faster way than copy-pasting them from services such as Google Maps. The application was designed with historical projects in mind but is suitable for any geocoding work.

### Advantages

- HGA is easy to access — it is web-based and does not require any additional software to be installed. The dataset is stored as a Google Sheets table; therefore, the user has full access to the version history and rights management, and all edits are automatically saved online. Thanks to this cloud-based solution, more editors can work on a dataset in parallel.
- HGA has an interactive visual interface that enhances the usability and effectiveness of an assisted geocoding strategy – a middle ground between the fully automated approach without any user control and the time-consuming manual approach. The interface of the application is fully graphical and map-centred, which allows the user to visually validate the input, compare various records from diverse services and easily navigate through the dataset.
- HGA stands on the integration of existing external services to assist the user in the geocoding process. Gazetteers (Geonames, Wikipedia, Getty TGN, Pleiades, and China Historical Gazetteer) automatically return the best suggestions for the selected record on the basis of the location name and the given geographic boundaries. These suggestions are then sorted with either the returned geocode quality parameter or, if not available (as in the case of Pleiades and Getty TGN), with the built-in string similarity algorithm based on the Levenshtein distance. Besides automated search in gazetteers, the user can use various integrated search engines (e.g., Google) to manually search for any location name.
- HGA is highly customizable – the user can set various options within the interface of the application, e.g. the names of reserved columns, the geographical scope for suggestions, and the content of the map. The second way of setting up the application is to edit the JSON configuration files to control map layers, global settings, and the access to Google Drive API. Moreover, the code of the application is open-source, so anyone can extend its functionality and deploy their own version of the software.
- HGA focuses specifically on historical research — we have integrated various relevant services such as [Pleiades](https://tempopedia.org/directory/pleiades), the Getty Thesaurus of Geographic Names, and Wikipedia. The application also proposes a customizable system of certainty levels that allows the user to classify the precision of the geocoded places. This system was created and tested specifically for the purposes of historical projects.