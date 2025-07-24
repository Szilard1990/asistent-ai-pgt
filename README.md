<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Asistent AI – PGT Jazz Carafe</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <style>
      html, body {
        margin: 0;
        padding: 0;
        height: 100%;
        font-family: sans-serif;
        background-color: #f2f2f2;
      }
    </style>
  </head>
  <body>
    <h2 style="text-align:center; padding: 20px;">Asistent AI – PGT Jazz Carafe</h2>
    <div id="vf-chat" style="width:100%; height:600px;"></div>

    <script type="text/javascript">
      (function(d, t) {
        var v = d.createElement(t), s = d.getElementsByTagName(t)[0];
        v.onload = function() {
          window.voiceflow.chat.load({
            verify: { projectID: '6880834ffec6de56176e03f6' },
            url: 'https://general-runtime.voiceflow.com',
            versionID: '6880834ffec6de56176e03f7',
            voice: { url: "https://runtime-api.voiceflow.com" }
          });
        }
        v.src = "https://cdn.voiceflow.com/widget-next/bundle.mjs";
        v.type = "text/javascript";
        s.parentNode.insertBefore(v, s);
      })(document, 'script');
    </script>
  </body>
</html>
