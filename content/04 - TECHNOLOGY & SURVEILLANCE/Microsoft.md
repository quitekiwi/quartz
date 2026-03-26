# Microsoft

#verified #credible #theory

**Folder:** 04 - TECHNOLOGY & SURVEILLANCE
**Source note:** [[SRC - Microsoft]]

---

## Why Microsoft Is Different

Every other platform in this vault 
sits on top of your device. 
Microsoft is the device.

Windows runs on approximately 
72% of the world's desktop and 
laptop computers. The surveillance 
layer is not an app you can delete. 
It is the foundation the entire 
system runs on. You cannot 
uninstall the operating system 
to protect your privacy — 
you would have no operating system.

This is a structurally different 
problem from Meta or Google. 
Those companies track what you do 
on their platforms. Microsoft tracks 
what you do on your computer. 
All of it. #verified

---

## The Telemetry System

Microsoft categorises its data 
collection into two buckets: 
Required and Optional.

**Required diagnostic data** — 
collected regardless of user 
preference on Windows Home 
and Pro editions — includes: #verified
- Device identifiers
- Hardware and OS configuration
- Network configuration details
- App installation records
- System stability and error reports
- Update and installation records
- Connected peripherals and drivers
- Authentication and licensing data

This cannot be turned off on 
consumer editions of Windows. 
Enterprise editions have more 
granular control. 
The average person running 
Windows at home has no 
supported way to fully 
disable required telemetry. #verified

**The transparency problem:**
Microsoft publishes a Diagnostic 
Data Viewer tool that lets users 
see what is being collected. 
Security researchers have noted 
this tool shows a fraction of 
what is actually transmitted — 
the full dataset is encrypted 
and inaccessible to anyone 
outside Microsoft. 
At one point Microsoft published 
a more complete list of what 
was being collected. 
They removed it. #credible

The telemetry service is called 
DiagTrack — Connected User 
Experiences and Telemetry. 
It collects application usage, 
system performance, error reports, 
and behavioural patterns. 
It is documented that even when 
users disable it through 
registry edits or third party 
tools, it tends to re-enable 
itself after Windows updates. 
#credible

---

## Microsoft Recall — The Most 
## Important Privacy Story in Tech

In May 2024 Microsoft announced 
a feature called Recall as part 
of its Copilot+ AI integration 
into Windows 11.

**What Recall does:**
Takes a screenshot of everything 
on your screen every few seconds. 
Processes each screenshot with 
on-device AI. Stores the results 
in a searchable database going 
back three months. Allows you 
to search your entire computing 
history in natural language — 
"find the PDF I was reading about 
geoengineering last Tuesday." #verified

**The initial version:**
- Enabled by default. 
  No opt-in required.
- Database stored unencrypted 
  in plaintext — including 
  passwords, credit card numbers, 
  private messages, banking data.
- No content moderation — 
  everything captured, 
  nothing filtered.
- Ethical hacker Alexander Hagenah 
  developed a tool called 
  TotalRecall within days of 
  announcement that could extract 
  and display the entire database. 
  #verified

Jeff Pollard, Vice President 
and Principal Analyst at Forrester: 
"I think a built-in keylogger 
and screenshotter that perfectly 
captures everything you do on 
the machine is a tremendous 
privacy nightmare." #verified

The UK Information Commissioner's 
Office wrote to Microsoft formally 
to understand what safeguards 
were in place. Microsoft declined 
to comment on security concerns. 
#verified

**What happened next:**
Microsoft pulled the feature after 
the backlash. Spent a year 
rebuilding it. Relaunched 
in April 2025 for Windows Insider 
testers with changes:
- Now opt-in (not default)
- Database encrypted with BitLocker
- Biometric authentication required 
  to access snapshots
- Sensitive data filter added 
  (passwords, credit card numbers)
- Data stated to be stored locally — 
  not sent to Microsoft servers

**What remains concerning:** #credible
- Experts warn the system 
  undermines encrypted apps — 
  Signal, WhatsApp, iMessage — 
  by capturing what appears 
  on screen before encryption 
  can protect it.
