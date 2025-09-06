+++
author = "Yukthi Chikkanna"
title = "My First Open Source Contribution" 
date = "2025-09-03"
description = "My first Open-source"
tags = [
    "open-source","GCP", "Alfred", "iam"
]
+++

Open source has always fascinated me, but for a long time, I felt like contributing was something “other people” did — developers with tons of experience or deep knowledge of certain frameworks. That changed recently when I made my **first open source contribution** to a project I actually use every day: [`alfred-gcp-workflow`](https://github.com/dineshgowda24/alfred-gcp-workflow).

## 🧠 What is Alfred?

[**Alfred**](https://www.alfredapp.com/) is a productivity app for macOS that boosts efficiency by allowing you to control your Mac with just your keyboard. It’s like Spotlight on steroids — you can:

* Launch apps and files
* Search the web
* Control your system
* Automate tasks
* Build and use **workflows** to integrate tools, APIs, and services

It’s one of those apps that quietly becomes essential once you start using it.

## ⚙️ The Project: alfred-gcp-workflow

One of the Alfred workflows I rely on is [`alfred-gcp-workflow`](https://github.com/dineshgowda24/alfred-gcp-workflow), which lets you search and access **Google Cloud Platform (GCP)** resources directly from Alfred. With a few keystrokes, you can find Cloud Functions, Storage Buckets, Projects, and jump right into their GCP Console URLs.

As someone who works with GCP frequently, this workflow saves me time and keeps me focused.


## 🤔 The Missing Feature

While using the workflow, I realized it didn’t support one thing I often need: **IAM Service Accounts**. These are essential for managing permissions and authentication in GCP, and I regularly need to search for them or open their settings.

It felt like a natural fit for the workflow — so I decided to add it.

## ✍️ My Contribution

This was my first time contributing to an open source project, so I started small and focused on one goal: **add IAM Service Accounts as a searchable resource** within the workflow.

I followed the structure used for other GCP resources in the project, added support for service accounts, and updated the necessary configuration and documentation.

Once it was working locally, I submitted a pull request. The project maintainer reviewed it, left a few comments, and merged it shortly after. Just like that — my first open source contribution was live.

📌 **PR:** [#61 - Searcher for IAM Service Account](https://github.com/dineshgowda24/alfred-gcp-workflow/pull/61)

## 💡 What I Took Away

* **Start small:** You don’t have to build a giant feature to contribute. Even a small addition can be meaningful.
* **Contribute to what you use:** This was a tool I already used daily, so I was naturally invested in making it better.
* **You belong:** Contributing helped me shake off the feeling that open source is only for “experts.”

This small contribution gave me the confidence to keep going. I’ve already started looking at other tools I use with the mindset of: *“Could I improve this for myself and others?”*

## 🔭 What's Next?

I’d love to contribute more to open source — whether it’s enhancements to tools I use, fixing bugs, or even helping improve docs for beginner contributors.

I also want to encourage others who feel like they’re “not ready” to get involved. You are. There’s room for everyone — and sometimes all it takes is a single pull request to get started.

Thanks for reading!
Feel free to check out my contribution here:
👉 [#61 - Searcher for IAM Service Account](https://github.com/dineshgowda24/alfred-gcp-workflow/pull/61)
