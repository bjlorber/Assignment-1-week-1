# Assignment-1-week-1
install.packages("ggplot2")
install.package("dplyr")
> #this next line is creating a subset called 'small' of the diamonds data
> small <- diamonds %>% 
+   filter(carat <= 2)
> #This next chunk is inline code. Inline code puts the text with the output of the function in my document.
> #This next code chunk will make a plot in our output doc
> small %>% 
+   ggplot(aes(carat)) + 
+   geom_freqpoly(binwidth = 0.01)
> #Once all of my code has been written, I click on the Knit button in the tool bar above to produce my document.

![image](https://user-images.githubusercontent.com/117047285/214909239-4a579eed-f908-4e42-887d-528f82e2ce30.png)
