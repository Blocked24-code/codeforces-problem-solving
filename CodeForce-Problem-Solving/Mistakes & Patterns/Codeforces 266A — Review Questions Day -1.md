

**Problem:** [266A — Stones on the Table](https://codeforces.com/problemset/problem/266/A)

## Part 1: Algorithm Understanding

**Q1.** Why does a group of `k` identical neighboring stones require `k - 1` removals?

**Q2.** For the string `RRRGGR`, how many adjacent pairs match?

**Q3.** For the same string, how many removals are required?

**Q4.** Why can we count matching adjacent pairs without physically removing stones after every comparison?

## Part 2: C++ Strings

**Q5.** What does `s.size()` tell us?

**Q6.** If a string has length 5, what are its valid indices?

**Q7.** If a loop compares `s[i]` with `s[i + 1]`, why must we protect the second index?

**Q8.** What is the difference between a C-style character array and a C++ `string` when determining the end of the text?

## Part 3: Debugging

**Q9.** Why did selecting GNU C11 cause a problem for code that used `iostream`?

**Q10.** Which kind of compiler option should be selected for C++ code?

**Q11.** What is the purpose of including the `<string>` header when using `std::string`?

**Q12.** When a compiler reports several errors, why is it useful to investigate the first error first?

## Part 4: Reflection

**Q13.** Which part of the problem did I solve independently?

**Q14.** Which part required debugging help?

**Q15.** If I receive a similar compilation error again, what will I check first?

## Completion Checklist

- I can explain why matching adjacent pairs determine the number of removals.
    
- I can calculate the number of removals for a short string.
    
- I understand valid string indices.
    
- I can explain the difference between C and C++ compiler configurations.
    
- I can diagnose the next similar error with less help.