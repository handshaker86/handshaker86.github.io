---
layout: page
title: Gomoku AI
description: An Intelligent Gomoku Game with Classical AI Search Algorithms
img: assets/img/project_preview/Gomuku_AI.png
importance: 2
category: fun
github: https://github.com/handshaker86/Gomoku_AI
---

A Python-based Five-in-a-Row game with an AI opponent powered by **Minimax + Alpha-Beta Pruning**, **Zobrist Hashing**, and **Iterative Deepening** (up to depth 7, 2s time limit).

The evaluation system performs **shape recognition** across four directions (live/blocked fours, threes, double threats) with **incremental scoring** for efficient leaf node evaluation. Three difficulty levels: Easy (greedy), Medium/Hard (minimax search).

Built with Python, NumPy, and Tkinter. Supports Player vs AI and local PvP modes.
