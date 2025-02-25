# FanChuan: A Multilingual and Graph-Structured Benchmark For Parody Detection and Analysis

Parody is an emerging phenomenon on social media, where people imitate a role or position opposite to their own, often for humor, provocation, or controversy. We built seven parody datasets from both English and Chinese corpora, with 14,758 annotated users and 21,927 annotated comments in total. To provide sufficient context information, we also collect replies and construct user-interaction graphs to provide richer contextual information. With these datasets, we test traditional methods and Large Language Models (LLMs) on three key tasks: (1) parody detection, (2) comment sentiment analysis with parody, and (3) user sentiment analysis with parody. Our extensive experiments reveal that parody-related tasks still remain challenging for all models, and contextual information plays a critical role. Interestingly, we find that, in certain scenarios, traditional sentence embedding methods combined with simple classifiers can outperform advanced LLMs, i.e. DeepSeek-R1 and GPT-o3, highlighting parody as a significant challenge for LLMs.

## Datasets

| **Dataset**       | **Background** | **Example** |
|-------------------|---------------|-------------|
| **Alibaba-Math**  | A vocational school student excelled in the Alibaba Mathematics Competition, sparking admiration and skepticism. Some accused her of cheating based on TV interview snippets. | **"这位同学有实力！阿里巴巴有眼光！请阿里巴巴破格录取进入达摩院，助力阿里科技快速发展。"** <br> *"This student has strength! Alibaba has vision! Please grant her an exceptional admission to DAMO Academy to boost Alibaba’s technological growth."* |
| **BridePrice**    | In China, the bride price tradition is debated—some see it as security for the bride, while others argue it has no link to marital happiness. | **"是的是的，姐妹们千万别乱嫁人，找不到年入百万的千万别嫁，女孩子五十岁都很值钱！"** <br> *"Ladies, never marry recklessly. If he doesn't make a million a year, don't marry him. Girls are valuable even at fifty!"* |
| **DrinkWater**    | A tech creator introduced a complex "Water Drinking Battle" system to encourage hydration, but its high cost and low effectiveness led to skepticism. | **"震古烁今，足以开启第五次技术革命。"** <br> *"A groundbreaking innovation capable of launching the fifth technological revolution."* |
| **CS2**          | In the CS2 World Championship finals, G2 lost to NAVI for the eighth time, fueling debates on whether roster changes improved their performance. | **"传奇捕虾人终结了G2的三日王朝。"** <br> *"The legendary shrimp catcher ended G2's three-day dynasty."*|
| **CampusLife**    | Discussions from a university forum covered topics like dorm life and administration. A debate arose over a roommate bringing their girlfriend overnight. Another topic involved a controversial restroom poster linking tuition fees to global conflicts. | *"Jealous?"* (Mocking the student's complaint) <br> *"Every computer on campus is equipped with an Intel processor... Switch to a Zhaoxin CPU immediately!"* |
| **Tiktok-Trump**  | A female Trump supporter lost a debate and faced criticism. Some parodically praised her performance to highlight her weak arguments. | *"She did a great job bringing up solid points."* |
| **Reddit-Trump**  | Trump's rhetoric and speaking style are frequently mimicked by critics using parody. | *"He's been tested—more than anyone, by the best doctors in the world... It’s incredible."* |


### The part of code is still being sorted out

