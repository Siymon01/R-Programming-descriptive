# R-Programming-descriptive

install.packages("psych")
install.packages("gmodels")
install.packages("Hmisc")
load("C:/Users/HP/Desktop/hospital1.RData")
View(hospital1)
View(hospital1)
attach(hospital1)
t.test(los~age80)
library(psych)
describeBy(agecat~los)
describeBy(los~agecat)
describeBy(hospital1$agecat,hospital1$los)
describeBy(hospital1$age,hospital1$los)
describeBy(hospital1$agecat,hospital1$los)
describeBy(hospital1$age80,hospital1$los)
describeBy(hospital1$los)
describeBy(hospital1$los,hospital1$gender)
describeBy(hospital1$los,hospital1$agecat)
los.aov<- aov(agecat~los)
install.packages("ANOVAShiny")
los.aov<
anova(agecat,los)
anova(agecat,los)
df<- data.frame(los,agecat)
ageg.aov<-aov(agecat~los, data =df)
summary(ageg.aov)
summary.aov(agecat,los)
summary.aov(agecat$los)
table(agecat)
summary(aov(los~agecat))
TukeyHSD(aov(los~as.factor(agecat)))
cor.test(los~tiadlmean)
cor.test(los$tiadlmean)
cor.test(hospital1$los, hospital1$tiadlmean)
save(hospital.Rdata,file = "C/hospital.rdata")
View(hospital1)
attach(hospital1)
load("C:/users/HP/Desktop/hospital1.RData")
table(agecat)
View(hospital1)
attach(hospital1)
t.test(los~age80)
