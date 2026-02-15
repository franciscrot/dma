---
layout: default
title: Critical AI Practice
---

# Critical AI Practice

Critical AI practice centres on thoughtful engagement with Machine Learning and automated systems. 

- Critical AI Studies
- AI Adversarial Literacy
- Using Machine Learning in DH+
- Carbon Estimation
- Distant Reading, AI Summation, Hallucination

## Critical AI Studies

DH is being transformed by Machine Learning and other AI. At the same time, arts and humanities have distinctive perspectives on AI, including the political economy, history, ethics, and philosophy of AI. These perspectives often diverge from fields like Responsible AI, Trustworthy AI, AI Alignment, AI Safety, Sustainable AI, and AI Ethics. 

- Understanding the political economy of AI
- Understanding AI cultures
- Envisioning alternative AI futures
- Historicising AI within longer history of automation
- Evaluating model bias, limitations, and transparency
- Considering cultural, social, and environmental impacts
- Designing human-centered workflows and safeguards
- Interrogating "the human"
- Enabling interdisciplinary collaboration
- Developing new ways of reading and interpreting in an era of AI slop and misinformation / disinformation

## AI Adversarial Literacy

Some resources on the more 'applied' side of Critical AI Studies. Spotting AI, stopping AI, and more.

<details markdown="1">
<summary>Resources</summary>

