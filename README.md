# Monsters Commune Front End


## develop
- static front-end project


## Nginx Config
```
server {
  server_name ~^(www\.|)monsterscommune.com;
  root /tmp/website/monster-fe;
  index index.html;
}
```

## pages
```
project
└───css // styles
└───fonts // ttf, otf files...
└───js // javaScropts files
pages
└───index.html // home page
└───about.html // about us
└───kids.html // kids sport recommends
└───warehouse.html // fitness warehouse recommends
```

## Tech
- [x] [imagesloaded](https://imagesloaded.desandro.com/)
- [x] [scrollMonitor](https://github.com/stutrek/scrollMonitor)



