# Prompt Guide

once the application note get published, the complete prompt guide will be uploaded immediately,including whole feed literatures, detailed prompts. etc.


Prompt engineering is an emerging field focusing on creating and refining prompts to maximize the effectiveness of large language models (LLMs) like GPT-4. This discipline is crucial for leveraging the full potential of LLMs across various applications and research areas. Key aspects include:

1. **Understanding Capabilities and Limitations**: Prompt engineering helps in comprehending the strengths and weaknesses of LLMs. This understanding is vital for realistic expectations and effective utilization.

2. **Applications in Diverse Domains**: LLMs are employed in numerous fields, including but not limited to question answering, text generation, and arithmetic reasoning. Prompt engineering tailors prompts to fit these diverse contexts.

3. **Optimization Techniques**: The field involves developing strategies to craft prompts that elicit the most accurate, relevant, and coherent responses from LLMs. This includes understanding the nuances of language and the model's interpretative mechanisms.

4. **Research and Development**: Researchers use prompt engineering to push the boundaries of what LLMs can do, exploring new applications and refining existing ones. Developers, on the other hand, focus on creating robust and efficient interfaces between LLMs and various applications.

5. **Continuous Evolution**: As LLMs evolve, so does prompt engineering. It adapts to changes in model architectures, capabilities, and user needs.

6. **Documentation and Knowledge Sharing**: The field emphasizes the importance of documenting case studies, best practices, and guidelines. Sharing detailed prompts, feed literature, and experiences helps the community to learn and grow collectively.

7. **Interdisciplinary Nature**: Prompt engineering intersects with linguistics, computer science, psychology, and more, offering a rich, interdisciplinary approach to problem-solving.


### 1. DBSCAN prompt

> me:

You aim to become a professional expert in agricultural machinery trajectory big data processing. We have selected several classic literature sources on the identifying  agricultural  machinery  operation  mode to assist you in understanding the tasks you will be handling next.

> chat-gpt4:

Embarking on a journey to become an expert in agricultural machinery trajectory big data processing is both challenging and rewarding. This field combines knowledge of agriculture, machinery operation, and advanced data processing techniques. To assist you in this endeavor, I can recommend some classic literature sources that will provide a foundational understanding of agricultural machinery operation modes and their relation to big data processing. Here are some key areas you should focus on:

1. **Agricultural Machinery Basics**: Start with books or academic papers that explain the types and functions of various agricultural machines. Understanding the machinery itself is crucial before delving into its operation modes.

2. **Operation Modes of Agricultural Machinery**: Look for literature that specifically discusses the different operation modes of these machines. This could include their working principles, settings for various agricultural tasks, and efficiency optimization.

3. **Big Data in Agriculture**: Seek out texts that explain how big data is used in agriculture. This will include data collection methods, data analysis, and how this data is used to improve agricultural practices.

4. **Data Processing Techniques**: Since your focus is on trajectory big data processing, it's important to understand the algorithms and software used in processing large sets of data, especially in relation to agricultural machinery.

5. **Case Studies and Research Papers**: Real-world case studies and recent research papers can provide insights into current practices and innovations in the field.

6. **Technological Trends**: Stay updated with the latest technological advancements in agricultural machinery and data processing. This might include AI, machine learning applications in agriculture, and the use of IoT devices in machinery.

Remember, the key is to build a strong foundation in both the agricultural and technological aspects of your field. Regularly reading industry journals, attending relevant conferences or webinars, and networking with professionals in the field can also be greatly beneficial.


> me:

We first regard field - road classification as a task only naming conventions, then the following conception such as  Field-road segmentation，Field-road classification，Field-road clustering, all identified as the field - road classification.


> chat-gpt4:

Your approach to understanding and classifying various tasks in agricultural machinery trajectory big data processing under the umbrella term of "field-road classification" is a structured way to organize this complex topic. Let's break down these concepts for clarity:

1. **Field-Road Classification (Naming Conventions)**: This initial task involves defining and distinguishing between different types of paths or areas where agricultural machinery operates, primarily differentiating between fields (where farming activities occur) and roads (used for transportation of machinery and goods). This classification is crucial for understanding the movement patterns and operational modes of the machinery.

2. **Field-Road Segmentation**: This involves the analysis of trajectory data to segment or separate the data points that correspond to field activities from those that correspond to road activities. This segmentation is critical for understanding where and how agricultural machinery is used, which helps in optimizing their routes and efficiency.

3. **Field-Road Classification (Analysis)**: After segmentation, the next step is a more detailed classification. This might involve categorizing different types of field activities (like plowing, seeding, harvesting) and different road activities (like transporting goods, moving between fields). This classification helps in understanding the specific tasks the machinery is performing, which is essential for operational efficiency and planning.

