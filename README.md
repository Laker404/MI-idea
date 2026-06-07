# EcoSort: AI assistant for waste sorting
Building AI course project - an idea for an AI project

## Summary
EcoSort is a computer vision-based app. The user takes a photo of an item, and the AI identifies its material (plastic, paper, glass) and suggests the correct recycling bin.

## Background
People often make mistakes when sorting waste, which leads to contamination of recyclable materials at recycling plants.
* **Problem:** Low levels of environmental awareness and confusing labelling.
* **Frequency:** Occurs daily in everyday life.
* **Motivation:** To simplify the process of separate waste collection for ordinary people.

## How is it used?
The app is used at home or outdoors before disposing of rubbish.
* **Users:** Anyone who wants to sort their rubbish but isn’t sure of the rules.
* **Process:** Open the app -> take a photo -> get instructions.

## Data sources and AI methods
The project utilises pre-existing datasets and machine vision techniques.
| Component | Details |
| ----------- | ----------- |
| **Data sources** | Open datasets containing images of litter. |
| **AI methods** | Deep learning for image classification. |

## Challenges
AI may struggle to recognise crumpled, dirty or mixed packaging; furthermore, users’ photos must not contain any personal information that appears in the frame
Main issue: The project does not provide the necessary infrastructure (the collection bins themselves).

## What next?
Addition of an interactive map showing the nearest collection points for hazardous waste (batteries, light bulbs). Introduction of a points system for correct waste sorting.
