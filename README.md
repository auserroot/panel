use cloudflare pages create owner vpn sub
create a pages setting those variables

UUID：enter an UUID
PROXYIP：Fill in the proxy IP address, which can be obtained from a random proxy IP site, or use a preferred domain name（et. cdn-b100.xn--b6gac.eu.org）
TR_PASS：password

Create KV: Click Storage & Database on the left, select KV, and create a new KV namespace

Bind KV: Go back to the created Pages screen. Click Settings -> [Binding], click Add, and select Add KV namespace

Note: The variable name can only be filled with "kv" (lowercase)

Retry the deployment

over success enter you host https://xxxx/panel


Configure BPB panel parameters
FakeDNS: set enable

Proxy IPs / Domains: Enter the IP or domain name, and PROXYIP to get the address: click to access

Clean IPs / Domains: Excellent IP Software Download [Click below to Download Scanner] | Online Preferred IP: Click to visit

TLS port: You need to use the port by ticking the box, the default is port 443

ROUTING RULES:Bypass xxx refers to xxx does not go through a proxy (direct connection) | Block xxx means that xxx is blocked (unreachable)

Bypass LAN: bypasses the local area network

Block Ads: Blocks ad URLs

Bypass Iran: Bypass Iran

Block Porn: Blocks color websites

Bypass China: Bypass Chinese mainland

Block QUIC: shields the QUIC protocol

Bypass Russia: Bypass Russia

CUSTOM RULES: In addition to the preset rules above, you can customize some IP addresses/websites that require direct connection (Bypass) and Block (Block) here.

Save the settings
CLICK APPLY SETTINGS TO SAVE THE BPB PANEL CONFIGURATION
