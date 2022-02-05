<div align="center">
    <h1>Data Labeling Platforms Comparison</h1>
</div>

Data labeling is a hot topic as a recent report from AI research and advisory firm Cognilytica found that over 80% of the time enterprises spend on AI projects goes toward preparing, cleaning and labeling data.

A new category of tools has emerged, called data labeling platforms, training data management platforms. Three years ago, this market did not exist. Today, the offer is plentiful and it is sometimes complicated to find one's way.

A good annotation tool must meet three needs:

- annotate quickly (productivity of annotators)
- annotate well (control the quality / consistency of annotations)
- annotate the right data (source diversity in the dataset)

Here is an attempt to do a fair comparison of data labeling / training data platforms.

I tried to be as accurate as possible, based on my experience with those solutions and their documentation.
If you see any mistake (this is likely), please create an issue / push a PR.


# Table Of Content

- [Tasks / tools by asset type](#tasks-tools-by-asset-type)
  - [Image](#image)
  - [Text](#text)
  - [PDF](#pdf)
  - [Video](#video)
  - [Audio](#audio)
  - [Timeserie](#timeserie)
- [Productivity Management](#productivity-management)
- [Quality management](#quality-management)
- [Dataset management](#dataset-management)
- [API](#api)
- [Deployment](#deployment)
- [Automation](#automation)
- [Workforce](#workforce)
- [Security](#security)

# Tasks / tools by asset type

## Image

The criteria are as follows:

- Classification
- Hierarchical classification
- Bounding Box
- Bounding Box
- Polygon
- Polyline
- Pose estimation
- Point
- Segmentation
- Vector Segmentation
- Image transcription / OCR
- Object relation
- Satellite imagery support
- High-resolution support
- DICOM support


|               | Classif. | Hierarchical classif. | Bounding Box | Polygon | Polyline | Pose estimation | Point   |
| ------------- | -------------- | --------------------------- | ------------ | ------- | -------- | --------------- | ------- |
| **Appen**         | ✔        |                         | ✔      | ✔ | ✔  |             | ✔ |
| **ClarifAI**      |            |                         | ✔      |     |      |             |     |
| **CVAT**          |            |                         | ✔      | ✔ | ✔  | ✔         | ✔ |
| **Dataloop**      | ✔        |                         | ✔      | ✔ | ✔  | ✔         | ✔ |
| **Hasty**         | ✔        |                         | ✔      | ✔ |      |             |     |
| **Hive**          | ✔        |                         | ✔      | ✔ | ✔  |             |     |
| **Innotescus**    | ✔        |                         | ✔      |     |      |             |     |
| **Kili**          | ✔        | ✔                     | ✔      | ✔ | ✔  | ✔         | ✔ |
| **Labelbox**      | ✔        | ✔                     | ✔      | ✔ | ✔  |             | ✔ |
| **LabelStudio**   | ✔        | ✔                     | ✔      | ✔ | ✔  |             | ✔ |
| **Playment**      | ✔        |                         | ✔      | ✔ | ✔  |             | ✔ |
| **Roboflow**      | ✔        |                         | ✔      |     |      |             |     |
| **Scale**         |            |                         | ✔      | ✔ | ✔  |             | ✔ |
| **Snorkel**       |            |                         |          |     |      |             |     |
| **SuperAnnotate** | ✔        |                         | ✔      | ✔ | ✔  | ✔         | ✔ |
| **Supervisely**   | ✔        | ✔                     | ✔      | ✔ | ✔  | ✔         | ✔ |
| **V7**            | ✔        | ✔                     | ✔      | ✔ | ✔  | ✔         | ✔ |

|               | Seg. | Vector Seg. | Image transcription / OCR | Object relation | Satellite | High-resolution support | DICOM support |
| ------------- | ------------ | ------------------- | ------------------------- | --------------- | --------- | ----------------------- | ------------- |
| **Appen**         | ✔      |                 |                       |             |       |                     |           |
| **ClarifAI**      | ✔      |                 | ✔                   |             |       |                     |           |
| **CVAT**          |          |                 |                       |             |       |                     |           |
| **Dataloop**      | ✔      |                 | ✔                   |             |       |                     |           |
| **Hasty**         | ✔      |                 |                       |             |       |                     |           |
| **Hive**          | ✔      |                 | ✔                   |             |       |                     |           |
| **Innotescus**    | ✔      |                 |                       |             |       |                     |           |
| **Kili**          | ✔      | ✔             | ✔                   | ✔         |       | ✔                 | ✔       |
| **Labelbox**      | ✔      |                 | ✔                   |             | ✔   |                     |           |
| **LabelStudio**   | ✔      |                 | ✔                   | ✔         |       | ✔                 | ✔       |
| **Playment**      | ✔      |                 |                       |             |       |                     |           |
| **Roboflow**      |          |                 |                       |             |       |                     |           |
| **Scale**         | ✔      |                 |                       |             |       |                     |           |
| **Snorkel**       |          |                 |                       |             |       |                     |           |
| **SuperAnnotate** | ✔      |                 |                       |             |       |                     | ✔       |
| **Supervisely**   | ✔      |                 |                       |             |       |                     |           |
| **V7**            | ✔      | ✔             | ✔                   |             |       | ✔                 | ✔       |

## Text

Task / tools available to annotate texts.

|               |         | Classification | Hierarchical classification | Named entities recognition | Relations extraction | Consensus Text |
| ------------- | ------- | -------------- | --------------------------- | -------------------------- | -------------------- | -------------- |
| **Appen**         | ✔ |            | ✔                     |                        |                  |
| **ClarifAI**      | ✔ |            | ✔                     |                        |                  |
| **CVAT**          |     |            |                         |                        |                  |
| **Dataloop**      | ✔ |            | ✔                     | ✔                    |                  |
| **Hasty**         |     |            |                         |                        |                  |
| **Hive**          | ✔ |            | ✔                     |                        |                  |
| **Innotescus**    |     |            |                         |                        |                  |
| **Kili**          | ✔ | ✔        | ✔                     | ✔                    | ✔              |
| **Labelbox**      | ✔ | ✔        | ✔                     | ✔                    | ✔              |
| **LabelStudio**   | ✔ | ✔        | ✔                     | ✔                    | ✔              |
| **Playment**      |     |            |                         |                        |                  |
| **Roboflow**      |     |            |                         |                        |                  |
| **Scale**         |     |            |                         |                        |                  |
| **Snorkel**       | ✔ |            | ✔                     | ✔                    |                  |
| **SuperAnnotate** | ✔ |            | ✔                     |                        |                  |
| **Supervisely**   |     |            |                         |                        |                  |
| **V7**            | ✔ | ✔        | ✔                     |                        |                  |

## PDF

Task / tools available to annotate PDFs.

|               | PDF document processing | Bounding Box on PDF | Object relation |
| ------------- | ----------------------- | ------------------- | --------------- |
| **Appen**         |                     |                 |             |
| **ClarifAI**      |                     |                 |             |
| **CVAT**          |                     |                 |             |
| **Dataloop**      |                     |                 |             |
| **Hasty**         |                     |                 |             |
| **Hive**          | ✔                 | ✔             |             |
| **Innotescus**    |                     |                 |             |
| **Kili**          | ✔                 | ✔             | ✔         |
| **Labelbox**      | ✔                 |                 |             |
| **LabelStudio**   |                     |                 | ✔         |
| **Playment**      |                     |                 |             |
| **Roboflow**      |                     |                 |             |
| **Scale**         | ✔                 |                 |             |
| **Snorkel**       | ✔                 |                 |             |
| **SuperAnnotate** |                     |                 |             |
| **Supervisely**   |                     |                 |             |
| **V7**            | ✔                 |                 |             |

## Video

Task / tools available to annotate videos.

|               | Classif. | Hierarchical classif. | Native Video/Frame | Classification | Object detection | Transcription |
| ------------- | -------------- | --------------------------- | ------------------ | -------------- | ---------------- | ------------- |
| **Appen**         | ✔        |                         | ✔            | ✔        | ✔          |
| **ClarifAI**      |            |                         | ✔            | ✔        |              |
| **CVAT**          |            |                         |                | ✔        |              |
| **Dataloop**      | ✔        |                         | ✔            | ✔        |              |
| **Hasty**         |            |                         |                |            |              |
| **Hive**          | ✔        |                         | ✔            | ✔        | ✔          |
| **Innotescus**    | ✔        |                         | ✔            | ✔        |              |
| **Kili**          | ✔        | ✔                     | ✔            | ✔        |              |
| **Labelbox**      | ✔        | ✔                     | ✔            | ✔        |              |
| **LabelStudio**   | ✔        | ✔                     | ✔            | ✔        | ✔          |
| **Playment**      | ✔        |                         |                | ✔        |              |
| **Roboflow**      |            |                         |                |            |              |
| **Scale**         |            |                         |                | ✔        |              |
| **Snorkel**       |            |                         |                |            |              |
| **SuperAnnotate** | ✔        |                         | ✔            | ✔        | ✔          |
| **Supervisely**   | ✔        |                         | ✔            | ✔        |              |
| **V7**            | ✔        | ✔                     | ✔            | ✔        |              |

## Audio

Task / tools available to annotate audio files.

|               | Voice transcription / Speech to text | Diarization | Ultrasound support |
| ------------- | ------------------------------------ | ----------- | ------------------ |
| **Appen**         | ✔                              |         |                |
| **ClarifAI**      |                                  |         |                |
| **CVAT**          |                                  |         |                |
| **Dataloop**      |                                  |         |                |
| **Hasty**         |                                  |         |                |
| **Hive**          | ✔                              | ✔     |                |
| **Innotescus**    |                                  |         |                |
| **Kili**          | ✔                              | ✔     |                |
| **Labelbox**      | ✔                              |         |                |
| **LabelStudio**   | ✔                              |         |                |
| **Playment**      |                                  |         |                |
| **Roboflow**      |                                  |         |                |
| **Scale**         |                                  |         |                |
| **Snorkel**       |                                  |         |                |
| **SuperAnnotate** |                                  |         |                |
| **Supervisely**   |                                  |         |                |
| **V7**            |                                  |         |                |

## Timeserie

Task / tools available to annotate timeseries.

|               | Classification | Range detection |
| ------------- | -------------- | --------------- |
| **Appen**         |            |             |
| **ClarifAI**      |            |             |
| **CVAT**          |            |             |
| **Dataloop**      |            |             |
| **Hasty**         |            |             |
| **Hive**          |            |             |
| **Innotescus**    |            |             |
| **Kili**          | ✔        | ✔         |
| **Labelbox**      |            |             |
| **LabelStudio**   | ✔        | ✔         |
| **Playment**      |            |             |
| **Roboflow**      |            |             |
| **Scale**         |            |             |
| **Snorkel**       | ✔        | ✔         |
| **SuperAnnotate** |            |             |
| **Supervisely**   |            |             |
| **V7**            |            |             |

# Productivity Management

How to accelerate the labeling process.

|               | Interface Customization | Asset preloading | Keyboard shortcuts / Hotkeys | Workload distribution | Autosave | Labeler productivity dashboard |
| ------------- | ----------------------- | ---------------- | ---------------------------- | --------------------- | -------- | ------------------------------ |
| **Appen**         |                     |              |                          |                   |      |                            |
| **ClarifAI**      |                     |              | ✔                      |                   |      |                            |
| **CVAT**          | ✔                 |              | ✔                      |                   | ✔  |                            |
| **Dataloop**      |                     |              | ✔                      | ✔               |      | ✔                        |
| **Hasty**         |                     |              | ✔                      |                   |      |                            |
| **Hive**          |                     |              | ✔                      |                   |      | ✔                        |
| **Innotescus**    |                     |              | ✔                      |                   |      | ✔                        |
| **Kili**          | ✔                 | ✔          | ✔                      | ✔               | ✔  | ✔                        |
| **Labelbox**      | ✔                 |              | ✔                      |                   | ✔  | ✔                        |
| **LabelStudio**   | ✔                 |              | ✔                      | ✔               |      | ✔                        |
| **Playment**      |                     |              | ✔                      | ✔               |      |                            |
| **Roboflow**      |                     |              | ✔                      |                   | ✔  |                            |
| **Scale**         |                     |              |                          |                   |      |                            |
| **Snorkel**       |                     |              | ✔                      |                   |      |                            |
| **SuperAnnotate** |                     |              | ✔                      | ✔               | ✔  | ✔                        |
| **Supervisely**   | ✔                 |              | ✔                      | ✔               | ✔  |                            |
| **V7**            | ✔                 |              | ✔                      | ✔               |      | ✔                        |

# Quality management

How to make sure labels are consistent.

|               | Issue management | Consensus Image | Consensus Video | Consensus Audio |
| ------------- | ---------------- | --------------- | --------------- | --------------- |
| **Appen**         |              |             |             |             |
| **ClarifAI**      |              | ✔         |             |             |
| **CVAT**          |              |             |             |             |
| **Dataloop**      | ✔          | ✔         |             |             |
| **Hasty**         |              | ✔         |             |             |
| **Hive**          |              |             |             |             |
| **Innotescus**    |              | ✔         |             |             |
| **Kili**          | ✔          | ✔         | ✔         |             |
| **Labelbox**      | ✔          | ✔         |             |             |
| **LabelStudio**   |              | ✔         | ✔         | ✔         |
| **Playment**      |              |             |             |             |
| **Roboflow**      | ✔          | ✔         |             |             |
| **Scale**         |              |             |             |             |
| **Snorkel**       |              |             |             |             |
| **SuperAnnotate** | ✔          | ✔         |             |             |
| **Supervisely**   | ✔          | ✔         |             |             |
| **V7**            |              | ✔         |             |             |

# Dataset management

How to managed and export the dataset.

|               | Data hub | Version control | Public project | ML export formats |
| ------------- | -------- | --------------- | -------------- | ----------------- |
| **Appen**         |      |             |            | ✔           |
| **ClarifAI**      |      |             |            |               |
| **CVAT**          |      |             |            | ✔           |
| **Dataloop**      | ✔  | ✔         |            | ✔           |
| **Hasty**         |      |             |            | ✔           |
| **Hive**          |      |             |            |               |
| **Innotescus**    |      |             |            |               |
| **Kili**          | ✔  | ✔         | ✔        | ✔           |
| **Labelbox**      |      |             |            |               |
| **LabelStudio**   |      |             |            | ✔           |
| **Playment**      |      |             |            | ✔           |
| **Roboflow**      | ✔  | ✔         |            | ✔           |
| **Scale**         |      |             |            | ✔           |
| **Snorkel**       |      |             |            |               |
| **SuperAnnotate** |      |             |            | ✔           |
| **Supervisely**   |      |             |            | ✔           |
| **V7**            | ✔  | ✔         |            | ✔           |

# API

How to programmatically interact with the tool.

|               | GraphQL API | Messaging bus API | CLI SDK | Python SDK |
| ------------- | ----------- | ----------------- | ------- | ---------- |
| **Appen**         |         |               |     |        |
| **ClarifAI**      |         |               |     | ✔    |
| **CVAT**          |         |               |     |        |
| **Dataloop**      |         |               |     | ✔    |
| **Hasty**         |         |               |     |        |
| **Hive**          |         |               |     | ✔    |
| **Innotescus**    |         |               |     |        |
| **Kili**          | ✔     | ✔           |     | ✔    |
| **Labelbox**      | ✔     |               |     | ✔    |
| **LabelStudio**   |         |               |     | ✔    |
| **Playment**      |         |               |     | ✔    |
| **Roboflow**      |         |               |     | ✔    |
| **Scale**         |         |               |     | ✔    |
| **Snorkel**       |         |               |     |        |
| **SuperAnnotate** |         |               |     | ✔    |
| **Supervisely**   |         |               |     | ✔    |
| **V7**            |         |               | ✔ | ✔    |

# Deployment

The different options to deploy the tool.

|               | On-premise data | On-premise deployment | Air gap deployment |
| ------------- | --------------- | --------------------- | ------------------ |
| **Appen**         |             |                   |                |
| **ClarifAI**      |             | ✔               | ✔            |
| **CVAT**          |             | ✔               | ✔            |
| **Dataloop**      |             | ✔               |                |
| **Hasty**         |             |                   |                |
| **Hive**          |             |                   |                |
| **Innotescus**    |             |                   |                |
| **Kili**          | ✔         | ✔               | ✔            |
| **Labelbox**      | ✔         | ✔               |                |
| **LabelStudio**   |             | ✔               | ✔            |
| **Playment**      |             |                   |                |
| **Roboflow**      |             | ✔               |                |
| **Scale**         |             |                   |                |
| **Snorkel**       |             | ✔               |                |
| **SuperAnnotate** |             |                   |                |
| **Supervisely**   |             | ✔               |                |
| **V7**            |             |                   |                |

# Automation

The offering in terms of labeling automation.

|               | Model-assisted labeling | Model based preannotation | Queue prioritisation | Model Training | Model Inference |
| ------------- | ----------------------- | ------------------------- | -------------------- | -------------- | --------------- |
| **Appen**         | ✔                 | ✔                   |                  | ✔        |             |
| **ClarifAI**      | ✔                 | ✔                   | ✔              |            |             |
| **CVAT**          |                     |                       |                  |            |             |
| **Dataloop**      | ✔                 | ✔                   |                  |            |             |
| **Hasty**         | ✔                 | ✔                   |                  | ✔        | ✔         |
| **Hive**          |                     |                       |                  |            |             |
| **Innotescus**    | ✔                 |                       |                  |            |             |
| **Kili**          | ✔                 | ✔                   | ✔              | ✔        |             |
| **Labelbox**      | ✔                 | ✔                   | ✔              |            |             |
| **LabelStudio**   |                     | ✔                   |                  |            |             |
| **Playment**      | ✔                 |                       |                  |            |             |
| **Roboflow**      | ✔                 |                       |                  | ✔        | ✔         |
| **Scale**         | ✔                 | ✔                   |                  |            |             |
| **Snorkel**       | ✔                 |                       |                  | ✔        | ✔         |
| **SuperAnnotate** | ✔                 | ✔                   |                  | ✔        |             |
| **Supervisely**   | ✔                 | ✔                   |                  |            |             |
| **V7**            | ✔                 |                       |                  | ✔        | ✔         |

# Workforce

Availability of workforce to help labeling

|               | Human in the loop | External workforce | On-premise external workforce |
| ------------- | ----------------- | ------------------ | ----------------------------- |
| **Appen**         |               | ✔            |                           |
| **ClarifAI**      |               |                |                           |
| **CVAT**          |               |                |                           |
| **Dataloop**      |               |                |                           |
| **Hasty**         |               |                |                           |
| **Hive**          |               |                |                           |
| **Innotescus**    |               |                |                           |
| **Kili**          | ✔           | ✔            | ✔                       |
| **Labelbox**      |               | ✔            |                           |
| **LabelStudio**   |               |                |                           |
| **Playment**      |               |                |                           |
| **Roboflow**      |               |                |                           |
| **Scale**         |               | ✔            |                           |
| **Snorkel**       |               |                |                           |
| **SuperAnnotate** |               |                |                           |
| **Supervisely**   |               |                |                           |
| **V7**            |               |                |                           |

# Security

Security certificates.

|               | HIPAA Compliance | SOC 2 Compliance |
| ------------- | ---------------- | ---------------- |
| **Appen**         | ✔          | ✔          |
| **ClarifAI**      | ✔          | ✔          |
| **CVAT**          |              |              |
| **Dataloop**      |              | ✔          |
| **Hasty**         |              |              |
| **Hive**          |              |              |
| **Innotescus**    |              |              |
| **Kili**          |              | ✔          |
| **Labelbox**      | ✔          | ✔          |
| **LabelStudio**   |              |              |
| **Playment**      |              | ✔          |
| **Roboflow**      | ✔          | ✔          |
| **Scale**         | ✔          | ✔          |
| **Snorkel**       |              |              |
| **SuperAnnotate** |              |              |
| **Supervisely**   |              |              |
| **V7**            | ✔          | ✔          |
