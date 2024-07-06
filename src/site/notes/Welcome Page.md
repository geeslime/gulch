---
{"dg-publish":true,"permalink":"/welcome-page/","tags":["gardenEntry"],"noteIcon":""}
---

<head>
  <title>Welcome Page</title>
  <meta property="og:title" content="Welcome Page" />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="https://raw.githubusercontent.com/geeslime/img/bcabf2fb1a59f4514ebb36da30045c835b5a4d85/thing/atlas.png" />
  <meta property="og:image:secure_url" content="https://raw.githubusercontent.com/geeslime/img/bcabf2fb1a59f4514ebb36da30045c835b5a4d85/thing/atlas.png" />
  <meta property="og:image:type" content="image/jpeg" />
  <meta property="og:image:width" content="688" />
  <meta property="og:image:height" content="419" />
  <meta property="og:description" content="This online Obsidian vault is meant to serve as a community-driven resource and wiki." />
  <meta property="og:locale" content="en_US" />
  <meta property="og:url" content="https://gulch.vercel.app/welcome-page" />
  <meta property="og:site_name" content="gulch" />
  <style>
    .banner {
        width: 100%;
        height: 200px;
        background: url('https://edge.discord.me/server/aeeb3c785c45d9f103c1f832c51c35bd78a6722e7d1a09d426e7534274a049f8/banner_6472219190918742f56cd3eaab4edf32bca21f5a8864053190cf671877d5ffc8.jpg') no-repeat top center;
        background-size: cover;
        position: relative;
        overflow: visible;
    }
    .banner::after {
        content: '';
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background: linear-gradient(to bottom, rgba(252, 252, 252, 0.1), rgba(252, 252, 252, 1)),
                    linear-gradient(to right, rgba(252, 252, 252, 1), rgba(252, 252, 252, 0.1) 20%, rgba(252, 252, 252, 0.1) 80%, rgba(252, 252, 252, 1));
    }
    .scrolling-links {
        position: fixed;
        right: 20px;
        top: 50%;
        transform: translateY(-50%);
        width: 220px;
        height: 350px;
        border: 2px solid #333;
        border-radius: 10px;
        overflow: hidden;
        padding: 10px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        background: #fff;
    }
    .scrolling-links ul {
        list-style-type: none;
        padding: 0;
        margin: 0;
        position: relative;
        height: calc(100% - 30px); /* Adjust for header */
        animation: scrollUp 60s linear infinite;
    }
    .scrolling-links li {
        background-color: #e7e7e7;
        padding: 10px;
        margin: 5px 0;
        border-radius: 5px;
        text-align: center;
        font-size: 16px;
    }
    @keyframes scrollUp {
        0% {
            transform: translateY(0%);
        }
        100% {
            transform: translateY(-100%);
        }
    }
    .scrolling-links h2 {
        text-align: center;
        margin: 0;
        padding: 0;
        border-top: 2px solid #333;
        padding-top: 10px;
        background: #f0f0f0; /* Slightly darker shade */
        position: relative;
        z-index: 1;
    }
  </style>
</head>
<body>
  <div class="banner"></div>
  <div class="container">
  </div>
</body>

<center><h1>WELCOME</h1></center>

This online <a href="https://obsidian.md/">obsidian</a> vault is meant to serve as a community-driven resource and wiki.
<center><h1>INFO</h1></center>

This vault is maintained by [[geeslime\|geeslime]]. It was initially a clone of [[note/LiquidZulu\|LiquidZulu's]] obsidian vault — similarly hosted online at <a href="https://liquidzulu.github.io/brain/">liquidzulu.github.io/brain</a> (this vault can be seen as a less highly curated but more community-driven and diversified addition to his overall project).
 
<center><h2>CONTRIBUTING</h2></center>

If you would like to contribute to this vault — or discuss about its contents with any of its [[contributors\|contributors]] — you can do so by joining this discord server: <a href="https://discord.gg/k5pJuUTpnQ">https://discord.gg/k5pJuUTpnQ</a> and asking me (gee.).

This site also supports disqus comments at the bottom of each page. If you would like to give some suggestions for the site as a whole you can do so [[c\|here]].



<body>
  </div>
  <div class="scrolling-links">
    <ul id="scrolling-list">
      <li><a href="https://gulch.vercel.app/note/liquid-zulu/">LiquidZulu</a></li>
      <li><a href="https://gulch.vercel.app/note/geeslime/">geeslime</a></li>
      <li>[[Contributor3\|Contributor3]]</li>
      <li>[[Contributor4\|Contributor4]]</li>
      <li>[[Contributor5\|Contributor5]]</li>
      <li>[[Contributor6\|Contributor6]]</li>
      <li>[[Contributor7\|Contributor7]]</li>
      <li>[[Contributor8\|Contributor8]]</li>
      <li>[[Contributor9\|Contributor9]]</li>
      <li>[[Contributor10\|Contributor10]]</li>
      <li><a href="https://gulch.vercel.app/note/liquid-zulu/">LiquidZulu</a></li> <!-- Duplicate set starts here -->
      <li><a href="https://gulch.vercel.app/note/geeslime/">geeslime</a></li>
      <li>[[Contributor3\|Contributor3]]</li>
      <li>[[Contributor4\|Contributor4]]</li>
      <li>[[Contributor5\|Contributor5]]</li>
      <li>[[Contributor6\|Contributor6]]</li>
      <li>[[Contributor7\|Contributor7]]</li>
      <li>[[Contributor8\|Contributor8]]</li>
      <li>[[Contributor9\|Contributor9]]</li>
      <li>[[Contributor10\|Contributor10]]</li> <!-- Duplicate set ends here -->
    </ul>
    <h2>Contributors</h2>
  </div>
  <!-- Include Disqus comments directly in HTML -->
  <div id="disqus_thread"></div>
  <script>
      var disqus_config = function () {
          this.page.url = "https://gulch.vercel.app/welcome-page";  // Replace with your page's canonical URL variable
          this.page.identifier = "welcome-page"; // Replace with your page's unique identifier variable
      };
      (function() {  // DON'T EDIT BELOW THIS LINE
          var d = document, s = d.createElement('script');
          s.src = 'https://https-gulch-vercel-app.disqus.com/embed.js';
          s.setAttribute('data-timestamp', +new Date());
          (d.head || d.body).appendChild(s);
      })();
  </script>
  <noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
</body>
</html>
