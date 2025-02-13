---
title: 'Usage Information'
description: 'Non-sensitive and anonymous usage information'
position: 1200
category: 'Product'
menuTitle: 'Usage Information'
---

<announcement></announcement>

NocoDB is a fast growing open source project which is UI heavy and we are committed to providing a solution that exceeds the expectations of the users and community.
We are also committed to continuing to develop and make NocoDB even better than it is today.
To that end, NocoDB contains a feature in which anonymous and otherwise non-sensitive data is collected.
This anonymous and non-sensitive data gives a better understanding of how users are interacting and using the product.

## Context
We will always continue to do hands-on UI/UX testing, surveys, issue tracking and roadmap.
Otherwise talk with the Community while striving to understand
and deliver what is being asked for and what is needed, by any means available.

However, these above actions alone are often insufficient
- To maintain an overall picture of the product usage.
- Prioritising the efforts.
- Impact of any breaking changes.
- To understand whether UI improvements are helpful to users.

## What we collect ?
We collect actions made on models (project, table, view, sharedView, user, hook, image, sharedBase etc) periodically with :
- System information (OS, node version, docker or npm)
- Environment (dev, staging, production)
- Instance information (Unique machine ID, database type, count of projects and users)
- Failures.



Our UI Dashboard is a Vuejs-Nuxtjs app. Actions taken on UI with completely anonymized route names are sent as payload.



## What we DO NOT collect ?
We do not collect any private or sensitive information, such as:
- Personally identifiable information
- Credential information (endpoints, ports, DB connections, username/password)
- Database/User data


## Opt-out
To disable usage information collection please set following environment variable.
> NC_DISABLE_TELE=true
