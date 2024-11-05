# Streamlined-Security-Cloud-Armor-Preconfigured-Web-Application-Firewall-Rules

## Overview
In this project, I work with Google Cloud Armor, Google’s enterprise edge network security solution that provides DDoS protection, WAF rule enforcement, and adaptive manageability at scale. Cloud Armor has enhanced its preconfigured WAF rule sets to mitigate against the OWASP Top 10 web application security vulnerabilities. These rule sets are based on the OWASP ModSecurity Core Rule Set version 3.0.2, helping protect against common web application security risks, including local file inclusion (LFI), remote file inclusion (RFI), remote code execution (RCE), and more. Through this project, I will mitigate some of these vulnerabilities by applying Google Cloud Armor WAF rules.

## Objectives
In this Project, I will:
Set up an Instance Group and a Global Load Balancer to support a service.
Configure Cloud Armor security policies with preconfigured WAF rules to protect against LFI, RCE, scanners, protocol attacks, and session fixation.
Validate that Cloud Armor mitigated an attack by observing logs.

I’ll use the OWASP Juice Shop application, which is valuable for security training and awareness as it contains instances of each of the OWASP Top 10 security vulnerabilities—intentionally designed for testing purposes. I’ll simulate some application attacks and then protect the application with Cloud Armor WAF rules. The application, fronted by a Google Cloud Load Balancer with Cloud Armor security policies and rules, is accessible on the public internet and protected using Cloud Armor and VPC firewall rules.
