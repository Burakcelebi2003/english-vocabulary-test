# english-vocabulary-test
An interactive English vocabulary testing application developed with Python, Streamlit, SQL and JSON.

Project Overview

Color League is a gamified English vocabulary learning application designed to turn repetitive vocabulary practice into a competitive league experience. Originally developed for YDS (Foreign Language Proficiency Exam) preparation, the application combines vocabulary recall with a football league simulation, making language revision more interactive, engaging, and sustainable.

Instead of following a conventional flashcard or vocabulary-testing format, users compete through teams represented by different colors and emojis. Each team participates in a full league season, earning points based on vocabulary knowledge.

Game Mechanics

12 Teams: The league consists of 12 teams, each represented by a unique color and emoji.

22-Week Season: A double round-robin fixture ensures that every team faces every other team twice, once at home and once away.

20 Questions per Match: Each match consists of 20 randomly selected vocabulary questions.

Alternating Turns: Teams answer questions alternately, with each correct answer earning one point.

League Scoring: Match results determine the standings:

Win: 3 points

Draw: 1 point

Loss: 0 points

Derby Matches: Selected rivalries receive special visual highlights to add another competitive element.

League Management & Statistics

The application automatically tracks and updates league statistics throughout the season.

Matches played, wins, draws, and losses.

Goals scored and conceded (AG/YG).

Goal difference.

Total league points.

Weekly fixtures and completed match results.

Dynamic league standings based on points, goal difference, and goals scored.

The application also features a historical championship archive, tracking season champions and cumulative championship titles.

Historical Championship Database

Color League includes a predefined historical championship database covering the 1986–2025 seasons.

This module provides:

Season-by-season championship records.

Total championship counts for each team.

Historical comparisons between teams.

Automatic updates when a new season is completed.

Vocabulary Database & Customization

The vocabulary database is maintained through a CSV file (Vocabulary.csv), allowing the question pool to be updated independently of the game's core logic.

The database supports:

English vocabulary entries.

Turkish definitions and alternative meanings.

Random sampling of 20 words for each match.

Flexible vocabulary replacement and expansion.

The system can also be adapted to different learning environments. Users can replace the original color-based teams with custom names, emojis, or other thematic identities. Furthermore, the vocabulary database can be refreshed using data extracted from SQL databases, making it possible to integrate different vocabulary collections and learning objectives.

Persistence & Data Management

Game progress is stored in a local JSON file (renkler_ligi_hafiza.json), preserving the league's state between application sessions.

The system maintains:

Current season and match progress.

Team standings.

Fixture structure.

Individual match results.

Historical champions and championship totals.

Active match questions and scores.

This allows users to resume an ongoing season without losing previously recorded results.

Technology Stack

Python: Core application logic and game mechanics.

Streamlit: Interactive web application and user interface.

Pandas: Vocabulary processing, data management, and league standings.

NumPy: Randomization and fixture generation.

JSON: Persistent storage of league data and game progress.

CSV: External vocabulary database.

Project Objective

The main objective of Color League is to demonstrate how conventional language-learning activities can be transformed into interactive, data-driven experiences through programming.

By combining vocabulary revision, randomized question selection, competitive scoring, historical tracking, and customizable databases, the project offers a reusable framework for gamified learning.

Although initially designed for personal YDS vocabulary practice, its modular structure allows it to be repurposed for other languages, vocabulary collections, and educational environments.
