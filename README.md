# Claude Strategist

**⚠️ Early Proof of Concept - Not Production Ready**

This is a basic framework demonstrating how AI could transform business inputs into strategic deliverables. The current prompts are quickly created for testing the concept only.

## What This Does

Converts business inputs (OKRs, backlog items, stakeholder interviews) into strategic outputs through a 10-step AI-powered process:

1. Strategic Analysis → Pain clustering
2. Baseline Metrics → Performance measurement
3. Vision Creation → Future-state narratives
4. Strategic Pillars → Theme grouping
5. Backlog Prioritization → Impact-effort scoring
6. Solution Design → User stories and scope
7. Release Planning → Multi-quarter roadmaps
8. Risk Management → Mitigation strategies
9. Presentation Creation → Slide outlines
10. Stakeholder Alignment → Feedback synthesis

## Quick Start

1. **Replace the example data** - The examples are toy data. Replace with your actual business inputs.
2. **Remove output files** - Delete any existing outputs so Claude can generate fresh analysis.
3. **Run steps 1-10** - Execute each prompt sequentially with an AI assistant.

## How to Execute This Framework

1. **Clone the Repository**

   - Clone or download this repository to your local machine. You can use tools like Cursor or Windsurf for the best experience.

2. **Open in Cursor or Windsurf**

   - Launch Cursor or Windsurf and open the project folder.

3. **Run Claude Code**

   - There is no special script or command to run. Just run Claude Code in Cursor or Windsurf and ask it to execute the steps.

4. **Recommended: Start with Plan Mode**

   - For best results, use "plan mode" first:
     - Press <kbd>Shift</kbd> + <kbd>Tab</kbd> in Claude Code to activate plan mode.
     - This will let Claude explain what it will do before running the step, so you understand the process.

5. **Proceed Through Steps**

   - After reviewing the plan, let Claude execute the step.
   - Continue sequentially through all 10 steps, using your own business data in the `context/` folder and generating outputs in the `output/` folder.

6. **No Special Prompts Needed**
   - You do not need to craft custom prompts—just follow the step files and let Claude handle the rest.

## Important Caveats

- **Version 0.1** - Basic prompts that will likely change significantly
- **Not plug-and-play** - Requires refinement of prompts, inputs, and process
- **Toy example** - Based on fictional data for illustration only
- **Proof of concept** - Demonstrates potential, not production-ready strategy

## Future Potential

Once prompts are refined and inputs are quality, this approach could automate strategic planning that typically takes weeks. Current version is just to test the core idea.

## Files

- `process/` - 10 sequential prompt files
- `context/` - Replace with your actual business data
- `output/` - Delete before running to generate fresh analysis

---

_This framework illustrates what's possible with AI-assisted strategic planning, not what's ready today._
