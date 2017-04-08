# pslab-android
PSLab Android App

[![Build Status](https://travis-ci.org/fossasia/pslab-android.svg?branch=master)](https://travis-ci.org/fossasia/pslab-android)
[![Gitter](https://badges.gitter.im/fossasia/pslab.svg)](https://gitter.im/fossasia/pslab?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/dd728d91bb5743ff916c16c1251f8dd5)](https://www.codacy.com/app/praveenkumar103/pslab-android?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=fossasia/pslab-android&amp;utm_campaign=Badge_Grade)

This repository holds the Android App for performing experiments with [PSLab](http://pslab.fossasia.org/). PSLab is a tiny pocket science lab that provides an array of equipment for doing science and engineering experiments. It can function like an oscilloscope, waveform generator, frequency counter, programmable voltage and current source and also as a data logger.

## Communication
Our chat channel is on gitter here: https://gitter.im/fossasia/pslab

## Roadmap
 - First we need to get communication between Android App and PSLab working.
 
## Setup to use PSLab with Android App
To use PSLab device with Android, you simply need an OTG cable, an Android Device with USB Host feature enabled ( most modern phones have OTG support ) and PSLab Android App. Connect PSLab device to Android Phone via OTG cable. Rest is handled by App itself.

## Code practices

Please help us follow the best practice to make it easy for the reviewer as well as the contributor. We want to focus on the code quality more than on managing pull request ethics. 

 * Single commit per pull request
 * Reference the issue numbers in the commit message. Follow the pattern ``` Fixes #<issue number> <commit message>```
 * Follow uniform design practices. The design language must be consistent throughout the app.
 * The pull request will not get merged until and unless the commits are squashed. In case there are multiple commits on the PR, the commit author needs to squash them and not the maintainers cherrypicking and merging squashes.
 * If the PR is related to any front end change, please attach relevant screenshots in the pull request description.

