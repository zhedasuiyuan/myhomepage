+++
abstract="Job scheduling plays an important role in improving the overall system performance in big data processing frameworks. Simple job scheduling policies, such as Fair and FIFO scheduling, do not consider job sizes and may degrade the performance when jobs of varying sizes arrive.  More elaborate job scheduling policies make the convenient assumption that jobs are recurring, and complete information about their sizes is available from their prior runs. In this paper, we design and implement an efficient and practical job scheduler for big data processing systems to achieve better performance even without prior information about job sizes. The superior performance of our job scheduler originates from the design of multiple level priority queues, where jobs are demoted to lower priority queues if the amount of service consumed so far reaches a certain threshold. In this case, jobs in need of a small amount of service can finish in the topmost several levels of queues, while jobs that need a large amount of service to complete are moved to lower priority queues to avoid head-of-line blocking. Our new job scheduler can effectively mimic the shortest job first scheduling policy without knowing the job sizes in advance. To demonstrate its performance, we have implemented our new job scheduler in YARN, a popular resource manager used by Hadoop/Spark, and validated its performance with both experiments on real datasets and large-scale trace-driven simulations. Our experimental and simulation results have strongly confirmed the effectiveness of our design: our new job scheduler can reduce the average job response time of the Fair scheduler by up to 45%."
abstract_short = ""
authors = ["Zhiming Hu, Baochun Li, Zheng Qin, Rick Siow Mong Goh"]
date = "2017-06-05"
image_preview = ""
math = true
publication_types = ["1"]
publication = "Proc.~of the 37th IEEE International Conference on Distributed Computing."
publication_short = "IEEE ICDCS"
selected = true
title = "Job Scheduling without Prior Information in Big Data Processing Systems"
url_code = ""
url_dataset = ""
url_pdf = "https://www.dropbox.com/s/6rphl323hg5cgot/zhu-icdcs17.pdf?dl=0"
url_project = "project/big_data_processing"
url_slides = ""
url_video = ""

+++

#More detail can easily be written here using *Markdown* and $\rm \LaTeX$ math code.
