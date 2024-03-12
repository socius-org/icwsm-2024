# Introduction 

#### Navigating 🧭 the complexities of APIs and data collection can be a daunting task, especially for researchers 👨‍💻 with limited coding backgrounds. **RedditHarbor simplifies collecting 📥 Reddit data and saving it to a database**. It **removes the complexity** of working with APIs 🏗️, letting you easily build a "harbor" of data for analysis.

![redditharbor_demo](https://github.com/socius-org/RedditHarbor/assets/130935698/7bb4f570-90f7-4e6c-a469-7e8debf9a260)

[RedditHarbor](https://github.com/socius-org/RedditHarbor/) is designed for researchers who want to focus on their analysis rather than grappling with technical complexities. While [PRAW](https://praw.readthedocs.io/en/stable/) offers flexibility for advanced users, RedditHarbor simplifies the process, allowing you to effortlessly collect the data you need through intuitive commands.

Here's how RedditHarbor empowers your research:

* **✨ Comprehensive Data Collection**: Connect directly to the Reddit API and gather submissions, comments, and user profiles with ease.
* **🔒 Privacy-Focused**: Anonymise any personally identifiable information (PII) to protect user privacy and comply with ethical research practices and IRB requirements.
* **📦 Organised Data Storage**: Store your collected data in a secure database that you control, ensuring accessibility and organisation.
* **📈 Scalable and Efficient**: Handle pagination seamlessly, even for large datasets with millions of rows. 
* **🕹️ Customisable Collection**: Tailor your data collection to your specific needs by configuring parameters.
* **📂 Analysis-Ready**: Export your database to CSV, JSON, or JPEG formats for effortless integration with your preferred analysis tools.

With RedditHarbor, you can spend less time wrestling with technical hurdles and more time focusing on your research objectives. 

```{admonition} Why Reddit? 
:class: tip
While there are various social media platforms and data APIs available, our focus will be solely on Reddit. This decision is driven by several key reasons, but primarily because Reddit is currently the *only* platform that provides data for academic research. Facebook terminated most API access years ago in the wake of the [Cambridge Analytica data scandal](https://en.wikipedia.org/wiki/Facebook%E2%80%93Cambridge_Analytica_data_scandal), and Twitter (now X) has [effectively closed the door on academic research](https://www.theverge.com/2023/5/31/23739084/twitter-elon-musk-api-policy-chilling-academic-research).
``` 