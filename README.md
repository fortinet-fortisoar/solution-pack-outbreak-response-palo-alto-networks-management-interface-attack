# Release Information 

- **Version**: 1.0.0 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR 7.4.0 and later 

# Overview 

Palo Alto Networks has recently disclosed two zero-day vulnerabilities, CVE-2024-0012 and CVE-2024-9474, affecting the PAN-OS firewall and other products. Both flaws, which are actively being exploited in the wild, affect the Management Web Interface. Successful exploitations allows attackers to bypass authentication and gain administrator-level access without any user interaction. 

 The **Outbreak Response - Palo Alto Networks Management Interface Attack** solution pack works with the Threat Hunt rules in [Outbreak Response Framework](https://github.com/fortinet-fortisoar/solution-pack-outbreak-response-framework/blob/release/2.0.0/docs/background-information.md#threat-hunt-rules) solution pack to conduct hunts that identify and help investigate potential Indicators of Compromise (IOCs) associated with this vulnerability within operational environments of *FortiSIEM*, *FortiAnalyzer*, *QRadar*, *Splunk*, and *Azure Log Analytics*.

 The [FortiGuard Outbreak Page](https://www.fortiguard.com/outbreak-alert/pan-os-management-interface-attack) contains information about the outbreak alert **Outbreak Response - Palo Alto Networks Management Interface Attack**. 

## Background: 

Palo Alto Networks PAN-OS Management Interface OS Command Injection Vulnerability (CVE-2024-9474) is an OS command injection vulnerability that allows for privilege escalation through the web-based management interface for several PAN products, including firewalls and VPN concentrators.

Palo Alto Networks PAN-OS Management Interface Authentication Bypass Vulnerability (CVE-2024-0012) is an authentication bypass vulnerability in the web-based management interface for several PAN-OS products, including firewalls and VPN concentrators. 

## Announced: 

 

## Latest Developments: 

November 18, 2024: CISA Added both the vulnerabilites to Known Exploited Vulnerabilities Catalog (KEV.)
https://www.cisa.gov/known-exploited-vulnerabilities-catalog

November 18, 2024: Palo Alto Networks published PAN-OS Management Interface OS Command Injection Vulnerability (CVE-2024-9474).
https://security.paloaltonetworks.com/CVE-2024-9474

November 8, 2024: Palo Alto Networks published Authentication Bypass in the Management Web Interface (CVE-2024-0012).
https://security.paloaltonetworks.com/CVE-2024-0012 

# Next Steps
 | [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) | 
 |--------------------------------------------|----------------------------------------------|------------------------|------------------------------|