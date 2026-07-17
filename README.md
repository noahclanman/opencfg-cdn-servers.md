<div>
  
```bash

$ Client Sample
> address: bughost or cdn-host e.g. www.railway.com
> host: e.g. railway.shinusterben.xyz
> sni: bughost or cdn-host e.g. railway.shinusterben.xyz

$ CDN Server List
> Oracle Paid Server 1...
 > vercel: hidden | railway: railway.shinusterben.xyz | alibaba: edge.shinusterben.xyz | cloudflre: arise.shinusterben.xyz
   > multiplexer setup
     > copy the sub-url,
       > paste it in any v2ray client,
         > find the multiplexer inbound and choose ws or xhttp then edit,
           > replace port to 443, set tls,
             > xhttp-alpn: h2, xhttp-alpn: http/1.1,
               > allowinsecure true or false { set true for sni trick }

$ CDN Server List
> Oracle Paid Server 2...
 > vercel: hidden | railway: hidden | alibaba: edge2.shinusterben.xyz | cloudflre: arise2.shinusterben.xyz
   > multiplexer setup
     > copy the sub-url,
       > paste it in any v2ray client,
         > find the multiplexer inbound and choose ws or xhttp then edit,
           > replace port to 443, set tls,
             > xhttp-alpn: h2, xhttp-alpn: http/1.1,
               > allowinsecure true or false { set true for sni trick 

$ make sure that you create an account via v2ray-vless in opencfg.xyz

```

</div>
