==========
Pentesting
==========

What's pentesting? 
==================

* Legally searching a system for security vulnerabilities

.. figure:: _static/whitehat_blackhat.jpg
    :align: center

Getting into the industry
=========================

|

.. figure:: _static/hacker.jpg
    :align: center
    :scale: 50%

* Often background in black-hat work
* Certifications/degrees can help; experience counts most

Pentesting Clients
==================

* Anyone whose systems might be attacked
    * Banking
    * e-commerce
    * Governments
    * Corporations
    * Military


How can pentesting be done legally?
===================================

* Contract with owner of system
    * Legal consent to find vulnerabilities
    * Clear explanation of what may be done with discovered problems
    * Avoid breaking laws about disclosing sensitive data

Acceptable Use Policies
=======================

**Authorized Use**

.. figure:: _static/osu_aup.png
    :align: center

Tools & Techniques
==================

Metasploit
----------

* Metasploit framework
* Free & Open Source
* Includes anti-forensic and evasion tools
* Choose exploit, encoding, and payload, then execute
  
.. figure:: metasploit_logo.png
    :align: center

nmap
----

* Network sweeps
* network tracing
* port scans
* OS fingerprinting
* version scans
* vulnerability scans

Nessus
------

* Proprietary, integrated vulnerability scanner
* 2.2.11 and before were GPL
* Misconfiguration, DoS with mangled packets, default passwords, PCI DSS audit
    * (Payment Card Industry Data Security Standard)

.. figure:: _static/nessus.png
    :align: center

Wireshark
---------

* Unsecured access points

Social engineering
------------------

.. figure:: _static/kid_dressed_as_pilot.jpg
    :align: right
    :scale: 60%

* Pretexting
* Phishing
* Baiting
    * Stuxnet
* Quid pro quo
* Tailgaiting

Vulnerabilities
===============

* SQL injection
* XSS
* JS injection

Privilege escalation
--------------------

Known, unpatched vulnerabilities
--------------------------------

Clueless (l)Users
-----------------

* Password reuse


Ethical Issues
==============

* Disclosing user data
* Discovering confidential data
* Appropriate disclosure if client doesn't fix vulnerabilities
    * Unfixed problems can endanger client's users
* Destructive vs. non-destructive testing
    * DoS attacks impact users, but would be available to malicious intruders

What results might be found? 
============================

.. note:: 
    Who would discover that a vulnerability had been exploited? (pentester, DBA, sysadmins, etc.)

    How would the pentester's results be presented?

    What actions would be taken by the company as a result?


