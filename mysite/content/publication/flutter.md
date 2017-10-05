+++
abstract="Typically called big data processing, processing large volumes of data from geographically distributed regions with machine learning algorithms has emerged as an important analytical tool for governments and multinational corporations. The traditional wisdom calls for the collection of all the data across the world to a central datacenter location, to be processed using data-parallel applications.  This is neither efficient nor practical as the volume of data grows exponentially.  Rather than transferring data, we believe that computation tasks should be scheduled where the data is, while data should be processed with a minimum amount of transfers across datacenters. In this paper, we design and implement Flutter, a new task scheduling algorithm that improves the completion times of big data processing jobs across geographically distributed datacenters.  To cater to the specific characteristics of data-parallel applications, we first formulate our problem as a lexicographical min-max integer linear programming (ILP) problem, and then transform it into a nonlinear program with a separable convex objective function and a totally unimodular constraint matrix, which can be solved using a standard linear programming solver efficiently in an online fashion.  Our implementation of Flutter is based on Apache Spark, a modern framework popular for big data processing. Our experimental results have shown that we can reduce the job completion time by at most 25%, and the amount of traffic transferred among different datacenters by at most 75%."
abstract_short = " "
authors = ["Zhiming Hu, Baochun Li, Jun Luo"]
date = "2016-04-10"
image_preview = ""
math = true
publication_types = ["1"]
publication = "Proc. of the IEEE Conference on Computer Communications."
publication_short = "IEEE INFOCOM"
selected = true
title = "Flutter: Scheduling Tasks Closer to Data Across Geo-Distributed Datacenters"
url_code = ""
url_dataset = ""
url_pdf = "https://www.dropbox.com/s/jqm4rs90rkvc2n7/zhu-infocom16.pdf?dl=0"
url_project = "project/big_data_processing"
url_slides = ""
url_video = ""

+++
