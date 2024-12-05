<b>
Optimal Page Replacement Algorithm

Aim:

Implement the Optimal page replacement algorithm for minimizing page faults.

Description:

The Optimal page replacement algorithm predicts future page references to minimize page faults by replacing the page that will not be used for the longest time in the future.

Algorithm:

Initialize page frames with -1
For each page in the reference string:

If page not in frame, increment page fault
If frame not full, add page
If frame full, find page to replace using future reference prediction


Track and display page faults

Output :
Enter the number of pages (<1000):
10
Enter 10 pages:
1 2 3 3 4 3 2 1 2 3
Enter the number of frames (<100):
2
PAGE FAULTS = 7
</b>
