1) values added:  20
2) final result:  20
3) You generally don’t want to use var because it can behave in confusing ways. Since it's not constrained to the block it shows up in, it can show up in other unexpected places. 
4) values added:  20
5) The code returns the error saying result is undefined. This happens because the result variable is only accessible inside of the if block since it was declared with a let inside the block.
6) Line 9 doesn't print because an error is returned saying assignment to const variable. This happens because you cannot reassign a const variable and the result variable is being reassigned.
7) Line 13 doesn't print since the function stops at the error at line 7.