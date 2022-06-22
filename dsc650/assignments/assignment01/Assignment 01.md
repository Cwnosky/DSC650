---
title: Assignment 1
subtitle: Computer performance, reliability, and scalability calculation
author: Chris Nosky
---

## 1.2 

#### a. Data Sizes

| Data Item                                  | Size per Item | 
|--------------------------------------------|--------------:|
| 128 character message.                     | 128 Bytes     |
| 1024x768 PNG image                         | 0.45704 MB    |
| 1024x768 RAW image                         | 0.16058 MB    | 
| HD (1080p) HEVC Video (15 minutes)         | ? MB          |
| HD (1080p) Uncompressed Video (15 minutes) | 300 MB        |
| 4K UHD HEVC Video (15 minutes)             | ? MB          |
| 4k UHD Uncompressed Video (15 minutes)     | 1260 MB       |
| Human Genome (Uncompressed)                | ~770 mb       |

#### b. Scaling

|                                           | Size     | # HD | 
|-------------------------------------------|---------:|-----:|
| Daily Twitter Tweets (Uncompressed)       | 59 GB    | 3    |
| Daily Twitter Tweets (Snappy Compressed)  | ??       |      |
| Daily Instagram Photos                    | 31.17 GB | 3    |
| Daily YouTube Videos                      | 870 GB   | 3    |
| Yearly Twitter Tweets (Uncompressed)      | 21.2 TB  | 9    |
| Yearly Twitter Tweets (Snappy Compressed) | ??       |      |
| Yearly Instagram Photos                   | 11.1 TB  | 6    |
| Yearly YouTube Videos                     | 310 TB   | 93   |

#### c. Reliability
|                                    | # HD | # Failures |
|------------------------------------|-----:|-----------:|
| Twitter Tweets (Uncompressed)      | 9    |  0.11      |
| Twitter Tweets (Snappy Compressed) | ??   |            |
| Instagram Photos                   | 6    |  0.07      |
| YouTube Videos                     | 93   |  1.13      |

#### d. Latency

|                           | One Way Latency      |
|---------------------------|---------------------:|
| Los Angeles to Amsterdam  | 112 ms               |
| Low Earth Orbit Satellite | 30 - 50 ms           |
| Geostationary Satellite   | 600 ms               |
| Earth to the Moon         | 2400 ms              |
| Earth to Mars             | 4 - 20 minutes            | 
