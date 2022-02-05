<div align="center">
    <h1>Data Labeling Platforms Comparison</h1>
</div>

Here is an attempt to do a fair comparison of data labeling / training data platforms.

I tried to be as accurate as possible, based on my experience with those solutions and their documentation.
If you see any mistake (this is likely), please create an issue / push a PR.

Disclaimer: I work for **Kili**.

# Table Of Content

- [Asset types](#asset-types)
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

# Asset types

## Image

Tasks / tools available to annotate images:

- Classification
- Hierarchical classification
- Bounding Box




|               | Classif. | Hierarchical classif. | Bounding Box | Polygon | Polyline | Pose estimation | Point   |
| ------------- | -------------- | --------------------------- | ------------ | ------- | -------- | --------------- | ------- |
| **Appen**         | ✔        |                         | Yes      | Yes | Yes  |             | Yes |
| **ClarifAI**      |            |                         | Yes      |     |      |             |     |
| **CVAT**          |            |                         | Yes      | Yes | Yes  | Yes         | Yes |
| **Dataloop**      | Yes        |                         | Yes      | Yes | Yes  | Yes         | Yes |
| **Hasty**         | Yes        |                         | Yes      | Yes |      |             |     |
| **Hive**          | Yes        |                         | Yes      | Yes | Yes  |             |     |
| **Innotescus**    | Yes        |                         | Yes      |     |      |             |     |
| **Kili**          | Yes        | Yes                     | Yes      | Yes | Yes  | Yes         | Yes |
| **Labelbox**      | Yes        | Yes                     | Yes      | Yes | Yes  |             | Yes |
| **LabelStudio**   | Yes        | Yes                     | Yes      | Yes | Yes  |             | Yes |
| **Playment**      | Yes        |                         | Yes      | Yes | Yes  |             | Yes |
| **Roboflow**      | Yes        |                         | Yes      |     |      |             |     |
| **Scale**         |            |                         | Yes      | Yes | Yes  |             | Yes |
| **Snorkel**       |            |                         |          |     |      |             |     |
| **SuperAnnotate** | Yes        |                         | Yes      | Yes | Yes  | Yes         | Yes |
| **Supervisely**   | Yes        | Yes                     | Yes      | Yes | Yes  | Yes         | Yes |
| **V7**            | Yes        | Yes                     | Yes      | Yes | Yes  | Yes         | Yes |

|               | Seg. | Vector Seg. | Image transcription / OCR | Object relation | Satellite | High-resolution support | DICOM support |
| ------------- | ------------ | ------------------- | ------------------------- | --------------- | --------- | ----------------------- | ------------- |
| **Appen**         | Yes      |                 |                       |             |       |                     |           |
| **ClarifAI**      | Yes      |                 | Yes                   |             |       |                     |           |
| **CVAT**          |          |                 |                       |             |       |                     |           |
| **Dataloop**      | Yes      |                 | Yes                   |             |       |                     |           |
| **Hasty**         | Yes      |                 |                       |             |       |                     |           |
| **Hive**          | Yes      |                 | Yes                   |             |       |                     |           |
| **Innotescus**    | Yes      |                 |                       |             |       |                     |           |
| **Kili**          | Yes      | Yes             | Yes                   | Yes         |       | Yes                 | Yes       |
| **Labelbox**      | Yes      |                 | Yes                   |             | Yes   |                     |           |
| **LabelStudio**   | Yes      |                 | Yes                   | Yes         |       | Yes                 | Yes       |
| **Playment**      | Yes      |                 |                       |             |       |                     |           |
| **Roboflow**      |          |                 |                       |             |       |                     |           |
| **Scale**         | Yes      |                 |                       |             |       |                     |           |
| **Snorkel**       |          |                 |                       |             |       |                     |           |
| **SuperAnnotate** | Yes      |                 |                       |             |       |                     | Yes       |
| **Supervisely**   | Yes      |                 |                       |             |       |                     |           |
| **V7**            | Yes      | Yes             | Yes                   |             |       | Yes                 | Yes       |

## Text

Task / tools available to annotate texts.

|               |         | Classification | Hierarchical classification | Named entities recognition | Relations extraction | Consensus Text |
| ------------- | ------- | -------------- | --------------------------- | -------------------------- | -------------------- | -------------- |
| **Appen**         | Yes |            | Yes                     |                        |                  |
| **ClarifAI**      | Yes |            | Yes                     |                        |                  |
| **CVAT**          |     |            |                         |                        |                  |
| **Dataloop**      | Yes |            | Yes                     | Yes                    |                  |
| **Hasty**         |     |            |                         |                        |                  |
| **Hive**          | Yes |            | Yes                     |                        |                  |
| **Innotescus**    |     |            |                         |                        |                  |
| **Kili**          | Yes | Yes        | Yes                     | Yes                    | Yes              |
| **Labelbox**      | Yes | Yes        | Yes                     | Yes                    | Yes              |
| **LabelStudio**   | Yes | Yes        | Yes                     | Yes                    | Yes              |
| **Playment**      |     |            |                         |                        |                  |
| **Roboflow**      |     |            |                         |                        |                  |
| **Scale**         |     |            |                         |                        |                  |
| **Snorkel**       | Yes |            | Yes                     | Yes                    |                  |
| **SuperAnnotate** | Yes |            | Yes                     |                        |                  |
| **Supervisely**   |     |            |                         |                        |                  |
| **V7**            | Yes | Yes        | Yes                     |                        |                  |

## PDF

Task / tools available to annotate PDFs.

|               | PDF document processing | Bounding Box on PDF | Object relation |
| ------------- | ----------------------- | ------------------- | --------------- |
| **Appen**         |                     |                 |             |
| **ClarifAI**      |                     |                 |             |
| **CVAT**          |                     |                 |             |
| **Dataloop**      |                     |                 |             |
| **Hasty**         |                     |                 |             |
| **Hive**          | Yes                 | Yes             |             |
| **Innotescus**    |                     |                 |             |
| **Kili**          | Yes                 | Yes             | Yes         |
| **Labelbox**      | Yes                 |                 |             |
| **LabelStudio**   |                     |                 | Yes         |
| **Playment**      |                     |                 |             |
| **Roboflow**      |                     |                 |             |
| **Scale**         | Yes                 |                 |             |
| **Snorkel**       | Yes                 |                 |             |
| **SuperAnnotate** |                     |                 |             |
| **Supervisely**   |                     |                 |             |
| **V7**            | Yes                 |                 |             |

## Video

Task / tools available to annotate videos.

|               | Classification | Hierarchical classification | Native Video/Frame | Classification | Object detection | Transcription |
| ------------- | -------------- | --------------------------- | ------------------ | -------------- | ---------------- | ------------- |
| **Appen**         | Yes        |                         | Yes            | Yes        | Yes          |
| **ClarifAI**      |            |                         | Yes            | Yes        |              |
| **CVAT**          |            |                         |                | Yes        |              |
| **Dataloop**      | Yes        |                         | Yes            | Yes        |              |
| **Hasty**         |            |                         |                |            |              |
| **Hive**          | Yes        |                         | Yes            | Yes        | Yes          |
| **Innotescus**    | Yes        |                         | Yes            | Yes        |              |
| **Kili**          | Yes        | Yes                     | Yes            | Yes        |              |
| **Labelbox**      | Yes        | Yes                     | Yes            | Yes        |              |
| **LabelStudio**   | Yes        | Yes                     | Yes            | Yes        | Yes          |
| **Playment**      | Yes        |                         |                | Yes        |              |
| **Roboflow**      |            |                         |                |            |              |
| **Scale**         |            |                         |                | Yes        |              |
| **Snorkel**       |            |                         |                |            |              |
| **SuperAnnotate** | Yes        |                         | Yes            | Yes        | Yes          |
| **Supervisely**   | Yes        |                         | Yes            | Yes        |              |
| **V7**            | Yes        | Yes                     | Yes            | Yes        |              |

## Audio

Task / tools available to annotate audio files.

|               | Voice transcription / Speech to text | Diarization | Ultrasound support |
| ------------- | ------------------------------------ | ----------- | ------------------ |
| **Appen**         | Yes                              |         |                |
| **ClarifAI**      |                                  |         |                |
| **CVAT**          |                                  |         |                |
| **Dataloop**      |                                  |         |                |
| **Hasty**         |                                  |         |                |
| **Hive**          | Yes                              | Yes     |                |
| **Innotescus**    |                                  |         |                |
| **Kili**          | Yes                              | Yes     |                |
| **Labelbox**      | Yes                              |         |                |
| **LabelStudio**   | Yes                              |         |                |
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
| **Kili**          | Yes        | Yes         |
| **Labelbox**      |            |             |
| **LabelStudio**   | Yes        | Yes         |
| **Playment**      |            |             |
| **Roboflow**      |            |             |
| **Scale**         |            |             |
| **Snorkel**       | Yes        | Yes         |
| **SuperAnnotate** |            |             |
| **Supervisely**   |            |             |
| **V7**            |            |             |

# Productivity Management

How to accelerate the labeling process.

|               | Interface Customization | Asset preloading | Keyboard shortcuts / Hotkeys | Workload distribution | Autosave | Labeler productivity dashboard |
| ------------- | ----------------------- | ---------------- | ---------------------------- | --------------------- | -------- | ------------------------------ |
| **Appen**         |                     |              |                          |                   |      |                            |
| **ClarifAI**      |                     |              | Yes                      |                   |      |                            |
| **CVAT**          | Yes                 |              | Yes                      |                   | Yes  |                            |
| **Dataloop**      |                     |              | Yes                      | Yes               |      | Yes                        |
| **Hasty**         |                     |              | Yes                      |                   |      |                            |
| **Hive**          |                     |              | Yes                      |                   |      | Yes                        |
| **Innotescus**    |                     |              | Yes                      |                   |      | Yes                        |
| **Kili**          | Yes                 | Yes          | Yes                      | Yes               | Yes  | Yes                        |
| **Labelbox**      | Yes                 |              | Yes                      |                   | Yes  | Yes                        |
| **LabelStudio**   | Yes                 |              | Yes                      | Yes               |      | Yes                        |
| **Playment**      |                     |              | Yes                      | Yes               |      |                            |
| **Roboflow**      |                     |              | Yes                      |                   | Yes  |                            |
| **Scale**         |                     |              |                          |                   |      |                            |
| **Snorkel**       |                     |              | Yes                      |                   |      |                            |
| **SuperAnnotate** |                     |              | Yes                      | Yes               | Yes  | Yes                        |
| **Supervisely**   | Yes                 |              | Yes                      | Yes               | Yes  |                            |
| **V7**            | Yes                 |              | Yes                      | Yes               |      | Yes                        |

# Quality management

How to make sure labels are consistent.

|               | Issue management | Consensus Image | Consensus Video | Consensus Audio |
| ------------- | ---------------- | --------------- | --------------- | --------------- |
| **Appen**         |              |             |             |             |
| **ClarifAI**      |              | Yes         |             |             |
| **CVAT**          |              |             |             |             |
| **Dataloop**      | Yes          | Yes         |             |             |
| **Hasty**         |              | Yes         |             |             |
| **Hive**          |              |             |             |             |
| **Innotescus**    |              | Yes         |             |             |
| **Kili**          | Yes          | Yes         | Yes         |             |
| **Labelbox**      | Yes          | Yes         |             |             |
| **LabelStudio**   |              | Yes         | Yes         | Yes         |
| **Playment**      |              |             |             |             |
| **Roboflow**      | Yes          | Yes         |             |             |
| **Scale**         |              |             |             |             |
| **Snorkel**       |              |             |             |             |
| **SuperAnnotate** | Yes          | Yes         |             |             |
| **Supervisely**   | Yes          | Yes         |             |             |
| **V7**            |              | Yes         |             |             |

# Dataset management

How to managed and export the dataset.

|               | Data hub | Version control | Public project | ML export formats |
| ------------- | -------- | --------------- | -------------- | ----------------- |
| **Appen**         |      |             |            | Yes           |
| **ClarifAI**      |      |             |            |               |
| **CVAT**          |      |             |            | Yes           |
| **Dataloop**      | Yes  | Yes         |            | Yes           |
| **Hasty**         |      |             |            | Yes           |
| **Hive**          |      |             |            |               |
| **Innotescus**    |      |             |            |               |
| **Kili**          | Yes  | Yes         | Yes        | Yes           |
| **Labelbox**      |      |             |            |               |
| **LabelStudio**   |      |             |            | Yes           |
| **Playment**      |      |             |            | Yes           |
| **Roboflow**      | Yes  | Yes         |            | Yes           |
| **Scale**         |      |             |            | Yes           |
| **Snorkel**       |      |             |            |               |
| **SuperAnnotate** |      |             |            | Yes           |
| **Supervisely**   |      |             |            | Yes           |
| **V7**            | Yes  | Yes         |            | Yes           |

# API

How to programmatically interact with the tool.

|               | GraphQL API | Messaging bus API | CLI SDK | Python SDK |
| ------------- | ----------- | ----------------- | ------- | ---------- |
| **Appen**         |         |               |     |        |
| **ClarifAI**      |         |               |     | Yes    |
| **CVAT**          |         |               |     |        |
| **Dataloop**      |         |               |     | Yes    |
| **Hasty**         |         |               |     |        |
| **Hive**          |         |               |     | Yes    |
| **Innotescus**    |         |               |     |        |
| **Kili**          | Yes     | Yes           |     | Yes    |
| **Labelbox**      | Yes     |               |     | Yes    |
| **LabelStudio**   |         |               |     | Yes    |
| **Playment**      |         |               |     | Yes    |
| **Roboflow**      |         |               |     | Yes    |
| **Scale**         |         |               |     | Yes    |
| **Snorkel**       |         |               |     |        |
| **SuperAnnotate** |         |               |     | Yes    |
| **Supervisely**   |         |               |     | Yes    |
| **V7**            |         |               | Yes | Yes    |

# Deployment

The different options to deploy the tool.

|               | On-premise data | On-premise deployment | Air gap deployment |
| ------------- | --------------- | --------------------- | ------------------ |
| **Appen**         |             |                   |                |
| **ClarifAI**      |             | Yes               | Yes            |
| **CVAT**          |             | Yes               | Yes            |
| **Dataloop**      |             | Yes               |                |
| **Hasty**         |             |                   |                |
| **Hive**          |             |                   |                |
| **Innotescus**    |             |                   |                |
| **Kili**          | Yes         | Yes               | Yes            |
| **Labelbox**      | Yes         | Yes               |                |
| **LabelStudio**   |             | Yes               | Yes            |
| **Playment**      |             |                   |                |
| **Roboflow**      |             | Yes               |                |
| **Scale**         |             |                   |                |
| **Snorkel**       |             | Yes               |                |
| **SuperAnnotate** |             |                   |                |
| **Supervisely**   |             | Yes               |                |
| **V7**            |             |                   |                |

# Automation

The offering in terms of labeling automation.

|               | Model-assisted labeling | Model based preannotation | Queue prioritisation | Model Training | Model Inference |
| ------------- | ----------------------- | ------------------------- | -------------------- | -------------- | --------------- |
| **Appen**         | Yes                 | Yes                   |                  | Yes        |             |
| **ClarifAI**      | Yes                 | Yes                   | Yes              |            |             |
| **CVAT**          |                     |                       |                  |            |             |
| **Dataloop**      | Yes                 | Yes                   |                  |            |             |
| **Hasty**         | Yes                 | Yes                   |                  | Yes        | Yes         |
| **Hive**          |                     |                       |                  |            |             |
| **Innotescus**    | Yes                 |                       |                  |            |             |
| **Kili**          | Yes                 | Yes                   | Yes              | Yes        |             |
| **Labelbox**      | Yes                 | Yes                   | Yes              |            |             |
| **LabelStudio**   |                     | Yes                   |                  |            |             |
| **Playment**      | Yes                 |                       |                  |            |             |
| **Roboflow**      | Yes                 |                       |                  | Yes        | Yes         |
| **Scale**         | Yes                 | Yes                   |                  |            |             |
| **Snorkel**       | Yes                 |                       |                  | Yes        | Yes         |
| **SuperAnnotate** | Yes                 | Yes                   |                  | Yes        |             |
| **Supervisely**   | Yes                 | Yes                   |                  |            |             |
| **V7**            | Yes                 |                       |                  | Yes        | Yes         |

# Workforce

Availability of workforce to help labeling

|               | Human in the loop | External workforce | On-premise external workforce |
| ------------- | ----------------- | ------------------ | ----------------------------- |
| **Appen**         |               | Yes            |                           |
| **ClarifAI**      |               |                |                           |
| **CVAT**          |               |                |                           |
| **Dataloop**      |               |                |                           |
| **Hasty**         |               |                |                           |
| **Hive**          |               |                |                           |
| **Innotescus**    |               |                |                           |
| **Kili**          | Yes           | Yes            | Yes                       |
| **Labelbox**      |               | Yes            |                           |
| **LabelStudio**   |               |                |                           |
| **Playment**      |               |                |                           |
| **Roboflow**      |               |                |                           |
| **Scale**         |               | Yes            |                           |
| **Snorkel**       |               |                |                           |
| **SuperAnnotate** |               |                |                           |
| **Supervisely**   |               |                |                           |
| **V7**            |               |                |                           |

# Security

Security certificates.

|               | HIPAA Compliance | SOC 2 Compliance |
| ------------- | ---------------- | ---------------- |
| **Appen**         | Yes          | Yes          |
| **ClarifAI**      | Yes          | Yes          |
| **CVAT**          |              |              |
| **Dataloop**      |              | Yes          |
| **Hasty**         |              |              |
| **Hive**          |              |              |
| **Innotescus**    |              |              |
| **Kili**          |              | Yes          |
| **Labelbox**      | Yes          | Yes          |
| **LabelStudio**   |              |              |
| **Playment**      |              | Yes          |
| **Roboflow**      | Yes          | Yes          |
| **Scale**         | Yes          | Yes          |
| **Snorkel**       |              |              |
| **SuperAnnotate** |              |              |
| **Supervisely**   |              |              |
| **V7**            | Yes          | Yes          |
