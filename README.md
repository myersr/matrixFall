Code to have matrix falling in your browser  
Paste the code below into a new tab in your browser:
'data:text/html,<body%20style=margin:0><canvas%20id=q%20/><script>var%20q=document.getElementById('q'),s=window.screen,w=q.width=s.width,h=q.height=s.height,p=Array(256).join(1).split(''),c=q.getContext('2d'),m=Math;setInterval(function(){c.fillStyle='rgba(0,0,0,0.05)';c.fillRect(0,0,w,h);c.fillStyle='rgba(0,255,0,1)';p=p.map(function(v,i){r=m.random();c.fillText(String.fromCharCode(m.floor(2720+r*33)),i*10,v);v+=10;%20return%20v>768+r*1e4?0:v})},33)</script>
'
