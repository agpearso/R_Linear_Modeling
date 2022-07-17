## Linear modeling ##

?lm

## Predict y based on x and other independent variables if necessary##

lm.y_x=lm(y~x+x_1+x_n)

summary(lm.y_x)
lm.beta(lm.y_x)