- [Reporter's Guide to Detecting AI-Generated Content](https://gijn.org/resource/guide-detecting-ai-generated-content/)
- [Iocaine](https://iocaine.madhouse-project.org/). "This software is not made for making the Crawlers go away. It is an aggressive defense mechanism that tries its best to take the blunt of the assault, serve them garbage, and keep them off of upstream resources."
- [Anubis.](https://anubis.techaro.lol/) "Weigh the soul of incoming HTTP requests to protect your website."
- Add resources on identifying genAI content

</details>


## Using Machine Learning in DH+ {#intro-to-making-ai}

The definition of 'AI' is blurry and contested. The Digital Humanities is definitely an area where you can trace back some AI uses cases back to older techniques which we might not normally call AI nowadays (or we might say "well, technically that's AI too").

<details markdown="1">
<summary>How long has the Digital Humanities been using AI?</summary>

- It really depends what you mean by "AI", and DH+ is a good space to observe how the term has shifted.
- There is actually a DH+ type project in tracing this history in a more granular way. But as a rough and reductive history ...
- Automated image recognition: 1950s–60s: early neural networks (e.g. the perceptron) and symbolic computer vision research, often described as pattern recognition or cybernetics. See e.g. the MIT [Summer Vision Project (1966)](https://dspace.mit.edu/bitstream/handle/1721.1/6125/AIM-100.pdf). 1970s–80s: scale-space theory formalised, providing a mathematically grounded way to analyse images at multiple resolutions; becomes foundational for edge detection and feature extraction. 1990s–2000s: feature-based pipelines (e.g. SIFT, 1999) combined with classifiers such as Support Vector Machines (mid-1990s) dominated computer vision; typically described as statistical machine learning or pattern recognition rather than mainstream “AI.” 2010s: deep convolutional neural networks — especially following the 2012 ImageNet breakthrough — dramatically improved large-scale image classification and re-centred computer vision within contemporary AI discourse. Rise of diffusion models and genAI for images.
- OCR: In the mid-2010s, neural network approaches (including LSTM-based models) improved performance on complex layouts and historical print, and Handwritten Text Recognition (HTR) gained traction for manuscript archives; at this point, OCR and HTR were increasingly folded into AI discourse.
- Topic modelling. 1960s–80s: computational text analysis focused on concordances, word frequencies, collocation, and stylometry — rarely framed as AI. Early 2000s: probabilistic topic modelling emerges, especially Latent Dirichlet Allocation, drawing on Bayesian machine learning and enabling large-scale thematic analysis across thousands of texts. 2000s–early 2010s: becomes much more central corpus-scale interpretation in DH, often described as statistical modelling or machine learning. Mid-2010s onward: increasingly absorbed into broader “AI” discourse
</details>

<details markdown="1">
<summary>Resources</summary>

- Programming Historian: [Interrogating a National Narrative with GPT-2](https://programminghistorian.org/en/lessons/interrogating-a-national-narrative-with-gpt-2). "In this lesson, you will learn how to apply a Generative Pre-trained Transformer language model to a large-scale corpus so that you can locate broad themes and trends within written text."
- Programming Historian: [Creating Deep Convolutional Neural Networks for Image Classification](https://programminghistorian.org/en/lessons/deep-convolutional-neural-networks). "This lesson provides a beginner-friendly introduction to convolutional neural networks (CNNs) for image classification."
- [Programming Historian: Facial Recognition in Historical Photographs with Artificial Intelligence in Python.](https://programminghistorian.org/en/lessons/facial-recognition-ai-python) "In this lesson, you’ll learn computer vision and machine learning principles for object recognition, and how to apply these principles using Python to recognize and classify smiling faces in historical photographs."
- Programming Historian: Creating Deep Convolutional Neural Networks for Image Classification. "This lesson provides a beginner-friendly introduction to convolutional neural networks (CNNs) for image classification."
- Programming Historian: Computer Vision for the Humanities: An Introduction to Deep Learning for Image Classification (Part 1). "This is the first of a two-part lesson introducing deep learning based computer vision methods for humanities research."
- Programming Historian: Computer Vision for the Humanities: An Introduction to Deep Learning for Image Classification (Part 2). "This lesson digs deeper into the details of training a deep learning based computer vision model."
- Programming Historian: Interrogating a National Narrative with GPT-2. "In this lesson, you will learn how to apply a Generative Pre-trained Transformer language model to a large-scale corpus so that you can locate broad themes and trends within written text."
- Programming Historian: Understanding and Creating Word Embeddings. "Through a primarily theoretical lens, this lesson will teach you how to prepare a corpus and train a word embedding model."
</details>

## Carbon estimation {#carbon-estimation}

AI's environmental costs have attracted a lot of attention, especially as hyperscale operators such as AWS, Microsoft Azure, and Google Cloud have failed to meet their decarbonisation targets. Estimating the carbon emissions of an AI system is hard, partly because of a lack of transparency from major hyperscale operators, and partly because there are many legitimate methodological approaches which will produce very different results. There is currently no well-established, generally accepted set of methodologies for measuring the carbon impact of AI systems. Water use for cooling is another significant environmental impact.

<details markdown="1">
<summary>Resources</summary>

- [Cook et al. (2025), Beyond Counting Carbon: AI Environmental Assessments Struggle to Inform Net Impact Decisions](https://research-information.bris.ac.uk/en/publications/beyond-counting-carbon-ai-environmental-assessments-struggle-to-i/)
- [The Digital Humanities Climate Coalition Toolkit](https://sas-dhrh.github.io/dhcc-toolkit/toolkit/decision-trees.html)
- [The Green Web Foundation](https://www.thegreenwebfoundation.org/)
- [CodeCarbon](https://codecarbon.io/) "Use Code Carbon to track and reduce your CO2 output."
- Branch Magazine, ['Pause'](https://branch.climateaction.tech/issues/issue-8/pause/).
- DHCC: [The Cloud and the Climate: Navigating Our AI-Powered Futures](https://drive.google.com/file/d/1WbD_YFZ9vceqfDWswGNkt-NNvSLkQBYN/view)
  
</details>

## Distant reading, automated summation, hallucination {#distance-reading}

[Distant reading](https://www.digitalstudies.org/article/id/8855/) emerged as an approach to literary scholarship in the 2000s, as a way of investigating larger patterns of literary production, circulation, and consumption. More recently, the rise of LLMs and the use of genAI raises new questions about computationally mediated texts, and about what counts as reading (distant, close, or otherwise).

<details markdown="1">
<summary>Resources</summary>

- Wikipedia: [Distant reading](https://en.wikipedia.org/wiki/Distant_reading)
- Programming Historian: Clustering and Visualising Documents using Word Embeddings. "This lesson uses word embeddings and clustering algorithms in Python to identify groups of similar documents in a corpus of approximately 9,000 academic abstracts."(https://programminghistorian.org/en/lessons/clustering-visualizing-word-embeddings)
- [Programming Historian: Analyzing Documents with TF-IDF. "This lesson focuses on a foundational natural language processing and information retrieval method called Term Frequency - Inverse Document Frequency (tf-idf)."](https://programminghistorian.org/en/lessons/analyzing-documents-with-tfidf)
- [Programming Historian: Understanding and Using Common Similarity Measures for Text Analysis](https://programminghistorian.org/en/lessons/common-similarity-measures). "This lesson introduces three common measures for determining how similar texts are to one another."
- Klein, Lauren F. (2013). [The Image of Absence: Archival Silence, Data Visualization, and James Hemings](https://read.dukeupress.edu/american-literature/article-abstract/85/4/661/4953/The-Image-of-Absence-Archival-Silence-Data). American Literature. 85 (4): 661–688. doi:10.1215/00029831-2367310
- Add resources on limitations and affordances of AI summaries
</details>

