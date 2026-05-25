# Movie-Recommendation-Systems
Overview
This repository contains the standalone article website for my technical deep-dive on building a production-grade, real-time movie recommendation system. The project covers everything from Kafka event ingestion to ONNX-optimized inference — and explains why the hardest part of ML isn't the model.
Live Article: Read on Medium

The Article
From Batch to Real-Time: Designing a Scalable Movie Recommendation System
Most recommendation system tutorials stop too early. They train a model, evaluate it offline, and call it a day. But real-world systems don't work like that.
In production, recommendations are driven by continuous user behavior, strict latency constraints, and constantly changing data. The real challenge isn't building a model — it's building a system that stays relevant in real time.
In this project, I built a scalable movie recommendation system that processes over 1M daily interaction events, updates features dynamically, and serves low-latency recommendations using a hybrid ranking approach. 

article/
├── index.html          # Main article page
├── css/
│   └── style.css       # All styles (editorial newspaper aesthetic)
└── README.md           # This file 

Author
Prashant Anand — Data Scientist building production ML systems.

✉️ prashant.anand206@gmail.com
