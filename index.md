---
layout: home
title: Aspire Dashboard
description: A free & open-source OpenTelemetry dashboard for deep insights into your apps on your local development machine.
image: /assets/img/aspire.gif
movie: /assets/img/aspire.mp4
button1:
  text: Features
  link: "#features"
button2:
  text: Get Started
  link: "#start"
features:
  intro: FEATURES
  title: Essentials for developers
  list3:
    title: Traces
    icon: /assets/img/logs.svg
    text: Understand the flow of requests and identify performance bottlenecks.
  list2:
    title: Metrics
    icon: /assets/img/metrixs.svg
    text: Analyze quantitative data about your apps behavior and performance.
  list1:
    title: Logs
    icon: /assets/img/trace.svg
    text: Detailed debugging and diagnostics with with structured and unstructured log views.
  list4:
    title: Dependencies
    icon: /assets/img/deps.svg
    text: Understand how your app is orchestrated and how the components work together.
github:
  intro: STATS
  title: Loved by developers
  text: Developers across the globe trust the Aspire Dashboard to get mission critical information while they are developing their applications. The Aspire Dashboard is free,  open-source, and constantly adding new features based on your feedback. 
  list:
    - title: Container Pulls (million)
      number: "2.6M"
    - title: Forks
      number: 543
    - title: Clones (monthly)
      number: 24575
    - title: GitHub Stars
      number: 4226
  star:
    title: GitGub Stars
    number: "3"
section:
  intro: ASPIRE CONTAINER
  title: Get the container
  subtitle: The container has two ports
  list: 
    - text: Port 4317 receives OpenTelemetry data from apps. Apps send data using OpenTelemetry Protocol (OTLP).
    - text: Port 18888 has the dashboard UI. Navigate to http://localhost:18888 in the browser to view the dashboard.
login:
  title: Login to dashboard
  subtitle: Data displayed in the dashboard can be sensitive. By default, the dashboard is secured with authentication that requires a token to login. The login token is printed to the container logs. After copying the highlighted token into the login page at http://localhost:18888, select the Login button.
  image: /assets/img/aspire-dashboard-container-log.png
start:
  intro: GET STARTED
  title: Easily integrate into your apps
start_python:
  title: Python
  icon: /assets/img/py.svg
  link: https://opentelemetry.io/docs/languages/python/getting-started/
start_javascript:
  title: JavaScript
  icon: /assets/img/js.svg
  link: https://opentelemetry.io/docs/languages/js/getting-started/
start_java:
  title: Java
  icon: /assets/img/java.svg
  link: https://opentelemetry.io/docs/languages/java/getting-started/
start_c:
  title: C#
  icon: /assets/img/csharp.svg
  link: https://opentelemetry.io/docs/languages/net/getting-started/
start_more:
  title: More
  link: https://opentelemetry.io/docs/languages/
faq:
  intro: FAQ
  title: Still have questions?
  list_active:
    q: Question 1
    a: Q1 Lorep ipsum dolor siamet Lorep ipsum dolor siamet Lorep ipsum dolor siamet
      Lorep ipsum dolor siamet Lorep ipsum dolor siamet Lorep ipsum dolor siamet
      Lorep ipsum dolor siamet Lorep ipsum dolor siamet
  list:
    - q: Question 2
      a: Q2 Lorep ipsum dolor siamet Lorep ipsum dolor siamet Lorep ipsum dolor siamet
        Lorep ipsum dolor siamet Lorep ipsum dolor siamet Lorep ipsum dolor
        siamet Lorep ipsum dolor siamet Lorep ipsum dolor siamet
    - q: Question 3
      a: Q3 Lorep ipsum dolor siamet Lorep ipsum dolor siamet Lorep ipsum dolor siamet
        Lorep ipsum dolor siamet Lorep ipsum dolor siamet Lorep ipsum dolor
        siamet Lorep ipsum dolor siamet Lorep ipsum dolor siamet
    - q: Question 4
      a: Q4 Lorep ipsum dolor siamet Lorep ipsum dolor siamet Lorep ipsum dolor siamet
        Lorep ipsum dolor siamet Lorep ipsum dolor siamet Lorep ipsum dolor
        siamet Lorep ipsum dolor siamet Lorep ipsum dolor siamet
    - q: Question 5
      a: Q5 Lorep ipsum dolor siamet Lorep ipsum dolor siamet Lorep ipsum dolor siamet
        Lorep ipsum dolor siamet Lorep ipsum dolor siamet Lorep ipsum dolor
        siamet Lorep ipsum dolor siamet Lorep ipsum dolor siamet
    - q: Question New
      a: This is answer for question new area
---
Get deep insight into your applications on your local development environment.

Full support for OpenTelemetry across a wide range of programming languages and frameworks including Python, Java, JavaScript, Ruby, Rust, .NET, Swift, and so much more!