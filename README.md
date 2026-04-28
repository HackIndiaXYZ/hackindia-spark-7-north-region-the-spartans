# hackindia-spark-7-north-region-the-spartans
Hackathon team repository for The Spartans - [hackindia-team:hackindia-spark-7-north-region:the-spartans]

Neurofied.ai

AI-powered Cognitive Health Platform

Live Demo: https://q58azg2z.insforge.site

It's best to view this project live. From this link, you can access all the features including cognitive testing, AI analysis and insight dashboards.

Overview

Neurofied.ai is an artificial intelligence (AI) based platform for cognitive health to facilitate early detection of cognitive decline by means of convenient, rapid and scalable digital approaches. Our approach is to detect early signs of cognitive decline through subtle changes in user behaviour, as well as subjective reports, well in advance of a clinical diagnosis. Users can access information about their cognitive health in a single integrated experience by combining various input modes.

Neurofied.ai's underlying philosophy is founded on the belief that many of the cases of cognitive decline could be prevented if detected early. The tool brings this idea to fruition for anyone to use, even without medical technologies and professional assistance.

Our philosophy is:
Preventing the 45 percent that can be avoided.

Problem

Impacts of cognitive decline and neurodegenerative diseases, such as Alzheimer's disease are usually detected well into their progression, when treatment is limited and less effective. Current diagnostic approaches use clinical and imaging assessments, and specialist review, which may not always be accessible or affordable for all. Further, early signs and symptoms are often mild, intermittent and go undetected.

This leads to a significant lag between the start of early changes in cognition and diagnosis. This results in people living unaware, and not taking advantage of early detection opportunities that might make a considerable difference. It has been shown that many cases are affected by lifestyle and other behavioral factors, suggesting that a key to early detection is a simple, scalable, easy to use approach.

Solution

Neurofied.ai tackles this challenge by offering a comprehensive cognitive assessment system that combines cognitive testing, health questionnaires and language analysis. The system is structured to pick up both objective and subjective measures to better understand cognitive function.

The approach consists of three pathways. The first is based on interaction involving simple cognitive tests with reaction time and memory measures. These tests yield objective measures of processing speed, attention and short-term memory, which are often the first to be impacted by cognitive impairment.

The second pathway uses structured input, where users input basic health details, such as age, lifestyle and basic cognitive markers. This information is analysed with a simple logistic regression-like model that categorises a person's cognitive risk status in a simple and explainable way.

The third pathway is based on expressive input, where users can provide information about their symptoms, complaints or experiences in a free-text format. This is processed with a pre-trained language model, allowing the system to understand unstructured information and provide contextual understanding. This reflects the real-world clinical practice where patient descriptions can often be diagnostic.

These three channels converge to create an integrated system, capturing behavioral, structured and expressive features for a more comprehensive evaluation than could be achieved with a single approach.

Features

The system has an intuitive and user-friendly interface. The home page serves as the starting point, directing users to various modes. The behavioral test module allows interactive and rapid assessment of cognitive function, whereas the structured form is a more traditional means of data input for risk calculation. The expressive analysis module allows users to freely express their feelings, leading to deeper insights.

Each of the input channels is associated with a specific result dashboard. These dashboards offer risk, scores and explanations in an easily digestible manner, enabling users to interpret their results without technical or medical knowledge. The platform also offers a profile page to store and view previous results, enabling users to view performance changes and trends over time.

Beyond the assessment aspect, there's an awareness module that provides educational videos on brain health, early signs and prevention. This makes the app not only diagnostic but educational and preventive as well.

Technical Approach

The architecture of the system is aimed to be simple, fast and scalable. Contemporary web technologies are used in the front-end to create a responsive user interface. User interaction data is fed into simple models and logic rules that allow for real-time feedback without the need for complex processing.

The behavioral test pathway uses deterministic data processing to interpret user performance data, providing predictable and consistent results. The structured input pathway employs a simple logistic regression-like model, building on machine learning methods, to determine risk based on user input features. The expressive pathway communicates with a pre-trained language model via API, making it possible to process natural language data inputs and gain insights.

This multi-pronged approach facilitates both the technical feasibility of the system within the limited time frame of the development, and the ability to showcase its usefulness in practice.

Why This Matters

Neurofied.ai is not only a showcase of technological prowess but also a move towards democratising cognitive health assessment. The focus on earlier stages of cognitive issues rather than just diagnosis allows people to proactively manage their cognitive health. The use of multiple data streams represents a more realistic view of cognitive decline in the real world. The tool shows that valuable health information can be extracted from minimal interactions, as long as they are well-designed and analysed. It showcases how integrating behavioral data, structured data and natural language processing into a single, practical, meaningful system can be successful.

Conclusion

Neurofied.ai is a scalable and user friendly system for early detection of cognitive impairment. It offers a unified platform combining various assessment methods, balancing clinical and user-friendly design. The approach is part of an iterative process that has the capacity for more complex models, data and clinical validation methods to be incorporated.

Ultimately, the project is based on the simple concept: prevention is better than cure. By democratising cognitive assessment, Neurofied.ai hopes to play a part in decreasing the number of preventable cases and to improve cognitive health.
