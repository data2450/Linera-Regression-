# Regularisation
way to prevent overfitting and thus improve the likely generalization performance of a model by restrecting the models possible parameter settings.This restriction reduce complexity of the final estimated model

The influence of regularization is controlled by the alpha parameter .Higher alpha means more regularization and simple models

Regularization works well when you have relatievly small amount of training data compared to the number of features in youre model,less important when amount of training data increses

# Ridge regularization
It's a regularization the linear regression by imposing that sum of squres of the W coeffients(slops).so the effect of incresing alpha is to shrinkage of W coeffients towards zero
and towards each other

# Lasso regularization
In lasso the regularization penality is sum of absolute value of the Coefficients

# when to use ridge vs lasso
>when we have many features with medium or small sized effect on output varible we use ridge

>when we have only a few varibles with medium or large effect on the output we use lasso
