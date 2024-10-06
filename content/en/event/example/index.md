---
title: location 

event: computer science lecture
event_url: https://csai.jbnu.ac.kr/csai/index.do

location: JBNU enginering school no.7
address:
  street: backjaedaero 567
  city: jeonju - duckjin
  region: jeon buk
  postcode: '54896'
  country: south korea
content:
  coordinates:
    latitude: '35.84601324617979'
    longitude: '127.13444961966684'
   

summary: where should i go to listen to CS lecture
abstract: 'Classes majoring in computer science are usually held in Chonbuk National Universitys Technology Hall 7. Major classes include algorithms, data structures, machine learning, web service design, data mining, operating systems, cryptography, artificial intelligence, cloud computing, and mobile programming. Professors labs are also located in the same building. '

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '1951-10-06T13:00:00Z'
#date_end: '2091-06-01T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/ko/%EC%82%AC%EC%A7%84/group-of-fresh-graduates-students-throwing-their-academic-hat-in-the-air-8CqDvPuo_kI)'
  focal_point: Right

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
url_code: 'https://github.com/05solar'
#url_pdf: ''
#url_slides: 'https://slideshare.net'
#url_video: 'https://youtube.com'

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
<div id="map" style="height: 400px; width: 100%;"></div>

<script>
  function initMap() {
    var location = {lat: 35.84601324617979, lng: 127.13444961966684}; // 전북대학교 공과대학 좌표
    var map = new google.maps.Map(document.getElementById('map'), {
      zoom: 15,
      center: location
    });
    var marker = new google.maps.Marker({
      position: location,
      map: map
    });
  }
</script>

<script async defer src="https://maps.googleapis.com/maps/api/js?key=AIzaSyCfBrU11k1rgvwY1Lri2O-JaqOV7_dHMis&callback=initMap"></script>