---
title: | 
  What Happens After You Leak Your Password: Understanding Credential Sharing on Phishing Sites

publication: AsiaCCS 2019
# event_url: https://example.org

# location: Wowchemy HQ
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

summary: "Phishing has been a big concern due to its active roles in recent data breaches and state-sponsored attacks. While existing works have extensively analyzed phishing websites and their operations, there is still a limited understanding of the information sharing flows throughout the end-to-end phishing process. In this paper, we perform an empirical measurement on the transmission and sharing of stolen login credentials. Over 5 months, our measurement covers more than 179,000 phishing URLs (47,000 live phishing sites). First, we build a measurement tool to feed fake credentials to live phishing sites. The goal is to monitor how the credential information is shared with the phishing server and potentially third-party collectors on the client side. Second, we obtain phishing kits from a subset of phishing sites to analyze how credentials are sent to attackers and third-parties on the server side. Third, we set up honey accounts to monitor the post-phishing exploitation activities from attackers. Our study reveals the key mechanisms for information sharing during phishing, particularly with third-parties. We also discuss the implications of our results for phishing defenses."


# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
# date: '2030-06-01T13:00:00Z'
# date_end: '2030-06-01T15:00:00Z'
# all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2023-10-05T00:00:00Z'

authors:
- Peng Peng
- Chao Xu
- Luke Quinn
- Hang Hu
- Bimal Viswanath
- Gang Wang
tags: [Phishing, Usability]

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 
  focal_point: Left

url_code: ''
url_pdf: 'https://dl.acm.org/doi/10.1145/3321705.3329818'
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
---

<!-- Slides can be added in a few ways:

- **Create** slides using Wowchemy's [_Slides_](https://docs.hugoblox.com/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/writing-markdown-latex/).

Further event details, including page elements such as image galleries, can be added to the body of this page. -->
