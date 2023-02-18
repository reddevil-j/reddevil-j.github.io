---
title: "You shall not pass: Mitigating SQL Injection Attacks on Legacy Web Applications"
collection: publications
permalink: /publication/2020-10-5-sqlblock
excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2020-10-5
venue: 'AsiaCSS'
paperurl: 'https://dl.acm.org/doi/pdf/10.1145/3320269.3384760'
citation: 'R Jahanshahi, A Doupe, and M Egele. You shall not pass: Mitigating SQL Injection Attacks on Legacy Web Applications. Proceedings of Asia conference on computer and communications security (Asia CCS). 2020'
---
SQL injection (SQLi) attacks pose a significant threat to the security of web applications. Existing approaches do not support object-oriented programming that renders these approaches unable to protect the real-world web apps such as Wordpress, Joomla, or Drupal against SQLi attacks.

We propose a novel hybrid static-dynamic analysis for PHP web applications that limits each PHP function for accessing the database. Our tool, SQLBlock, reduces the attack surface of the vulnerable PHP functions in a web application to a set of query descriptors that demonstrate the benign functionality of the PHP function.

We implement SQLBlock as a plugin for MySQL and PHP. Our approach does not require any modification to the web app. We evaluate SQLBlock on 11 SQLi vulnerabilities in Wordpress, Joomla, Drupal, Magento, and their plugins. We demonstrate that SQLBlock successfully prevents all 11 SQLi exploits with negligible performance overhead (i.e., a maximum of 3% on a heavily-loaded web server).
[Download paper here](https://dl.acm.org/doi/pdf/10.1145/3320269.3384760)

Recommended citation: **R Jahanshahi**, A Doupe, and M Egele. You shall not pass: Mitigating SQL Injection Attacks on Legacy Web Applications. Proceedings of Asia conference on computer and communications security (Asia CCS). 2020