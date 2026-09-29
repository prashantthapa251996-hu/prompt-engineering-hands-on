# Prompt Engineering Hands-On

## Project Overview

This project demonstrates how prompt engineering techniques can improve AI-generated content.

The project compares simple **Before prompts** with optimized **After prompts** across six different content types.

## Project Objective

The objective of this project is to:

- Understand different prompt engineering techniques
- Create optimized prompts for different content types
- Compare Before and After AI outputs
- Evaluate improvements using specific quality criteria
- Document the prompt engineering process

## Content Types

The project covers the following six content types:

1. Blog
2. LinkedIn Post
3. Email
4. Instagram Caption
5. YouTube Script
6. Product Description

## Prompt Engineering Techniques

| Content Type | Technique |
|---|---|
| Blog | RGCCO + Style Transfer |
| LinkedIn | Role Prompting + Zero-Shot |
| Email | One-Shot Prompting |
| Instagram | Few-Shot Prompting |
| YouTube | Role Prompting + RGCCO |
| Product Description | Few-Shot Prompting |

## Repository Structure

| File | Description |
|---|---|
| `Before-Prompts.md` | Original prompts used before optimization |
| `prompt_library.md` | Optimized prompts and prompting techniques |
| `generated_content.md` | AI-generated Before and After content |
| `improvement_report.md` | Quality comparison and analysis |

## Quality Evaluation

Each Before and After output was evaluated using four criteria:

- **Relevance**
- **Tone**
- **Formatting**
- **Length**

Each criterion was scored from **1 to 5**:

| Score | Meaning |
|---|---|
| 1 | Poor |
| 2 | Needs Improvement |
| 3 | Acceptable |
| 4 | Good |
| 5 | Excellent |

The maximum score for each output is **20/20**.

## Before vs. After Comparison

| Content | Version | Relevance | Tone | Formatting | Length | Total |
|---|---|---:|---:|---:|---:|---:|
| Blog | Before | 4 | 4 | 4 | 4 | **16/20** |
| Blog | After | 5 | 5 | 5 | 5 | **20/20** |
| LinkedIn | Before | 4 | 4 | 4 | 4 | **16/20** |
| LinkedIn | After | 5 | 5 | 5 | 5 | **20/20** |
| Email | Before | 4 | 3 | 4 | 4 | **15/20** |
| Email | After | 5 | 5 | 5 | 5 | **20/20** |
| Instagram | Before | 5 | 4 | 5 | 5 | **19/20** |
| Instagram | After | 5 | 5 | 5 | 5 | **20/20** |
| YouTube | Before | 4 | 4 | 3 | 4 | **15/20** |
| YouTube | After | 5 | 5 | 5 | 3 | **18/20** |
| Product | Before | 4 | 4 | 4 | 4 | **16/20** |
| Product | After | 5 | 5 | 5 | 2 | **17/20** |

## Overall Results

| Version | Score |
|---|---:|
| Before | **97/120** |
| After | **115/120** |
| Improvement | **+18 points** |

## Assessment Sections

The improvement report contains four sections for each content type:

1. **Objective**
2. **Issue with the Before Prompt**
3. **After Strategy**
4. **Quality Comparison Summary**

## How to Use This Repository

1. Review the original Before prompts.
2. Review the optimized After prompts.
3. Compare the generated outputs.
4. Review the quality scores.
5. Read the improvement analysis for each content type.

## Challenges / Assumptions

The main challenge was ensuring that each optimized prompt included enough context and constraints to produce a more specific output.

The comparison was based on Relevance, Tone, Formatting, and Length.
