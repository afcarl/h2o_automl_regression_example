# H2O.ai regression example

Regression is not well documented in the h2o.ai documentation.  So I present one in this repo.

The key to doing regression is here:

`aml = H2OAutoML(max_runtime_secs = 30, stopping_metric="deviance")`

specifically, `stopping_metric="deviance"`.

With this the AutoML routinue does regression.

