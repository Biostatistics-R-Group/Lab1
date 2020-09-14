# Lab1
Space for working recommendations on translating Lab 1 from Stata to R

Oh-- come edit this document with comments :

# If_else command help
I've been working with case_when, but it bothers me that I can't get the hang of the if_else() command
This link was pretty useful and I'm sure I'll be returning to it.
https://rstudio-pubs-static.s3.amazonaws.com/116317_e6922e81e72e4e3f83995485ce686c14.html#/

my code for the lab looks like this

kenya <- kenya %>%
  mutate(male2 = if_else(b4 ==2, "0", "1"))
  
 So simple!

-Nathan 


