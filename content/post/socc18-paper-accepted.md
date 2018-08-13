---
title: "Socc'18 Paper Accepted"
date: 2018-08-13T10:23:03-07:00
draft: false
categories:
  - Video
---

Our paper on _Sprocket_, a serverless video processing framework,
has been accepted to the ACM SoCC conference, which is co-located
with this year's OSDI.

## Abstract

Sprocket is a highly configurable, stage-based, scalable, serverless video
processing framework that exploits intra-video parallelism to achieve low
latency. Sprocket enables developers to program a series of operations over
video content in a modular, extensible manner. Programmers implement custom
operations, ranging from simple video transformations to more complex computer
vision tasks, in a simple pipeline specification language to construct custom
video processing pipelines. Sprocket then handles the underlying access,
encoding and decoding, and processing of video and image content across
operations in a highly parallel manner. In this paper we describe the design
and implementation of the Sprocket system on the AWS Lambda serverless cloud
infrastructure, and evaluate Sprocket under a variety of conditions to show
that it delivers its performance goals of high parallelism, low latency, and
low cost (10s of seconds to process a 3,600 second video 1000-way parallel for
less than $3).

[Link to conference website](https://acmsocc.github.io/2018/)
