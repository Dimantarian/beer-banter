# beer-banter
A project to take some beer reviews shared through COVID quarantine and see if I can build something fun.

## Overview
The main purpose of this is to play around with some of the GCP APIs and see if I can make something interesting. Over the last month or so, some friends and I have shared a virtual beer most days, and have submitted beer reviews. This project will attempt the following

* Transcribe all the video reviews
* Run basic text analytics over the reviews
* See if there are any interesting quirks to the reviews

All of this will be attempted in GCP, using serverless compute where possible.

At the moment, main decisions are:

* What should the front end be?
  * Design
  * Compute?
  * What features?
* Language to code the back end (fairly confident I'll just go with python)
* How to store the data?
  * Structured - thinking BQ
  * Unstructured - thinking buckets / some sort of CDN
* Bash vs python for utility type stuff?
