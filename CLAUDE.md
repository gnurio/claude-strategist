# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a **strategic analysis framework** designed to transform business stakeholder feedback into actionable strategic insights. The repository contains a 10-step process that converts raw business inputs (OKRs, backlog items, stakeholder interviews) into comprehensive strategic deliverables including vision narratives, roadmaps, and presentation materials.

## Architecture

The project follows a **sequential prompt-based architecture** with 10 distinct processing steps:

### Core Workflow (process/ directory)
- **Step 1**: Strategic Analysis - Synthesizes OKRs, backlog items, and stakeholder interviews into pain clusters and unified problem statements
- **Step 2**: Baseline Metrics - Maps pain clusters to measurable data points and identifies performance red zones
- **Step 3**: Vision Creation - Develops future-state narratives with North-Star metrics and supporting KPIs
- **Step 4**: Strategic Pillars - Groups pain clusters into 3-4 strategic themes with purposes, target metrics, and non-goals
- **Step 5**: Backlog Prioritization - Ranks initiatives using Impact-Effort scoring against pillar alignment
- **Step 6**: Solution Design - Creates user stories, success hypotheses, and scope definitions for top opportunities
- **Step 7**: Release Planning - Builds 6-quarter roadmaps with capacity management and tech-debt allocation
- **Step 8**: Risk Management - Performs pre-mortem analysis and creates mitigation strategies
- **Step 9**: Presentation Creation - Generates slide outlines with speaker notes and visual recommendations
- **Step 10**: Stakeholder Alignment - Synthesizes feedback and creates approval tracking mechanisms

### Template Variables
Each step uses placeholder variables (e.g., `{{COMPANY_TEAM_OKRS}}`, `{{BACKLOG_ITEMS}}`, `{{STAKEHOLDER_INTERVIEW_NOTES}}`) that must be populated with actual business data before execution.

### Data Flow
The output from each step becomes input for subsequent steps, creating a cascading analytical pipeline that builds comprehensive strategic artifacts from raw business inputs.

## Usage

### Running the Process
1. Replace template variables in step files with actual business data
2. Execute steps sequentially (1-10) using the prompts as LLM instructions
3. Each step's output feeds into the next step's input variables
4. Final deliverables include strategic decks, roadmaps, and alignment tracking

### Key Input Requirements
- **OKRs**: Company/team objectives and key results
- **Backlog Items**: Existing feature requests and technical debt
- **Stakeholder Interviews**: Pain points and requirements from internal users
- **Engineering Capacity**: Quarterly development capacity assumptions
- **Raw Data**: Performance metrics and operational data

### Output Deliverables
- Insight briefs with pain cluster analysis
- Baseline metrics dashboards with red zone identification
- Vision narratives with North-Star metrics
- Strategic pillar frameworks
- Prioritized opportunity lists
- Solution brief packs
- 6-quarter roadmaps with resource requirements
- Risk registers with mitigation strategies
- Executive presentation outlines
- Stakeholder approval tracking