<mark>*Templates and Config files for application security with NGINX App Protect*</mark>

| NGINX App Protect (Signatures only)                                                                                          | NGINX App Protect  (Bot Defence only)                                                                |  NGINX App Protect (L7 DoS only)                                                                                              |
|-                                                                                                                             |-                                                                                                     | -                                                                                                                             |
| - Signatures  <br><br> [nginx.conf](configs/waf-nginx.conf) <br> [policy.json](policies/nap_policy_waf.json)     | - Bot Defence <br><br> [nginx.conf](configs/bot-nginx.conf) <br> [policy.json](policies/nap_policy_bot.json)     | - L7 DoS <br><br> [nginx.conf](configs/dos-nginx.conf) <br> [policy.json](policies/nap_policy_dos.json)                       |


<mark>*Templates and Config files for comprehensive application security with NGINX App Protect*</mark>

| NGINX App Protect + (Threat Campaigns, Bot Detection, L7 DoS)                                                                                                                          |
|-                                                                                                                                                                                       |
| - Signatures <br> - Threat Campaigns <br> - Bot Defence <br> - L7 DoS <br><br> [nginx.conf](configs/waf_tc_bot_dos-nginx.conf) <br> [policy.json](configs/nap_policy_tc_bot_dos.json)   |

<br>
<br>

<mark>*Templates and Config files for integrating Shape Security with NGINX App Protect*</mark>

| NGINX App Protect + DeviceID+                                                                                                                    |
|-                                                                                                                                                 |
| - Signatures <br> - Device Identification <br><br><br> [nginx.conf](configs/waf-nginx.conf) <br> [policy.json](policies/nap_policy_waf.json)     |
