# applied-ml-learning
This is a collection of papers, blogs, and videos I have read/watched as a learner of applied machine learning, together with scattered comments. Suggestions and pull requests welcomed.


## Books:
1. [Designing Machine Learning Systems: An Iterative Process for Production-Ready Applications](https://www.oreilly.com/library/view/designing-machine-learning/9781098107956/) `Chip Huyen` `2022`
    * Covers end-to-end life cycle of ML with real industry examples. Must read.
2. [Machine Learning Design Patterns](https://www.oreilly.com/library/view/machine-learning-design/9781098115777/) `Valliappa Lakshmanan, Sara Robinson, Michael Munn` `2020`
    * A good complement to Chip Huyen's book.

## Recommendation System
### RecSys Design Patterns:

1. [Moving Beyond Recommender Models: the Four Stages of Production Recommeder Systems (Video)](https://www.youtube.com/watch?v=5qjiY-kLwFY) `NVIDIA` `2021`
    * Clear summary of the four stages of RecSys, great for first-time learners.
2. [System Design for Recommendations and Search](https://eugeneyan.com/writing/system-design-for-discovery/) `Eugene Yan` `2021`
    * Great summary of the online/offline components of RecSys.
3. [RecSys Design & Its Evaluations, Video](https://youtu.be/PRjfT_Lt0uk?t=4769) [(Slides)](https://docs.google.com/presentation/d/1u8UPRYuQdB6GIe7A8jHKSQurnBi6HGKr2IVjhoXh9YM/edit#slide=id.p1) `MLOps Learners` `2022`
    * Great discussions on the metrics used in RecSys.
4. [Patterns for Personalization in Recommendations and Search](https://eugeneyan.com/writing/patterns-for-personalization/) `Eugene Yan` `2021`
    * How to summarize embeddings.
5. [How to Build a Deep Learning Powered Recommender System, Part 2](https://developer.nvidia.com/blog/how-to-build-a-winning-recommendation-system-part-2-deep-learning-for-recommender-systems/) `NVIDIA` `2021`
    * Introduction of common Deep Learning models used in RecSys.
6. [Real-time Machine Learning For Recommendations](https://eugeneyan.com/writing/real-time-recommendations/) `Eugene Yan` `2021`
    * Great discussions about batch VS. real-time scoring.
7. [Ten Mistakes to Avoid When Creating a Recommendation System](https://funcorp.dev/blog/ten-mistakes-to-avoid) `Funcorp` `2022`
    * Practical and comprehensive guide from practitioner's perspective.
8. [Core Modeling at Instagram](https://instagram-engineering.com/core-modeling-at-instagram-a51e0158aa48) `Instagram` 2019
    * Gem that discusses the nitty-gritty details in the system.
9. [Improving job matching with machine-learned activity features](https://engineering.linkedin.com/blog/2022/improving-job-matching-with-machine-learned-activity-features-) `Linkedin` `2022`

### Classical Papers
1. [De‍‌‍‍‍‌‍‌‌‍‌‍‍‌‍‍‌‌‍‍ep Neural Networks for YouTube Recommendations](https://research.google.com/pubs/archive/45530.pdf) `YouTube` `2016`
2. [Wide & Deep Learning for Recommender Systems
](https://arxiv.org/pdf/1606.07792.pdf) `Google` `2016`
3. [Recommending What Video to Watch Next: A Multitask Ranking System](https://daiwk.github.io/assets/youtube-multitask.pdf) `YouTube` `2019`

### Real time Recommendation
1. [Monolith: Real Time Recommendation System With Collisionless Embedding Table](https://arxiv.org/pdf/2209.07663.pdf) `Bytedance` `2022`
2. [How Pinterest Leverages Realtime User Actions in Recommendation to Boost Homefeed Engagement Volume](https://medium.com/pinterest-engineering/how-pinterest-leverages-realtime-user-actions-in-recommendation-to-boost-homefeed-engagement-volume-165ae2e8cde8) `Pinterest` `2022`

### RecSys for Specific Product:
1. [Powered by AI: Instagram’s Explore recommender system](https://ai.facebook.com/blog/powered-by-ai-instagrams-explore-recommender-system/) `Instagram` `2019`
2. [How Instagram suggests new content](https://engineering.fb.com/2020/12/10/web/how-instagram-suggests-new-content/)
`Instagram` `2020`
3. [Good Questions, Real Answers: How Does Facebook Use Machine Learning to Deliver Ads?](https://www.facebook.com/business/news/good-questions-real-answers-how-does-facebook-use-machine-learning-to-deliver-ads) `Facebook` `2020`
4. [How machine learning powers Facebook’s News Feed ranking algorithm](https://engineering.fb.com/2021/01/26/ml-applications/news-feed-ranking/) `Facebook` `2021`
5. [On YouTube’s recommendation system](https://blog.youtube/inside-youtube/on-youtubes-recommendation-system/) `YouTube` `2021`
6. [How we use AutoML, Multi-task learning and Multi-tower models for Pinterest Ads](https://medium.com/pinterest-engineering/how-we-use-automl-multi-task-learning-and-multi-tower-models-for-pinterest-ads-db966c3dc99e) `Pinterest` `2020`
7. [Building Airbnb Categories with ML and Human-in-the-Loop](https://medium.com/airbnb-engineering/building-airbnb-categories-with-ml-and-human-in-the-loop-e97988e70ebb) `Airbnb` `2022`
    * Make recommendation not only optimize for booking but also build more "inspireational" browsing experiences such that guests discover places didn't think of.

### Surfacing (Ordering/Reranking)
1. [Homepage Recommendation with Exploitation and Exploration](https://doordash.engineering/2022/10/05/homepage-recommendation-with-exploitation-and-exploration/) `DoorDash` `2022`
    * Discusses the challenging problem of carousel ranking.


## Search
1. [Search - Query Matching via Lexical, Graph, and Embedding Methods](https://eugeneyan.com/writing/search-query-matching/) `Eugene Yan` `2021`
2. [Embedding-based Retrieval in Facebook Search](https://arxiv.org/pdf/2006.11632.pdf) `Facebook` `2020`
    * Very inspiring paper. Especially where it discusses the reasoning and experiments behind the choices of positive/negative labels.

## Integrity:
1. [Preserving Integrity in Online Social Networks](https://arxiv.org/pdf/2009.10311.pdf) `Facebook` `2020`
    * Comprehensive survey in the area of social media content moderation.
2. [Machine Learning for Fraud Detection in Streaming Services](https://netflixtechblog.medium.com/machine-learning-for-fraud-detection-in-streaming-services-b0b4ef3be3f6) `Netflix` `2022`


## A/B testing:
1. [Meet Dash-AB — The Statistics Engine of Experimentation at DoorDash](https://doordash.engineering/2022/05/24/meet-dash-ab-the-statistics-engine-of-experimentation-at-doordash/)
`DoorDash` `2022`
2. [Balancing Velocity and Confidence in Experimentation](https://doordash.engineering/2022/11/15/balancing-velocity-and-confidence-in-experimentation/) `DoorDash` `2022`
    * No need to stick to alpha=0.05 and power=0.8! For certain decisicion, a tolerance of higher false positive in exchange of high velocity is worthwhile: it allows one to run more experiments!

## Enterprise-level Overview: 
1. [150 Successful Machine Learning Models: 6 Lessons Learned at Booking.com](https://blog.kevinhu.me/2021/04/25/25-Paper-Reading-Booking.com-Experiences/bernardi2019.pdf) `Booking.com` `2019`
