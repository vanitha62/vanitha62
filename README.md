# nmap -Pn testing.pinewheel.ai
gobuster dir -u https://testing.pinewheel.ai -w /usr/share/wordlists/dirb/common.txt
whatweb testing.pinewheel.ai
sqlmap -u "https://testing.pinewheel.ai/endpoint" --data="param=value" 
<script>alert('XSS')</script>
nikto -h https://testing.pinewheel.ai
nmap -Pn testing.pinewheel.ai