- A person you are messaging who 
  has Recall enabled will have 
  your messages captured 
  in their database — 
  without your knowledge or consent.
- Cybersecurity experts demonstrated 
  that guessing the PIN gives 
  full access to all content — 
  deleted or not.
- Signal responded by making 
  its Windows app produce a 
  black screen on screenshots — 
  the only defence available 
  because Microsoft does not 
  give developers better options 
  to protect their content 
  from Recall.
- Currently rolling out to 
  Copilot+ PCs only — 
  less than 2% of Windows laptops 
  as of early 2025. 
  This will not remain the case. 
  #investigate

**The pattern this fits:**
A feature that records everything 
on your screen is launched 
enabled by default with an 
unencrypted database. 
When caught it is pulled, 
hardened, and relaunched 
as opt-in. The architecture 
of total screen surveillance 
is built, tested, and normalised. 
The direction of travel is clear. 
See [[The Pattern of Revelation]]

---

## The Broader Microsoft Ecosystem

Microsoft's data collection 
extends well beyond Windows:

**Microsoft 365 / Office:**
Every document, email, and 
spreadsheet you create in 
Word, Excel, or Outlook 
generates telemetry. 
Content is processed for 
AI features. 
For professionals handling 
confidential client data — 
legal, medical, financial — 
the implications of OS-level 
and application-level telemetry 
running simultaneously on 
the same machine are significant. 
#credible

**LinkedIn:**
Owned by Microsoft since 2016. 
Contains professional identity, 
employment history, salary 
expectations, career aspirations, 
and relationship maps of 
professional networks for 
over one billion people. 
Cross-referenced with Microsoft 
account data this creates 
a professional and personal 
profile of significant depth. 
#verified

**Xbox / Gaming:**
Tracks gameplay patterns, 
voice communications, 
spending behaviour, 
and social connections 
across gaming networks. 
#verified

**Azure / OpenAI:**
Microsoft is the primary investor 
in OpenAI. Every interaction 
with ChatGPT and the Azure 
AI ecosystem passes through 
Microsoft infrastructure. 
The full data retention and 
usage policies for AI 
interactions at scale are 
not publicly disclosed. 
#investigate

---

## The Honest Assessment

Microsoft is the platform that 
most people think least about 
from a privacy perspective — 
because it is the infrastructure, 
not the app. It is invisible 
in the way foundations are invisible.

The telemetry runs below everything. 
The Recall feature, if fully deployed, 
would create a photographic memory 
of every document opened, 
every message read, every website 
visited, every private conversation 
held on screen — on the device 
of over a billion users.

This is not speculation. 
This is a described, announced, 
partially deployed feature 
from the company that runs 
the operating system of 
most of the world's computers.

[[I. The Observer]] notes: 
the most dangerous surveillance 
is the surveillance that is 
so foundational it becomes 
part of the environment — 
invisible, assumed, accepted.

---

## Practical Steps

- Use Firefox with uBlock Origin 
  for all browsing on Windows — 
  it kills the tracking layer 
  that Chrome enables
- Use O&O ShutUp10++ — 
  free tool that provides 
  granular control over 
  Windows privacy settings 
  beyond what Settings allows
- Do NOT enable Recall 
  when prompted. 
  If already enabled: 
  Settings → Privacy & Security 
  → Recall & Snapshots → 
  toggle off Save Snapshots → 
  Delete existing snapshots
- For maximum privacy on a 
  desktop or laptop: 
  Linux (Ubuntu, Fedora) 
  collects minimal telemetry 
  by default and asks 
  before sending anything. 
  Requires technical comfort.
- See [[Digital Privacy & Protection]]

---

## Linked Notes

[[Surveillance Capitalism]] · 
[[The Managed World]] · 
[[The Planetary Nervous System]] · 
[[The Pattern of Revelation]] · 
[[Apple]] · [[Google & Alphabet]] · 
[[Digital Privacy & Protection]] · 
[[I. The Observer]] · 
[[SRC - Microsoft]]
