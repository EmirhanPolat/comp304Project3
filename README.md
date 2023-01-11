# comp304Project3
For this project, we are expected to simulate the paging behavior of OS systems.
---PART1---
Since we divide each tlbentry by half and assigning logical and physical addresses to their fields,
we first need to find the corresponding integers to mask the first and second half of the logical address
I have found the corresponding bit sequence using the https://www.rapidtables.com/convert/number/decimal-to-binary.html

Then I needed to implement search_tlb and add_to_tlb functions
