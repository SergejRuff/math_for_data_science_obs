Code:

# generate Matrix test and matrix test 2 which have the same dimensions.
test <-  matrix(c(1,2,3, 11,12,13), nrow = 2, ncol = 3, byrow = TRUE,
                dimnames = list(c("row1", "row2"),
                                c("C.1", "C.2", "C.3")))

test2 <-  matrix(c(1,2,3, 11,12,13), nrow = 2, ncol = 3, byrow = TRUE,
                 dimnames = list(c("row1", "row2"),
                                 c("C.1", "C.2", "C.3")))

print(test)
print("------")
print(test2)
print("-----")
print(test2+test)

# repeat the addition but now with matrix of unequal length to demonstrate error
# and why you cant use addition.
test <-  matrix(c(1,2,3, 11,12,13), nrow = 2, ncol = 3, byrow = TRUE,
                dimnames = list(c("row1", "row2"),
                                c("C.1", "C.2", "C.3")))

test2 <-  matrix(c(1,2,3,4, 11,12,13,14), nrow = 2, ncol = 4, byrow = TRUE)

print(test)
print("------")
print(test2)
print("-----")
print(test2+test)


Output:

print(test)
     C.1 C.2 C.3
row1   1   2   3
row2  11  12  13


> print(test2)
     C.1 C.2 C.3
row1   1   2   3
row2  11  12  13
> print("-----")


> print(test2+test)
     C.1 C.2 C.3
row1   2   4   6
row2  22  24  26

Output for unequal dim:

> print(test)
     C.1 C.2 C.3
row1   1   2   3
row2  11  12  13

print(test2)
  1    2    3    4
  11   12   13   14

print(test2+test)
Error in test2 + test : non-conformable arrays