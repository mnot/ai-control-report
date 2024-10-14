---
title: "IAB AI-CONTROL Workshop Report"
category: info

docname: draft-nottingham-ai-control-report-latest
submissiontype: IAB
number:
date:
consensus: true
v: 3
keyword:
 - policy
 - Artificial Intelligence
 - robots.txt

author:
 -
    ins: M. Nottingham
    name: Mark Nottingham
    organization: Cloudflare
    postal:
      - Prahran
    country: Australia
    email: mnot@mnot.net
    uri: https://www.mnot.net/
 -
    ins: S. Krishnan
    name: Suresh Krishnan
    organization: Cisco
    email: suresh.krishnan@gmail.com

normative:

informative:

  CHATHAM-HOUSE:
    title: Chatham House Rule
    target: https://www.chathamhouse.org/about-us/chatham-house-rule
    author:
      -
        org: Chatham House

  CFP:
    title: IAB Workshop on AI-CONTROL
    target: https://datatracker.ietf.org/group/aicontrolws/about/
    author:
      -
        org: Internet Architecture Board


--- abstract

The AI-CONTROL Workshop was convened by the Internet Architecture Board (IAB) in September 2024. This report summarizes its significant points of discussion and identifies topics that may warrant further consideration.

Note that this document is a report on the proceedings of the workshop. The views and positions documented in this report are those of the workshop participants and do not necessarily reflect IAB views and positions.


--- middle

# Introduction

The Internet Architecture Board (IAB) holds occasional workshops designed to consider long-term issues and strategies for the Internet, and to suggest future directions for the Internet architecture. This long-term planning function of the IAB is complementary to the ongoing engineering efforts performed by working groups of the Internet Engineering Task Force (IETF).

The IAB convened the AI-CONTROL Workshop to "explore practical opt-out mechanisms for AI and build an understanding of use cases, requirements, and other considerations in this space." {{CFP}} In particular, the emerging practice of using the Robots Exclusion Protocol {{RFC9309}} -- also known as "robots.txt" --


## Chatham House Rule

Participants agreed to conduct the workshop under the Chatham House Rule {{CHATHAM-HOUSE}}, so this report does not attribute statements to individuals or organizations without express permission. Most submissions to the workshop were public and thus attributable; they are used here to provide substance and context.

{{attendees}} lists the workshop participants, unless they requested that this information be witheld.

# Overview

# Attachment

# Vocabulary

# Potential Future Work


# Security Considerations

_TODO_



--- back


# About the Workshop

The AI-CONTROl Workshop was held on 2024-09-19 and 2024-09-29 at Wilkinson Barker Knauer in Washington DC, USA.

Workshop attendees were asked to submit position papers. These papers are published on the IAB website [CFP], unless the submitter requested it be withheld.

The workshop was conducted under the Chatham House Rule [CHATHAM-HOUSE], meaning that statements cannot be attributed to individuals or organizations without explicit authorization.

## Agenda

This section outlines the broad areas of discussion on each day.

### Thursday 2024-09-19

Setting the stage
: An overview of the current state of AI opt-out, its impact, and existing work in this space

Lightning talks
: A variety of perspectives from participants

### Friday 2024-09-20

Out Out Attachment: robots.txt and beyond
: Considerations in how policy is attached to content on the Internet

Vocabulary: what opt out means
: What information the opt out signal needs to convey

Discussion and wrap-up
: Synthesis of the workshop's topics and how future work might unfold

## Attendees {#attendees}

Attendees of the workshop are listed with their primary affiliation. Attendees from the program committee (PC) and the Internet Architecture Board (IAB) are also marked.

* Jari Arkko, Ericsson
* Hirochika Asai, Preferred Networks
* Farzaneh Badiei, Digital Medusa (PC)
* Fabrice Canel, Microsoft (PC)
* Lena Cohen, EFF
* Alissa Cooper, Knight-Georgetown Institute (PC, IAB)
* Marwan Fayed, Cloudflare
* Christopher Flammang, Elsevier
* Carl Gahnberg
* Max Gendler, The News Corporation
* Ted Hardie
* Dominique Hazaël-Massieux, W3C
* Gary Ilyes, Google (PC)
* Sarah Jennings, UK Department for Science, Innovation and Technology
* Paul Keller, Open Future
* Elizabeth Kendall, Meta
* Suresh Krishnan, Cisco (PC, IAB)
* Mirja Kühlewind, Ericsson (PC, IAB)
* Greg Leppert, Berkman Klein Center
* Greg Lindahl, Common Crawl Foundation
* Mike Linksvayer, GitHub
* Fred von Lohmann, OpenAI
* Shayne Longpre, Data Provenance Initiative
* Don Marti, Raptive
* Sarah McKenna, Alliance for Responsible Data Collection; CEO, Sequentum
* Eric Null, Center for Democracy and Technology
* Chris Needham, BBC
* Mark Nottingham, Cloudflare (PC)
* Paul Ohm, Georgetown Law (PC)
* Braxton Perkins, NBC Universal
* Chris Petrillo, Wikimedia
* Sebastian Posth, Liccium
* Michael Prorock
* Matt Rogerson, Financial Times
* Peter Santhanam, IBM
* Jeffrey Sedlik, IPTC/PLUS
* Rony Shalit, Alliance For Responsible Data Collection; Bright Data
* Ian Sohl, OpenAI
* Martin Thomson, Mozilla
* Thom Vaughan, Common Crawl Foundation (PC)
* Kat Walsh, Creative Commons
* James Whymark, Meta

The following participants requested that their identity and/or affiliation not be revealed:

* A government official


# IAB Members at the Time of Approval
{:numbered="false"}

Internet Architecture Board members at the time this document was approved for publication were:

_TBC_


# Acknowledgements
{:numbered="false"}

The Program Committee and the IAB would like to thank Wilkinson Barker Knauer for their generosity in hosting the workshop.

We also thank our scribes for capturing notes that assisted in production of this report:

* Zander Arnao
* Andrea Dean
* Patrick Yurky
