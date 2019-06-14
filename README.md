# Select-a-Subset-from-big-data-
Select subset for regression 
  states.en.met.pop.wst <- subset(states, select = c("energy", "metro", "pop", "waste"))
  summary(states.en.met.pop.wst)
