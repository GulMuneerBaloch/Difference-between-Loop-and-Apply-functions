Duckweed.mat <- matrix(c(1:10, 11:20, 31:40, 41:50, 51:60, 61:70), nrow = 10, byrow =  F)
rownames(Duckweed.mat) <- c("D1", "D2", "D3", "D4", "D5", "D6", "D7", "D8", "D9", "D10")
colnames(Duckweed.mat) <- c("R1", "R2", "R3", "R4", "R5", "R6")
duck <- Duckweed.mat
class(duck)
max(duck[1,])
max(duck[2,])
max(duck[,6])

for (i in 1:10) {
  row1 <- duck[i,]
  max1 <- max(row1)
  print(max1)
}

apply(duck, 1, max)
