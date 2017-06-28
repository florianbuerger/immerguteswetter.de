+++
title = "Bilder"
layout = "default"
[menu]
    [menu.main]
        weight = 120
+++

<h1 class="title-main">Wir auf Instagram</h1>

<div id="instafeed"></div>

<h3 class="insta-more"><a href="">mehr Bilder →</a></h3>

<script type="text/javascript" src="/js/instafeed.min.js"></script>

<script type="text/javascript">
  var userFeed = new Instafeed({
    get: 'user',
    userId: '3137108085',
    clientId: 'f565d0d1a8504e19a1ceaf7478e289dd',
    accessToken: '3137108085.3a81a9f.314d32427efb424dac36519f0c39ab2d',
    resolution: 'standard_resolution',
    template: '<a href="{{link}}" target="_blank" id="{{id}}"><img src="{{image}}" /></a>',
    sortBy: 'most-recent',
    limit: 16,
    links: false
  });
  userFeed.run();
</script>