4. **Field-Road Clustering**: This task involves grouping similar patterns or types of field and road activities. Clustering can reveal common routes, operational patterns, and even identify areas for improvement in machinery deployment. It's a higher-level analysis that looks for patterns and commonalities in the data.

Throughout these tasks, the key is to effectively utilize big data techniques such as machine learning, data mining, and pattern recognition to analyze and interpret the vast amounts of data generated by agricultural machinery. This analysis can lead to more efficient use of machinery, better planning of agricultural activities, and overall improvements in productivity and sustainability in agriculture.

In summary, your approach to categorize and analyze agricultural machinery operation through the lens of field-road classification tasks is comprehensive. It allows for a detailed understanding of machinery usage patterns, which is fundamental in optimizing agricultural practices using big data.


> me:

I'm going to give you some papers that focus on the concept of field - road classification, you just need to understand the concept in conjunction with the paper


> chat-gpt4:

Absolutely, feel free to share the papers focusing on the concept of field-road classification. I'll review them to provide you with an understanding of how these concepts are applied and discussed in the papers. Please upload the documents or provide the key details from these papers for analysis.

> me:

You need to learn the meaning of field road segmentation based on above papers. I will then give you agriculture machinery trajectory. You should be able to distinguish which trajectory points are in the field and which ones are running in roads.

> chat-gpt4:

The concept of field-road trajectory segmentation, as discussed in the paper by Li et al. (2023), is a critical component in the analysis of agricultural machinery operations. This segmentation is essential for distinguishing between the activities of agricultural machinery in fields (where farming activities occur) and on roads (used for transport and movement between locations). Let's delve into the key aspects of this concept based on the paper:

1. **Purpose of Field-Road Trajectory Segmentation**: The segmentation process is vital for accurately calculating operational indicators during field operation and road driving. These indicators include the area covered, the duration of operations, and the driving distance.

2. **Methodology Used**: The paper employs a density-based spatial clustering approach (specifically DBSCAN - Density-Based Spatial Clustering of Applications with Noise) for trajectory segmentation. This method effectively differentiates between the harvester’s trajectory points during field operations and road driving. In their illustration, red trajectory points indicate field operations, while green points denote road driving.

3. **Application and Importance**: The segmentation allows for a detailed quantitative analysis of trans-regional operations of harvesters using GNSS (Global Navigation Satellite System) data. By separating field and road activities, it is possible to gain insights into patterns such as the quantity of operations, driving distances, harvesting duration, and harvested areas. This detailed analysis is crucial for optimizing the operational efficiency of harvesters and making informed decisions regarding agricultural machinery deployment.

4. **Broader Implications**: The study revealed significant insights such as the proportion of harvesters involved in trans-district operations and their coverage of the total harvested area. It also identified regions with a significant reliance on nonlocal harvesters, providing valuable information for government agencies, agricultural machinery enterprises, and operators to enhance decision-making and operational efficiency.

In summary, field-road trajectory segmentation in agricultural machinery big data analysis is a pivotal process for differentiating between field and road operations. This distinction enables a more nuanced understanding of machinery utilization, operational efficiency, and the spatial-temporal dynamics of agricultural operations【19†source】【20†source】【21†source】.

> me:

I give you a agricultural machinery trajectory data containing latitude and longitude, you use DBSCAN algorithm to do field-road segmentation and save the result as excel

> chat-gpt4:

The agricultural machinery trajectory data consists of longitude and latitude coordinates. To perform field-road segmentation using the DBSCAN algorithm, I will:

1. Apply the DBSCAN clustering algorithm to the dataset.
2. Identify distinct clusters, which will represent different segments (field operations and road driving).
3. Label the data points accordingly and save the results in an Excel file.

Let's proceed with this analysis.

The field-road segmentation of the agricultural machinery trajectory data has been completed using the DBSCAN algorithm. The resulting data, with segments labeled as either 'field' or 'road', has been saved as an Excel file.

You can download the segmented trajectory data from the following link: [Segmented Trajectory Data](sandbox:/mnt/data/segmented_trajectory_data.xlsx).

> me:

Change the label value “road” to 0 (regard as road) and the "field" to 1 (regard as field)

> chat-gpt4:

The labels in the segmented trajectory data have been updated as requested, with 'road' changed to 0 and 'field' to 1. The revised data has been saved to a new Excel file.

You can download the updated segmented trajectory data from this link: [Updated Segmented Trajectory Data](sandbox:/mnt/data/updated_segmented_trajectory_data.xlsx).

> me:

The effect of field road segmentation is not accurate. I will give you a real value as a reference. Generally speaking, the noise-like points of DBSCAN can be divided into roads. A large dense area can be divided into roads. You can combine the real value with what I said. Change the parameters of DBSCAN

> chat-gpt4:

The reference data includes longitude, latitude, and a label indicating whether each point is a road (0) or a field (1). To improve the accuracy of the field-road segmentation using DBSCAN, I'll take into account your guidance and the reference data. The approach will involve:

