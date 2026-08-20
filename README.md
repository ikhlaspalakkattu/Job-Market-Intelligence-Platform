Most people navigate the job market on instinct. They pick skills based on what sounds popular, target roles based on gut feeling, and hope generic advice translates into real opportunities. This project seeks to change that.

The Job Market Intelligence Platform turns raw job posting data into a clear, structured picture of what employers are actually looking for. The first release focuses on Data Science and AI roles across the Gulf region as a proof of concept, with the longer term goal of covering any industry, any region, and any audience including job seekers, recruiters and university course designers.

How the data was collected

The dataset was built from scratch using the Apify web scraper, pulling active job postings from LinkedIn in June 2026. Postings were collected across three Gulf region countries: the UAE, Saudi Arabia and Qatar. Four search queries were used to capture the relevant roles: machine learning, artificial intelligence, data science and data scientist.

The raw results were filtered down in two steps. First, postings were limited to those published within the past year to ensure the data reflected current employer demand rather than outdated listings. Second, any postings that appeared in the results purely due to keyword overlap but were not genuinely relevant to Data Science or AI work were removed manually. This filtering process brought the final sample to 264 postings.

It is worth being transparent about what this dataset is and is not. 264 postings is a meaningful starting point for identifying patterns but it is not large enough to make definitive market wide claims. The data reflects one platform, LinkedIn, at one point in time, and the Gulf region is a broad label that covers markets with different hiring cultures and demand levels. All findings in this analysis should be read as directional signals within this sample rather than absolute statements about the market as a whole.

Role by role skill breakdown

Not all Data Science and AI roles ask for the same things, and treating them as interchangeable is one of the most common mistakes junior job seekers make. Breaking the dataset down by role category reveals clear and meaningful differences in what employers actually expect.

AI Engineer was the largest category in the sample at 29% of postings. Postings in this group skewed toward general AI and Machine Learning tags alongside Python, with Communication and Research also appearing frequently. The profile suggests a generalist role that sits at the intersection of technical implementation and business context.

Data Scientist postings told a different story. This was the most SQL heavy category in the entire dataset, with SQL appearing in 72% of Data Scientist postings compared to much lower rates elsewhere. Python and Machine Learning were also consistently present. The Data Scientist role, at least in this sample, still centres on querying and modelling structured data more than any other category.

ML Engineer postings were the most technically specific. PyTorch and TensorFlow both appeared in 75% of ML Engineer listings, making this the only role category where deep learning frameworks consistently ranked among the top required skills. If framework level expertise is your strength, ML Engineering is where the market is most likely to reward it.

AI Leadership roles, which accounted for 19% of postings, unsurprisingly prioritised Leadership and Communication above technical tooling. However AI and Machine Learning still appeared in the majority of these postings, suggesting that even senior non-hands-on roles expect candidates to have a working understanding of the technology rather than just managing teams around it.

On the technical skills side overall, Python appeared in roughly half of all postings and remains the closest thing to a universal requirement across role types. Azure, AWS and GCP were all present at similar rates, which suggests that cloud platform flexibility is more valuable than deep specialisation in any single provider. Notably, Communication appeared in nearly half of all postings across every role category, reinforcing that technical skills alone are not sufficient in this market.

What comes next

The platform currently serves as a working snapshot of the Gulf Data Science and AI market. The next phase of development will focus on automating data collection, expanding to additional job boards and regions, and opening the pipeline to non-technical job categories so the same intelligence layer can serve a much broader audience.
