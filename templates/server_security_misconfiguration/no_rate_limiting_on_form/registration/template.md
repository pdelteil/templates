# No Rate Limiting on Registration 

## Overview

<!--
Provide a 1-2 sentence description - see http://cveproject.github.io/docs/content/key-details-phrasing.pdf for tips

This format is a good guide:
[VULNTYPE] in [COMPONENT] in [APPLICATION] allows [ATTACKER] to [IMPACT] via [VECTOR] 
-->

Rate Limiting is a measure used by applications to prevent spam attacks or brute forcing.

A lack of a Rate Limiting in {{target}} allows a malicious attacker to brute force or spam an application/functionality.

## Walkthrough & PoC

<!--
Provide a step-by-step walkthrough on how to access the vulnerable injection point, and how to exploit the vulnerability.

Adding a dot-pointed walkthrough with relevant screenshots will speed triage time and result in faster rewards!
-->

1. Navigate to the following URL:

{{value}}

1. Fill in the form to register and intercept in a Web Proxy


1. Use {{program}} (Up to 10 requests) to launch a spam attack 

## Vulnerability Evidence

<!--
Your submission MUST include evidence of the vulnerability and not be theoretical in nature.
-->

The image(s) below demonstrates the lack of rate limiting on the registration functionality:

{{screenshot}}

## Demonstrated Impact

<!--
Provide a full Proof of Concept here.
--> 

This will allow an attacker to generate multiple spam accounts on the website, and squat usernames on the website, preventing legitmate users from joining.