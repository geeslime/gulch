---
{"dg-publish":true,"permalink":"/note/welcome-page/","tags":["gardenEntry"],"created":"2025-01-02T18:59:40.908-05:00","updated":"2025-01-03T16:45:22.712-05:00"}
---


<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Welcome Page</title>
  <meta property="og:title" content="Welcome Page" />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="https://raw.githubusercontent.com/geeslime/img/main/atlasdoodle.png" />
  <meta property="og:image:secure_url" content="https://raw.githubusercontent.com/geeslime/img/main/atlasdoodle.png" />
  <meta property="og:image:type" content="image/jpeg" />
  <meta property="og:image:width" content="688" />
  <meta property="og:image:height" content="419" />
  <meta property="og:description" content="This online Obsidian vault is maintained by gee." />
  <meta property="og:locale" content="en_US" />
  <meta property="og:url" content="https://gees-gulch.wiki/welcome-page" />
  <meta property="og:site_name" content="gulch" />
</head>






<center><h2>WELCOME</h2></center>

This online <a href="https://obsidian.md/">Obsidian</a> **vault** is *maintained* by [[gee\|gee]]. If you would like to contribute to this vault — or discuss about its contents with any of its [[contributors\|contributors]] — you can do so by joining this Discord server: <a href="https://discord.gg/k5pJuUTpnQ">https://discord.gg/k5pJuUTpnQ</a> and asking me (gee.).

The site also supports Disqus comments at the bottom of each page for readers to add their thoughts to a note.

<center><h2>ALL NOTES LIST</h2></center>

<center><h6><i><u>sort by tags</u></i></h6></center>

<div class="tab">
 <button class="tablinks" onclick="openTab(event, 'All')">All</button>
 <button class="tablinks" onclick="openTab(event, 'Definitions')">Definitions</button>
</div>

<div id="All" class="tabcontent">

| File                                   | Tags | Aliases |
| -------------------------------------- | ---- | ------- |
| [[note/Welcome Page\|Welcome Page]] | \-   | \-      |
| [[note/Untitled\|Untitled]]         | \-   | \-      |

{ .block-language-dataview}

</div>


<div id="Definitions" class="tabcontent">
  
 | File | Tags | Aliases |
| ---- | ---- | ------- |

{ .block-language-dataview}

</div>


<script>
    function openTab(evt, tabName) {
      var i, tabcontent, tablinks;
      tabcontent = document.getElementsByClassName("tabcontent");
      for (i = 0; i < tabcontent.length; i++) {
        tabcontent[i].classList.remove("show");
      }
      tablinks = document.getElementsByClassName("tablinks");
      for (i = 0; i < tablinks.length; i++) {
        tablinks[i].className = tablinks[i].className.replace(" active", "");
      }
      document.getElementById(tabName).classList.add("show");
      evt.currentTarget.className += " active";
    }

    document.addEventListener("DOMContentLoaded", function() {
      document.querySelector(".tab button").click();
    });
</script>


<body>
  <!-- Include Disqus comments directly in HTML -->
  <div id="disqus_thread"></div>
  <script>
      var disqus_config = function () {
          this.page.url = "https://gees-gulch.wiki/welcome-page";  // Replace with your page's canonical URL variable
          this.page.identifier = "welcome-page"; // Replace with your page's unique identifier variable
      };
      (function() {  // DON'T EDIT BELOW THIS LINE
          var d = document, s = d.createElement('script');
          s.src = 'https://https-gees-gulch-wiki.disqus.com/embed.js';
          s.setAttribute('data-timestamp', +new Date());
          (d.head || d.body).appendChild(s);
      })();
  </script>
  <noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
</body>