---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 65

title: Projects
subtitle: ''

content:
  # Page type to display. E.g. project.
  page_type: project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  title: Ecommerce App
  summary: A fully functional ecommerce web app that allows you to browse through different products, add the products you like to your cart and buy what you like by entering your details, selecting your shipping and paying with Stripe. Uses Next.JS, React.JS, Stripe, Sanity.
  external_link: 'https://github.com/metabiswadeep/ecommerce-app'

  title: Driver Drowsiness Detection and Alarm System
  summary: A machine learning model that can detect drowsiness of the individual driving a car and sound an alarm to wake him/her up. It uses a computer vision neural network to identify facial features for drowsiness. It can help drastically reduce the number of road accidents caused due to sleep deprivation of individuals. Uses Python, Yolov5, OpenCV, PyTorch, Tkinter.
  external_link: 'https://github.com/metabiswadeep/driver-drowsiness-detection-and-alarm-system'

  title: Chatter Away
  summary: A chatroom webapp that allows users validated using unique validation keys to create channels and use text, emojis and attachments to express thoughts better. Uses React.JS, Stream API.
  external_link: 'https://github.com/metabiswadeep/ChatterAway'

  title: Sentiment Analysis of Amazon reviews
  summary: Performed sentiment analysis using the VADER and Roberta models to classify amazon reviews as positive, neutral or negative. Uses NLTK, Hugging Face transformers, Python.
  external_link: 'https://github.com/metabiswadeep/Sentiment-Analysis-of-Amazon-Reviews/'

  title: Admission Management System
  summary: Provides a system through which vast amount of data and records of students could be maintained in a systematic and clean manner for smoother administration procedures. Uses Python, MySQL, Tkinter.

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  # filter_button:
  #  - name: All
  #    tag: '*'
  #  - name: Deep Learning
  #    tag: Deep Learning
  #  - name: Other
  #    tag: Demo

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '1'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 2

  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---
