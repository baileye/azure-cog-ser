# azure-cog-ser
Azure Congitive Services workshop - follow the steps and set up a smart search over a set of images. Including building a custom ML model

# Requirements
Make sure you have the following set up before you start this walkthrough:
 - An [Azure account](http://portal.azure.com/)
 - Access to [Azure Cognitive Services](https://azure.microsoft.com/en-us/services/cognitive-services/)
 - Internet access on your laptop
 - Access to this repo

In this walkthrough we will set up Azure Search over a collection of images. We will add metadata to the search index for each image by utilising Azure Cognitive Services.  

# TODO
 - Image dataset - chicago art institute
   - Azure vision service
   - classifier model, etching versus paing
   - object detection
   - OCR
   - Entity analysis (from text)
   - Logo detection (from images)
 - Cog Ser setup steps
 - Cog ser custom models
   - Classifier
   - Object detection
   - OCR
   - Entity analysis
   - Logo detection
 - Azure functions code
   - Parameters for storage access and container, Azure search API endpoints, Cognitive services API endpoints
   - Triggered from storage
   - Query Azure Search API
   - Update Azure search index based on filename
 - Azure storage set up
 - Azure search steps
   - API calls for testing
