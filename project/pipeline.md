# Building multi-stage AI pipelines for vision systems

This project involves developing multi-stage AI pipelines that leverage different AI models in sequence to achieve more accurate object classification. The concept is to use an initial model to perform a broad classification (e.g., identifying a light vehicle) and then feed the result into subsequent models that perform more specific classifications (e.g., distinguishing between a bus, car, van, ute, etc.).

## Description

Multi-stage AI pipelines can help with the speed of classification by reducing the number of parameters.   Models that classify smaller numbers of classes are also typically smaller.  Leveraging this, using a model for doing a ‘rough’ classification step, then multiple specialist models for fine-grained classification should yield much better (and faster results).

You will be using publicly available datasets for different vehicles.  The client has already selected which ones to start with.  Your goal is to build and select the most appropriate model for each classification and map these results against the previous existing model.

The team running this capstone project expects that you will need to learn lots on the project.  We have the experience to help you with the project and teach you more about AI, software design and best practices.   Making you the best developers out there.  

If you have an interest in the AI field or computer vision or are looking at getting a deep understanding of how AI companies operate, this is the project for you and your team.

AI is a fast-growing area, ensuring that we have accurate and reliable detection is vital to the success of the project.  If you have an interest in working on new areas of research in the AI space, this is the project for you.

## Scope
- Design and implement a multi-stage AI pipeline for object classification.
- Develop or select pre-trained models for initial broad classification and subsequent detailed classification.
- Integrate the models into a cohesive pipeline that ensures seamless data flow and processing.
- Optimize the pipeline for accuracy and efficiency.
- Test and validate the pipeline in various real-world scenarios.


## Resources
- [YOLO Model Guides](https://docs.ultralytics.com/guides/)

## Timeline

**Week 1-2:**
- **Milestone 1: On-boarded and Dataset completed**
- Introduction and regular meeting schedule
- Access to High-Performance Compute ready
- Sample model training up and running on compute
- Datasets researched and organised
- GitHub repo ready
- Two (2) AI model training runs completed (on sample data)
- Web portal started

**Week 3-4:**
- **Milestone 2: First round of results and presentation.**
- Four (4) AI Model training runs completed with results compared
- Create validation dataset for comparing each model’s performance
- Create testing framework for rapid and automated testing of each model performance
- Image augmentation and dataset expansion to improve future model results
- Augment the dataset to increase variability and robustness.
- Research additional data sources from online
- GitHub workflows established (both automated and team review process).
- Check-In Presentation #1

**Week 5-6:**
- **Milestone 3: Second round of results and presentation**
- Further Six (6) AI training runs completed with results compared (total 10+)
- Pipelining up and running to improve reliability for 2 subclasses.
- Incorporate new data sources to help improve model
- Continue with data generation
- Mid-Semester Presentation

**Week 7-8:**
- **Milestone 4: Fully automated training pipeline with constant AI training runs**
- Further Eight (8) AI training runs completed with results compared (total 18+)
- Continue to incorporate new data sources and external data sources to model
- Pipelining up and running to improve reliability for 4 subclasses.
- Docker container for model inference and training.
- Check-In Presentation #2

**Week 9-10:**
- **Milestone 5: Pipeling working reliability for multiple sub-classes and more**
- Evidence of Constant AI model training and fine-tuning for best results based on previous 8 weeks of research and development. (total 30+ AI model training runs)
- Pipelining up and running to improve reliability for 8 subclasses.
- Continue to incorporate new data sources
- Check-In Presentation #3

**Week 11-12:**
- **Milestone 6: Project Completion**
- Final Client Deployment
- End of Semester Presentation
- Handover


## Expected Deliverables
- Multi-Stage AI Pipeline: A functional pipeline capable of broad and detailed object classification.
- Performance Metrics: Metrics demonstrating the accuracy and efficiency of the pipeline.
- Documentation: Detailed guides on installation, configuration, and usage of the pipeline.
- Source Code: Open-source codebase for community use and contribution.
- Paper Draft:  a research paper that could be published to an AI journal to share the knowledge gained on the project.
- Comprehensive Report: A report documenting the project, methodologies, experiments, results, and recommendations.
- Presentation: A final presentation summarizing the project, methodologies, findings, and conclusions.



## Resources provided by client:

You will be provided access to the client’s research infrastructure for AI training.

Any additional services or compute required will be provided on request by students.

If students have access to their own GPU hardware, that would also be great.  Training AI Models can take a very long time on laptops.  We will be discouraging this method.  This is why we provide access to GPUs when needed on the project.

Compute should not be an issue with this project.

Data will be provided to the students as well.  We have large amounts of data and are using it ourselves to train models.  We are gathering more data every day.  