1. Adjusting the parameters of the DBSCAN algorithm, particularly the epsilon (neighborhood size) and min_samples (minimum number of points to form a dense region), to better match the real-world data.
2. Applying the adjusted DBSCAN algorithm to the original trajectory data.
3. Comparing the results with the reference data to ensure improved accuracy.

Let's proceed with this revised analysis.

The field-road segmentation of the agricultural machinery trajectory data has been re-analyzed using the adjusted DBSCAN parameters. The revised data, with segments now labeled as either 0 (road) or 1 (field), has been saved in a new Excel file.

You can download the adjusted segmented trajectory data from the following link: [Adjusted Segmented Trajectory Data](sandbox:/mnt/data/adjusted_segmented_trajectory_data.xlsx). This adjusted analysis should better match the real-world data and your specified criteria.

> me:

After adjusting the parameters, it becomes even more inaccurate. You first divide it into several categories to let the noise come out save it as a excel

> chat-gpt4:

The trajectory data has been segmented using the original DBSCAN parameters, and this time the noise points have been kept as a separate category. This approach should help in identifying the noise-like points more clearly.

You can download the segmented trajectory data with noise categories from the following link: [Original Segmented Trajectory Data with Noise](sandbox:/mnt/data/original_segmented_with_noise.xlsx). This file includes the different categories as identified by DBSCAN, which can be used for further analysis or adjustments.

> me:

Divide the data into multiple categories. Be sure to get more noise points. Don’t just have the value 0.

> chat-gpt4:

The trajectory data has been re-segmented using fine-tuned DBSCAN parameters aimed at generating more noise points and distinct categories. This adjustment should result in a more detailed categorization, including a greater number of noise points.

You can download the fine-tuned segmented trajectory data from this link: [Fine-Tuned Segmented Trajectory Data](sandbox:/mnt/data/fine_tuned_segmented_trajectory_data.xlsx). The resulting file includes the new segmentation, offering a more granular view of the data.

> me:

adjust the DBSCAN parameters and let noise points account for a larger proportion

> chat-gpt4:

The trajectory data has been segmented again with DBSCAN parameters specifically adjusted to increase the proportion of noise points. This should result in a segmentation where noise points (representing less dense areas) form a larger part of the data.

You can download the segmented trajectory data with a higher proportion of noise points from this link: [Segmented Trajectory Data with More Noise](sandbox:/mnt/data/more_noise_segmented_trajectory_data.xlsx). The resulting file includes this new segmentation, reflecting a greater emphasis on noise identification.

> me:

Change the label value -1 to 0 (regard as road) and the other values to 1 (regard as field)

> chat-gpt4:

The labels in the segmented trajectory data have been updated as requested: -1 has been changed to 0 (regarded as road) and all other values have been changed to 1 (regarded as field). The revised data has been saved to a new Excel file.

You can download the updated segmented trajectory data with the revised labels from this link: [Updated Segmented Trajectory Data with More Noise](sandbox:/mnt/data/updated_more_noise_segmented_trajectory_data.xlsx).

> me:

This is the real value of  field-road segmentation and adjust the parameters yourself. You want the accuracy of the new adjusted parameters to be above 80

> chat-gpt4:

After iteratively adjusting the parameters of the DBSCAN algorithm and comparing with the real values for field-road segmentation, the best configuration achieved an accuracy of approximately 97.41%. The parameters that led to this high accuracy are:

- Epsilon (ε): 0.0002
- Minimum Samples: 14

These parameters will now be used to segment the original trajectory data, aiming for an accuracy above 80%. Let's proceed with applying these optimized parameters.

The trajectory data has been segmented using the optimized DBSCAN parameters, which achieved an accuracy of approximately 97.41%. The segmented data, with updated labels based on these parameters, has been saved in a new Excel file.

You can download the optimized segmented trajectory data from the following link: [Optimized Segmented Trajectory Data](sandbox:/mnt/data/optimized_segmented_trajectory_data.xlsx). This segmentation should closely align with the real field-road classification values.

> me:

I will give you some new excel files next. You need use the dbscan parameters you just adjusted to perform field road segmentation operations and save them as excel.

> chat-gpt4:

Absolutely, I'm ready to apply the optimized DBSCAN parameters for field-road segmentation on any new data files you provide. Please upload the Excel files, and I'll proceed with the segmentation and save the results as Excel files.

> me:

Note: The name of the file saved as excel must be consistent with the name of the uploaded file.

> chat-gpt4:

The field-road segmentation has been performed on the new data file using the optimized DBSCAN parameters. The segmented data has been saved in an Excel file, named consistently with the original file name.

You can download the segmented data from the following link: [Segmented wheat_1_harvestor_12_longitude_latitude.xlsx](sandbox:/mnt/data/segmented_wheat_1_harvestor_12_longitude_latitude.xlsx).












