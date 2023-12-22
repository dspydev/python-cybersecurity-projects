# DNS Lookup Tool

This project contains a DNS lookup tool implemented in Python. The tool performs DNS lookups for a given domain and a list of record types.

## Project Description

In the realm of cybersecurity, understanding the DNS (Domain Name System) records associated with a domain can provide valuable insights. These records can reveal the IP addresses associated with a domain (A and AAAA records), mail servers (MX records), text records often used for configuration settings (TXT records), and more.

This DNS Lookup Tool is designed to fetch and display these records, providing a simple way to perform DNS lookups. It can be a valuable asset for cybersecurity audits, network troubleshooting, or even competitive analysis.

## Practical Applications

For businesses, this tool can serve multiple purposes:

1. **Cybersecurity Audits**: By examining DNS records, businesses can identify potential vulnerabilities or misconfigurations in their network infrastructure.
2. **Network Troubleshooting**: DNS records are often the first place to look when diagnosing network connectivity issues.
3. **Competitive Analysis**: Businesses can use DNS lookups to gather intelligence about competitors' network infrastructures.

## Usage

The tool is straightforward to use. Simply specify the target domain and the DNS record types you're interested in, and the tool will print out the corresponding records.

Here's an example usage:

```python
target_domain = "example.com"
record_types = ["A", "AAAA", "CNAME", "MX", "NS", "SOA", "TXT"]

dns_lookup(target_domain, record_types)
