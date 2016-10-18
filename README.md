# week-1
# plot 1
Copy and paste rows with date=1/2/2007 and 2/2/2007 to another text file named as HPC_Useful

> HPC_Useful <- read.csv("~/Analytic training/Coursera/Week 1/HPC_Useful.txt", sep=";")
>   View(HPC_Useful)
> summary(HPC_Useful)
> attach(HPC_Useful)
> hist(Global_active_power)
> hist(Global_active_power, col = "red", main = "Global Active Power",xlab = "Global Active Power (kilowatts)", ylim = c(0,1200))
