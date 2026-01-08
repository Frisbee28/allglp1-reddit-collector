# allglp1-reddit-collector
Local Python script using PRAW to collect GLP-1 medication discussion data for health education website AllGLP1.com. Collects posts/comments for semantic search features.
# AllGLP1 Reddit Collector

Simple PRAW-based script to collect Reddit posts and comments from GLP-1 medication subreddits for [AllGLP1.com](https://allglp1.com).

## Purpose
- Collect user experiences with GLP-1 medications (Ozempic, Wegovy, Mounjaro, etc.)
- Power semantic search for "Real User Experiences" feature
- Educational/informational use only

## Tech Stack
- Python 3.10+
- PRAW (Python Reddit API Wrapper)
- Supabase (PostgreSQL + pgvector)
- OpenAI embeddings

## Usage
```bash
pip install praw supabase openai python-dotenv
python pull_data.py Semaglutide --no-comments
