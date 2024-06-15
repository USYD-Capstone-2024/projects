# High-Res vs Low-Res images for long-range AI detection of vehicles

This project aims to evaluate the effectiveness of high-resolution (high-res) versus low-resolution (low-res) images in the long-range detection of construction vehicles using AI. The primary goal is to determine which resolution provides better accuracy and reliability for detection in various environmental conditions. The project involves developing and training AI models, conducting experiments with different image resolutions, and analyzing the results.

## Description
You will be using a 128 Megapixel camera system and feeding these images into the AI.  The camera system allows for lower resolutions (such as 32 MP or 8 MP).  Comparing the results of the AI for the various resolutions.  You could also scale down the original 128 MP images.

The AI model in use now is a variant of the YOLOv8 model.  This project is open-ended and will allow you to be flexible in selecting, training and utilising the model that your team feels is the best for the job.

Previous AI projects utilise lower resolution images (e.g. 640 x 640 or 1024 x 1024).  This project will likely use 18,000 x 13,000 images for model inference – significantly larger than any existing AI products on the market.

The team running this capstone project expects that you will need to learn lots on the project.  We have the experience to help you with the project and teach you more about AI, software design and best practices.   Making you the best developers out there.  

AI is a fast-growing area, ensuring that we have accurate and reliable detection is vital to the success of the project.  If you have an interest in working on new areas of research in the AI space, this is the project for you.


## Scope
- Research & Implement an AI detection model for construction vehicles.
- Collate high-res and low-res image datasets of construction vehicles (client to assist)
- Train and evaluate the model using both datasets.
- Analyze performance metrics such as accuracy, precision, recall, and processing time.
- Provide recommendations based on the comparative analysis.
- Experiment with different types of models and find the best one.


## Resources
- [YOLO Model Guides](https://docs.ultralytics.com/guides/)

## Timeline

**Week 1-2:**
- **Milestone 1: On-boarded and Dataset completed**
- Introduction and regular meeting schedule
- Access to High-Performance Compute ready
- Sample model training up and running on compute
- Datasets organised
- GitHub repo ready
- Two (2) AI model training runs completed (on sample data)

**Week 3-4:**
- **Milestone 2: First round of results and presentation.**
- Six (6) AI Model training runs completed with results compared
- Create validation dataset for comparing each models performance
- Create testing framework for rapid and automated testing of each model performance
- Image augmentation and dataset expansion to improve future model results
- Augment the dataset to increase variability and robustness.
- Research additional data sources from online
- GitHub workflows established (both automated and team review process).
- Check-In Presentation #1

**Week 5-6:**
- **Milestone 3: Second round of results and presentation**
- Further Eight (8) AI training runs completed with results compared (total 14+)
- Incorporate new data sources to help improve model
- Continue with data generation
- Deliver results for best High-Res or Low-Res image options (is high-res better?  High-res scaled? Low-res?  No difference?)
- Mid-Semester Presentation

**Week 7-8:**
- **Milestone 4: Fully automated training pipeline with constant AI training runs**
- Further Twelve (12) AI training runs completed with results compared (total 26+)
- Continue to incorporate new data sources and external data sources to model
- Docker container for model inference and training.
- Check-In Presentation #2

**Week 9-10:**
- **Milestone 5: Highly improved AI model for vehicle detection based on 10 weeks of research**
- Evidence of Constant AI model training and fine-tuning for best results based on previous 8 weeks of research and development. (total 50+ AI model training runs)
- Continue to incorporate new data sources
- Check-In Presentation #3

**Week 11-12:**
- **Milestone 6: Project Completion**
- Final Client Deployment
- End of Semester Presentation
- Handover


## Expected Deliverables
- High-res and Low-res Image Datasets: Curated datasets for construction vehicle detection.
- AI Detection Models: Trained models for both high-res and low-res images.
- Performance Metrics: Detailed performance metrics for both resolutions.
- Comparative Analysis Report: Comprehensive report documenting the experiments, results, and analysis.
- Paper Draft:  a research paper that could be published to an AI journal to share the knowledge gained on the project.
- Recommendations: Insights and recommendations on the optimal image resolution for AI-based long-range detection.
- Presentation: A final presentation summarizing the project, methodologies, findings, and conclusions.


## Resources provided by client:

You will be provided access to the client’s research infrastructure for AI training.

Any additional services or compute required will be provided on request by students.

If students have access to their own GPU hardware, that would also be great.  Training AI Models can take a very long time on laptops.  We will be discouraging this method.  This is why we provide access to GPUs when needed on the project.

Compute should not be an issue with this project.

Data will be provided to the students as well.  We have large amounts of data and are using it ourselves to train models.  We are gathering more data every day.  
