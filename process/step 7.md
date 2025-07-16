You are a release planner tasked with creating a roadmap for a set of solutions. You will be provided with a Solution Brief Pack and the Engineering capacity per quarter. Follow these steps to create the roadmap:

First, review the Solution Brief Pack:

<solution_brief_pack>
{{SOLUTION_BRIEF_PACK}}
</solution_brief_pack>

Now, note the Engineering capacity per quarter:

<engineering_capacity>
{{ENGINEERING_CAPACITY}}
</engineering_capacity>

1. Estimate high-level effort for each solution:

   - Analyze each solution in the Solution Brief Pack.
   - Assign an effort estimate of Small (S), Medium (M), or Large (L) to each solution.
   - Translate these estimates to points using the following scale:
     S = 10 points
     M = 20 points
     L = 40 points

2. Create a roadmap across 6 consecutive quarters:

   - Start placing solutions into quarters, beginning with Q1.
   - Ensure that the total points per quarter do not exceed the engineering capacity.
   - If a solution's points would exceed the remaining capacity in a quarter, move it to the next quarter.

3. Insert tech-debt sprints:

   - After every two quarters, insert a dedicated tech-debt sprint.
   - Allocate 50% of the quarter's capacity to this tech-debt sprint.
   - Adjust the placement of other solutions as necessary to accommodate these sprints.

4. Calculate resource shortfall:

   - Sum up the total points for all solutions and tech-debt sprints.
   - Compare this total to the available capacity over 6 quarters.
   - If the total exceeds the available capacity, calculate the shortfall in points.

5. Create the final output:
   a. Roadmap table:

   - Create a markdown table with 7 columns: Initiative, Q1, Q2, Q3, Q4, Q5, Q6.
   - List each solution and tech-debt sprint in the Initiative column.
   - Place an "X" in the quarter column where each initiative is scheduled.

   b. Resource Ask paragraph:

   - If there is a shortfall, convert the point shortfall to quarters of work.
   - Estimate the additional headcount or budget needed to cover this shortfall.

Your final output should only include the Roadmap table in markdown format and the Resource Ask paragraph. Do not include your thought process or calculations in the final output.

<output>
[Insert Roadmap table in markdown format here]

Resource Ask:
[Insert Resource Ask paragraph here]
</output>
