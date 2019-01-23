<br/>
<div align="center">

A curated list of awesome Java security-related resources.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

_List inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing._

Supported by: [GuardRails.io](https://www.guardrails.io)

</div>
<br/>

# Tools

## Web Framework Hardening

- [Apache Shiro](https://shiro.apache.org/) - A powerful and easy-to-use Java security framework that performs authentication, authorization, cryptography, and session management.
- [JJWT](https://github.com/jwtk/jjwt) - Java JWT: JSON Web Token for Java and Android.
- [OWASP ESAPI Java](https://github.com/ESAPI/esapi-java-legacy) - Enterprise Security API is a free, open source, web application security control library that makes it easier for programmers to write lower-risk applications.
- [PAC4J](https://github.com/pac4j/pac4j) - Security engine for Java to authenticate users, get their profiles and manage authorizations in order to secure web applications and web services.
- [Spring Security](https://github.com/spring-projects/spring-security) - A powerful and highly customizable authentication and access-control framework.
- [Spring Security Oauth](https://github.com/spring-projects/spring-security-oauth) - Support for adding OAuth1(a) and OAuth2 features (consumer and provider) for Spring web applications.

## Multi tools

- [hawkeye](https://github.com/hawkeyesec/scanner-cli) - Multi-purpose security/vulnerability/risk scanning tool supporting Ruby, Node.js, Python, PHP and Java.
- [GuardRails](https://github.com/apps/guardrails) - A GitHub App that gives you instant security feedback in your Pull Requests.

## Static Code Analysis

- [Spotbugs](https://github.com/spotbugs/spotbugs) - SpotBugs is FindBugs' successor. A tool for static analysis to look for bugs in Java code.
- [Find Security Bugs](https://github.com/find-sec-bugs/find-sec-bugs/) - SpotBugs plugin for security audits of Java web applications and Android applications.
- [Detect Secrets](https://libraries.io/pypi/detect-secrets) - An enterprise friendly way of detecting and preventing secrets in code.
- [Gitrob](https://github.com/michenriksen/gitrob) - Gitrob is a tool to help find potentially sensitive files pushed to public repositories on Github.
- [Sonarqube](https://github.com/SonarSource/sonarqube) - SonarQube provides the capability to show the health of an application and highlight newly introduced issues.

## Runtime Analysis

- [Code Pulse](https://github.com/codedx/codepulse) - Code Pulse is a real-time code coverage tool for penetration testing activities.
- [OWASP ZAP](https://github.com/zaproxy/zaproxy) -  Helps automatically find security vulnerabilities in your web applications.

## Vulnerabilities and Security Advisories

- [OWASP Dependency-Check](https://github.com/jeremylong/DependencyCheck) - Detects publicly disclosed vulnerabilities in application dependencies.
- [Snyk](https://github.com/snyk/snyk) - CLI and build-time tool to find & fix known vulnerabilities in open-source dependencies.
- [Snyk Vulnerability DB](https://snyk.io/vuln?type=maven) - Commercial but free listing of known vulnerabilities in libraries.
- [Common Vulnerabilities and Exposures](https://www.cvedetails.com/product/19117/Oracle-JRE.html?vendor_id=93) - Vulnerabilities that were assigned a CVE. Covers the language and packages.
- [National Vulnerability Database](https://nvd.nist.gov/vuln/search/results?form_type=Basic&results_type=overview&query=java&search_type=all) - Java known vulnerabilities in the National Vulnerability Database.

## Cryptography

- [Bouncy Castle](https://www.bouncycastle.org/java.html) - Java implementation of cryptographic algorithms.
- [Conscrypt](https://github.com/google/conscrypt) - Java Security Provider that implements parts of the Java Cryptography Extension and Java Secure Socket Extension.
- [Cryptomator](https://github.com/cryptomator/cryptomator) - Multi-platform transparent client-side encryption of your files in the cloud.
- [Keyczar](https://github.com/google/keyczar) - Easy-to-use crypto toolkit by Google.
- [Keywhiz](https://github.com/square/keywhiz) - System for distributing and managing secrets.
- [Tink](https://github.com/google/tink) - Multi-language, cross-platform library that provides cryptographic APIs that are secure, easy to use correctly, and hard(er) to misuse.

# Educational

## Hacking Playground

- [BodgeIt Store](https://github.com/psiinon/bodgeit) - A vulnerable web application aimed at people who are new to pen testing.
- [OWASP Benchmark](https://github.com/OWASP/Benchmark) - A Java test suite designed to verify the speed and accuracy of vulnerability detection tools.
- [Security Shepherd](https://github.com/OWASP/SecurityShepherd) - Web and mobile application security training platform.
- [WebGoat](https://github.com/WebGoat/WebGoat) - A deliberately insecure Java Web Application.

## Articles, Guides & Talks

- [Java Platform, Standard Edition Security Developer’s Guide](https://docs.oracle.com/javase/10/security/toc.htm) - This guide covers major Java Standard Edition security components: Java Cryptography Architecture (JCA), Java Authentication and Authorization Service (JAAS) and Java Secure Socket Extensions (JSSE)
- [Application Security Verification Standard](https://www.owasp.org/images/3/33/OWASP_Application_Security_Verification_Standard_3.0.1.pdf) - (PDF) The standard is a list of application security requirements that can be used by developers.
- [Spring Security CSRF](https://www.baeldung.com/spring-security-csrf) - A Guide to CSRF Protection in Spring Security.
- [Secure Coding Guidelines](https://www.oracle.com/technetwork/java/seccodeguide-139067.html) - Secure Coding Guidelines for Java SE
- [Securing a Web Application](https://spring.io/guides/gs/securing-web/) - This guide walks you through the process of creating a simple web application with resources that are protected by Spring Security.
- [Spring Security Guides](https://docs.spring.io/spring-security/site/docs/current/guides/html5/index.html) - Step by step guides on how to use Spring Security.
- [Prevent cross-site scripting (XSS) attacks](https://www.ibm.com/developerworks/library/se-prevent-cross-site-scripting-attacks/index.html) - This guide explains how XSS attacks work and suggests a methodoloy to block XSS attacks.

## Specifications

- [JSR 115: Java Authorization Contract for Containers](https://jcp.org/en/jsr/detail?id=115)
- [JSR 196: Java Authentication Service Provider Interface for Containers](https://www.jcp.org/en/jsr/detail?id=196)
- [JSR 375: Java EE Security API](https://jcp.org/en/jsr/detail?id=375)

# Other

## Reporting Bugs

- [Java Security Reporting](https://www.oracle.com/corporate/security-practices/assurance/vulnerability/reporting.html)

# Contributing

Found an awesome project, package, article, or another type of resources related to Java Security? Open a pull request!
Just follow the [guidelines](/CONTRIBUTING.MD). Thank you!

---

say _hi_ on [Twitter](https://twitter.com/s_streichsbier)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
