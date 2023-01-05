1.Check if a number is palindrome

```matlab

Number = 121

s = num2str(Number) - '0';

Reversed_Number = polyval(s(end:-1:1),10);


    if (Number==Reversed_Number)
        disp('the no. is palindrome');
    else
        disp('the no. is not palindrome');
    end
    ```
