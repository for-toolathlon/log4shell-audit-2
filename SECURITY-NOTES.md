# Log4Shell Security Notes

## Core facts

- **Vulnerability:** Log4Shell — remote code execution in Apache Log4j 2 via JNDI lookups
- **CVE ID:** CVE-2021-44228
- **CVSS 3.1 score:** 10.0 CRITICAL (CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:C/C:H/I:H/A:H)
- **Affected versions:** 2.0-beta9 through 2.14.1 (inclusive)
- **Fixed versions:** 2.3.1 (Java 6), 2.12.2 (Java 7), 2.15.0 (Java 8 and later)
  - CISA recommends 2.16.0 if possible (2.17.1 for Java 8), 2.12.4 for Java 7, 2.3.2 for Java 6
- **CVSS-able:** Arbitrary code execution, always exploitable over the network with no authentication

## Sources

- Apache Logging Services security page: https://logging.apache.org/security.html
- CISA Apache Log4j Vulnerability Guidance: https://www.cisa.gov/news-events/news/apache-log4j-vulnerability-guidance
- CVE-2021-44228 record: https://www.cve.org/CVERecord?id=CVE-2021-44228
- SLF4J advisory: https://www.slf4j.org/log4shell.html
- Datadog Security Labs: https://securitylabs.datadoghq.com/articles/log4j-log4shell-vulnerability-overview-and-remediation/
