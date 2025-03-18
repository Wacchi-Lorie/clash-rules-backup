```
rule-providers:
# loyalsoldier clash rules
 reject:
  type: http
  behavior: domain
  url: "https://cdn.jsdelivr.net/gh/Loyalsoldier/clash-rules@release/reject.txt"
  path: ./providers/reject.yaml
  interval: 86400
 proxy:
  type: http
  behavior: domain
  url: "https://cdn.jsdelivr.net/gh/Loyalsoldier/clash-rules@release/proxy.txt"
  path: ./providers/proxy.yaml
  interval: 86400
 CN_DIRECT:
  type: http
  behavior: domain
  url: "https://cdn.jsdelivr.net/gh/Loyalsoldier/clash-rules@release/direct.txt"
  path: ./providers/CN_DIRECT.yaml
  interval: 86400
 private:
  type: http
  behavior: domain
  url: "https://cdn.jsdelivr.net/gh/Loyalsoldier/clash-rules@release/private.txt"
  path: ./providers/private.yaml
  interval: 86400
 gfw:
  type: http
  behavior: domain
  url: "https://cdn.jsdelivr.net/gh/Loyalsoldier/clash-rules@release/gfw.txt"
  path: ./providers/gfw.yaml
  interval: 86400
 tld-not-cn:
  type: http
  behavior: domain
  url: "https://cdn.jsdelivr.net/gh/Loyalsoldier/clash-rules@release/tld-not-cn.txt"
  path: ./providers/tld-not-cn.yaml
  interval: 86400
 cncidr:
  type: http
  behavior: ipcidr
  url: "https://cdn.jsdelivr.net/gh/Loyalsoldier/clash-rules@release/cncidr.txt"
  path: ./providers/cncidr.yaml
  interval: 86400
 lancidr:
  type: http
  behavior: ipcidr
  url: "https://cdn.jsdelivr.net/gh/Loyalsoldier/clash-rules@release/lancidr.txt"
  path: ./providers/lancidr.yaml
  interval: 86400
# a-dove-is-dumb domains
 FuckAdobe:
  type: http
  behavior: classical
  url: "https://cdn.jsdelivr.net/gh/ignaciocastro/a-dove-is-dumb@main/clash.yaml"
  path: ./providers/FuckAdobe.yaml
  interval: 86400
# ios_rule_script platforms domains
 Niconico:
  type: http
  behavior: classical
  url: "https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Clash/Niconico/Niconico_No_Resolve.yaml"
  path: ./providers/Niconico.yaml
  interval: 86400
 Steam:
  type: http
  behavior: classical
  url: "https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Clash/Steam/Steam_No_Resolve.yaml"
  path: ./providers/Steam.yaml
  interval: 86400
 Paypal:
  type: http
  behavior: classical
  url: "https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Clash/PayPal/PayPal_No_Resolve.yaml"
  path: ./providers/PayPal.yaml
  interval: 86400
 Bahamut:
  type: http
  behavior: classical
  url: "https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Clash/Bahamut/Bahamut_No_Resolve.yaml"
  path: ./providers/Bahamut.yaml
  interval: 86400
 Apple:
  type: http
  behavior: classical
  url: "https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Clash/Apple/Apple_Classical_No_Resolve.yaml"
  path: ./providers/Apple.yaml
  interval: 86400
 Microsoft:
  type: http
  behavior: classical
  url: "https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Clash/Microsoft/Microsoft_No_Resolve.yaml"
  path: ./providers/Microsoft.yaml
  interval: 86400
 Spotify:
  type: http
  behavior: classical
  url: "https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Clash/Spotify/Spotify_No_Resolve.yaml"
  path: ./providers/Spotify.yaml
  interval: 86400
 BiliBili:
  type: http
  behavior: classical
  url: "https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Clash/BiliBili/BiliBili_No_Resolve.yaml"
  path: ./providers/BiliBili.yaml
  interval: 86400
 Youtube:
  type: http
  behavior: classical
  url: "https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Clash/YouTube/YouTube_No_Resolve.yaml"
  path: ./providers/Youtube.yaml
  interval: 86400
 Netflix:
  type: http
  behavior: classical
  url: "https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Clash/Netflix/Netflix_Classical_No_Resolve.yaml"
  path: ./providers/Netflix.yaml
  interval: 86400
 Amazon_Prime:
  type: http
  behavior: classical
  url: "https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Clash/AmazonPrimeVideo/AmazonPrimeVideo_No_Resolve.yaml"
  path: ./providers/Amazon_Prime.yaml
  interval: 86400
 Disney_Plus:
  type: http
  behavior: classical
  url: "https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Clash/Disney/Disney_No_Resolve.yaml"
  path: ./providers/Disney_Plus.yaml
  interval: 86400
 HBO:
  type: http
  behavior: classical
  url: "https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Clash/HBO/HBO_No_Resolve.yaml"
  path: ./providers/HBO.yaml
  interval: 86400
 Emby:
  type: http
  behavior: classical
  url: "https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Clash/Emby/Emby_No_Resolve.yaml"
  path: ./providers/Emby.yaml
  interval: 86400
 iQIYI:
  type: http
  behavior: classical
  url: "https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Clash/iQIYI/iQIYI_No_Resolve.yaml"
  path: ./providers/iQIYI.yaml
  interval: 86400
 Private_Tracker:
  type: http
  behavior: classical
  url: "https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Clash/PrivateTracker/PrivateTracker_No_Resolve.yaml"
  path: ./providers/Private_Tracker.yaml
  interval: 86400
# acl4ssr rules
 BanAD:
  type: http
  behavior: classical
  url: "https://cdn.jsdelivr.net/gh/ACL4SSR/ACL4SSR@master/Clash/Providers/BanAD.yaml"
  path: ./providers/BanAD.yaml
  interval: 86400
 China_Domain:
  type: http
  behavior: classical
  url: "https://cdn.jsdelivr.net/gh/ACL4SSR/ACL4SSR@master/Clash/Providers/ChinaDomain.yaml"
  path: ./providers/China_Domain.yaml
  interval: 86400
 China_IP:
  type: http
  behavior: ipcidr
  url: "https://cdn.jsdelivr.net/gh/ACL4SSR/ACL4SSR@master/Clash/Providers/ChinaIp.yaml"
  path: ./providers/China_IP.yaml
  interval: 86400
 China_IP6:
  type: http
  behavior: classical
  url: "https://cdn.jsdelivr.net/gh/ACL4SSR/ACL4SSR@master/Clash/Providers/ChinaIpV6.yaml"
  path: ./providers/China_IP6.yaml
  interval: 86400
# wacchi-lorie backup rules
 Steam_test:
  type: http
  behavior: classical
  url: "https://cdn.jsdelivr.net/gh/Wacchi-Lorie/clash-rules-backup@main/Steam_test.yaml"
  path: ./providers/Steam_test.yaml
  interval: 86400
 GamePlatform_domain:
  type: http
  behavior: domain
  url: "https://cdn.jsdelivr.net/gh/Wacchi-Lorie/clash-rules-backup/GamePlatform_domain.yaml"
  path: ./providers/GamePlatform_domain.yaml
  interval: 86400
 SocialAPP_domain:
  type: http
  behavior: domain
  url: "https://cdn.jsdelivr.net/gh/Wacchi-Lorie/clash-rules-backup@main/SocialAPP_domain.yaml"
  path: ./providers/SocialAPP_domain.yaml
  interval: 86400
 SocialAPP_ipcidr:
  type: http
  behavior: ipcidr
  url: "https://cdn.jsdelivr.net/gh/Wacchi-Lorie/clash-rules-backup@main/SocialAPP_ipcidr.yaml"
  path: ./providers/SocialAPP_ipcidr.yaml
  interval: 86400
 TAG_Exempt:
  type: http
  behavior: classical
  url: "https://cdn.jsdelivr.net/gh/Wacchi-Lorie/clash-rules-backup@main/tag_exempt.yaml"
  path: ./providers/TAG_Exempt.yaml
  interval: 86400
```