# 🚆 TransitFind AI — AI-Powered Lost and Found Platform

## 📌 Project Overview

**TransitFind AI** is an AI-powered lost-and-found platform designed to help passengers recover lost belongings on public transportation, including buses, trains, metro systems, and terminals.

The platform uses **computer vision, image similarity, and contextual information** to match lost-item reports with registered found items. Passengers can upload an image of their lost belongings along with details such as item category, color, route, location, date, and time. Transport staff can register found items using the same process.

The system analyzes visual features and relevant contextual information to rank potential matches, helping passengers and transport authorities reduce the time and effort required to recover lost belongings.

## 🎯 Problem Statement

Traditional lost-and-found systems often rely on manual logbooks, phone calls, and written descriptions. These methods can be time-consuming, inefficient, and unreliable, especially when passengers cannot accurately describe their lost belongings.

TransitFind AI aims to address these challenges through automated image-based matching and centralized lost-and-found management.

## ✨ Key Features

- **Image-Based Item Matching:** Compare images of lost and found belongings using AI-based visual similarity.
- **Lost Item Reporting:** Allow passengers to submit item images and relevant travel details.
- **Found Item Registration:** Enable transport staff to register found belongings with images and discovery information.
- **Context-Aware Matching:** Use item category, color, route, location, date, and time to improve match relevance.
- **Similarity Ranking:** Rank potential matches to help users identify the most relevant results.
- **Centralized Database:** Maintain lost-and-found records across multiple stations and routes.
- **Ownership Verification:** Verify ownership details before returning a recovered item.
- **Improved User Experience:** Reduce dependency on manual descriptions and paperwork.

## 🧠 AI and Machine Learning Approach

The proposed system follows a multimodal matching approach:

1. **Image Feature Extraction:** Use models such as MobileNet, ResNet, or CLIP to generate image embeddings.
2. **Text Feature Extraction:** Use models such as Sentence-BERT (SBERT) or CLIP to represent textual descriptions.
3. **Similarity Calculation:** Apply cosine similarity to compare image and text embeddings.
4. **Contextual Matching:** Incorporate route, location, and time information.
5. **Final Match Scoring:** Combine image, text, location, and time similarity scores.
6. **Match Ranking:** Display potential matches in descending order of relevance.
7. **Verification and Notification:** Verify ownership and notify the user about a suitable match.

The proposed final matching score is:

`S = w1 × S_image + w2 × S_text + w3 × S_location + w4 × S_time`

Here, the weights determine the importance of each similarity component.

## 🛠️ Proposed Technology Stack

- **Artificial Intelligence:** Computer Vision, Deep Learning
- **Image Models:** MobileNet, ResNet, CLIP
- **Text Embeddings:** Sentence-BERT (SBERT), CLIP
- **Similarity Measurement:** Cosine Similarity
- **Data Management:** Centralized database
- **Application Platform:** Web-based application

*Note: The final technology stack will depend on the implementation.*

## 🌍 Scope of the Project

- Supports lost-and-found management for buses, trains, metro stations, and terminals.
- Covers common belongings such as bags, mobile phones, wallets, and accessories.
- Connects passenger-side lost-item reporting with staff-side found-item registration.
- Focuses on image-based matching and contextual information.
- Does not include GPS-based tracking or real-time physical item location.

## 🚀 Expected Benefits

- Faster recovery of lost belongings.
- Reduced manual workload for transport staff.
- Better matching accuracy than relying only on written descriptions.
- Centralized management of lost-and-found records.
- Improved passenger satisfaction and trust in public transportation services.

## 🔮 Future Enhancements

- Real-time notifications for potential matches.
- Mobile application for passengers and transport staff.
- Multilingual support for item descriptions.
- Integration with public transportation management systems.
- Improved matching models using additional real-world data.
- Secure authentication and enhanced ownership verification.

## 👨‍💻 Project Information

- **Project Name:** TransitFind AI
- **Domain:** Artificial Intelligence and Machine Learning
- **Project Type:** Academic Project — Stage I
- **Application Area:** Public Transportation
- **Core Concept:** AI-powered image matching for lost-and-found management

## 🤝 Contributors

- Aditya Dattu Kadam
- Ishwari Pramod Jawak
- Vaishnavi Ashok Kokate
- Mansi Mukund Kondhare

## 📄 Project Status

**Stage I — Project Proposal and System Design**

The project focuses on defining the problem, researching existing approaches, and designing the proposed AI-based matching workflow. Implementation details and the final technology stack will be updated as development progresses.
