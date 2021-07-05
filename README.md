<mark>*Templates and Config files for advanced application security with NGINX App Protect*</mark>

| NGINX App Protect                                                                                                            | NGINX App Protect + (Threat Campaigns, Bot Detection, L7 DoS)                                                                                                                          |
|-                                                                                                                             |-                                                                                                                                                                                       |
| - Signatures  <br><br><br><br><br> [nginx.conf](configs/waf-nginx.conf) <br> [policy.json](policies/nap_policy_waf.json)     | - Signatures <br> - Threat Campaigns <br> - Bot Defence <br> - L7 DoS <br><br> [nginx.conf](configs/waf_tc_bot_dos-nginx.conf) <br> [policy.json](configs/waf_tc_bot_dos-nginx.conf)   |

<br>
<br>

<mark>*Templates and Config files for integrating Shape Security with NGINX App Protect*</mark>

| NGINX App Protect + DeviceID+                                                                                                | NGINX App Protect + Shape Enterprise Defence                                                                                                                           |
|-                                                                                                                             |-                                                                                                                                                                                       |
| - Signatures <br> - Device Identification <br><br><br> [nginx.conf](configs/waf-nginx.conf) <br> [policy.json](policies/nap_policy_waf.json)     | - Signatures <br> - Advanced Fraud Mitigation <br> - Account Takeover Protection <br> - Credential Stuffing Protection <br><br> [nginx.conf](configs/waf_tc_bot_dos-nginx.conf) <br> [policy.json](configs/waf_tc_bot_dos-nginx.conf)   |