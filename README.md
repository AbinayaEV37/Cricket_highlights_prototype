# AI-Based Cricket Highlights Generator

## Project Description
This project automatically generates cricket highlights from a full-length cricket match video using video processing and rule-based event filtering techniques.

The system analyzes the match footage, detects important moments based on visual and event-based filtering, and automatically extracts highlight clips from the original video.

These clips are then merged to create a final highlights video summarizing the key moments of the match.

## Features
- Automatic cricket highlight generation
- Video processing using FFmpeg
- Event filtering from match footage
- Highlight clip extraction
- Final highlights video creation

## Main Modules

### ipl_filter.py
This module processes the match video and filters important frames or events that may correspond to key match moments.

### ipl_highlight_generator.py
This module generates highlight clips around detected events and merges them into the final highlights video.

## Technologies Used
- Python
- NumPy
- FFmpeg
- FastAPI
- Whisper

## Installation

Clone the repository 

git clone https://github.com/AbinayaEV37/Cricket_highlights_prototype


## Move into the project folder

cd Cricket_highlights_prototype


## Install dependencies

pip install -r requirements.txt


Install FFmpeg (required for video processing)

https://ffmpeg.org/download.html

## How to Run

## Run the main scripts:

python ipl_filter.py
python ipl_highlight_generator.py


These scripts process the match video, detect highlight events, and generate the final highlights video.

## Output

The system generates:

- Final highlights video **ipl_final.mp4**

## System Architecture

The system follows a pipeline-based architecture to generate highlights automatically from a full-length cricket match video.

Input Match Video  
→ Video Processing (FFmpeg)  
→ Event Filtering (ipl_filter.py)  
→ Highlight Detection  
→ Clip Generation (ipl_highlight_generator.py)  
→ Final Highlight Video (ipl_final.mp4)


Each stage processes the video data and passes the relevant information to the next stage to produce the final highlights video.

## Project Workflow

Full Match Video  
↓  
Video Processing  
↓  
Event Filtering  
↓  
Highlight Detection  
↓  
Clip Extraction  
↓  
Final Highlights Video

## Notes
This project is a prototype implementation for automatic cricket highlight generation from full match videos.

## Team Members

This project was developed as part of a team assignment.

- Abinaya E V
- Monica K
- Mohanalakshmi S
- Gopika S
- Lakshmi sri sanjana P V
