<div>
  
```bash
$ CDN Server List
> Oracle Paid Server 1...
 > vercel: vvr.shinusterben.xyz | railway: railway.shinusterben.xyz | alibaba: edge.shinusterben.xyz | cloudflre: arise.shinusterben.xyz
   > multiplexer setup
     > copy the sub-url,
       > paste it in any v2ray client,
       > find the multiplexer inbound and choose ws or xhttp then edit,
       > replace port to 443, set tls,
       > xhttp-alpn: h2, xhttp-alpn: http/1.1,
       > allowinsecure true or false { set true for sni trick }
$ Client Sample
> address: bughost or cdn-host e.g. www.railway.com
> host: e.g. railway.shinusterben.xyz
> sni: bughost or cdn-host e.g. railway.shinusterben.xyz
```

</div>
